Advanced selection in GROMACS
=============================

* The protein receptor need to be centered back in to the simulation box for post-MD processing. This step is easier when there are only 1 protein receptor chain. Things will get more complicated when there are more than 1 chain, because there will be a huge fluctuation between the chains. 
* To overcome this problem, i would select the important sections on both the chain, ie: the important interacting site (or interface) between 2 chains, or centering the protein receptor chains by using the residues around the binding site as reference. 

Residues around the binding site as reference
---------------------------------------------

* In my case, there are 2 chains in the protein receptor and there are 3 important residues which is the catalytic triad. 
* Although all the residues of the catalytic triad located on chain B (which is also the binding site), chain A also interacts with chain B. So I will select residues on the receptor protein (both chain A and chain B) which is within the radius of 0.5 nm (or 5 A) from the center of mass (COM) of the catalytic triad. 
* The workflow goes like this: 

#. Because :code:`.gro` file does not contain chain information, so cannot select chain if use the :code:`em.gro` as input to make index file. Instead, use :code:`trjconv` to convert :code:`em.gro` to :code:`em_gro.pdb` first, then use that as an input for :code:`gmx make_ndx`. 
#. By using :code:`gmx make_ndx`, select the catalytic triad on chain B 1 by 1 and create their own entries in an index file. In the :code:`gmx make_ndx` prompt, do 

    .. code-block::  
        
        chain B & r 51 
        chain B & r 75 
        chain B & r 135 
 
#. Combine all the entries 

    .. code-block::  

        23|24|25

    * This will create group number 26, which contains all the catalytic triad residues from entries created in the step above.
    * This is just an example, the group number will not necessarily always be 23, 24, and 25. Adjust the group number according to the group entries of your index file. 

#. :code:`gmx select`

    .. code-block::  

        gmx select -s npt.tpr -f npt_processed.pdb -n index.ndx -on radius.ndx -select "group "Protein" and same residue as within 0.5 of res_com of group 26"

    * This will create an index file named :code:`radius.ndx` which contains all the residues within the radius of 0.5 nm from the COM of the catalytic triad. This can later be used as a reference when trying to centering the whole protein-ligand complex during post MD processing. 


Automation
----------

* To automate the creating index file process, create a text file that have the following: 

.. code-block:: 
   
    chain B & r 51 
    chain B & r 75 
    chain B & r 135
    23|24|25
    q

save as something like :code:`triad_ndx.txt`

* Then do

.. code-block::

    gmx make_ndx -f em_cg_gro.pdb -n index.ndx -o triad.ndx < triad_ndx.txt

* Beware of the entry number in the index file, always double check before proceed. 
* To create index file automatically wihtout supplying GROMACS with a seperate text file, the command is slightly longer.  

.. code-block::

    echo -e "chain A \n chain B \n chain A & 4 \n chain B & 4 \n chain B & r 51 \n chain B & r 75 \n chain B & r 135 \n 27|28|29 \n q" | gmx make_ndx -f em_cg_gro.pdb -n index.ndx -o index.ndx  # Creating index file automatically with entries including protein chains and their respective backbone, then combine all the individual groups into a one group
    gmx select -s em_cg.tpr -f em_cg_gro.pdb -n index.ndx -on radius.ndx -select "group "Protein" and same residue as within 0.5 of res_com of group 30"  
    echo -e "31 & 4 \n q" |  gmx make_ndx -f em_cg_gro.pdb -n index.ndx radius.ndx -o index.ndx  # Index group for backbone of the protein residues within the radius
    echo -e "32 0 \n q" | gmx trjconv -s md_0_1.tpr -f trajout.xtc -n index.ndx -o trajout_center_ABinter.xtc -pbc mol -ur compact -center  # Center the protein-ligand complex by using the selected residues as reference, then output the trajectory of the centered protein-ligand complex