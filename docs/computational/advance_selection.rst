Advanced selection in GROMACS
=============================

The protein receptor need to be centered back in to the simulation box for post-MD processing. This step is easier when there are only 1 protein receptor chain. Things will get more complicated when there are more than 1 chain, because there will be a huge fluctuation between the chains. To overcome this problem, we would usually select the important sections on both the chain, ie: the important interacting site (or interface) between 2 chains, or centering the protein receptor chains by using the residues around the binding site as reference. 

Residues around the binding site as reference
---------------------------------------------

In my case, there are 2 chains in the protein receptor and there are 3 important residues, which is known as a catalytic triad. Although all the residues of the catalytic triad located on chain B (which is also the binding site), chain A also interacts with chain B. So I will select residues on the receptor protein (both chain A and chain B) which is within the radius of 0.5 nm (or 5 A) from the center of mass (COM) of the catalytic triad. 

The workflow goes like this: 

#. By using :code:`gmx make_ndx`, select the catalytic triad on chain B 1 by 1 and create their own entries in an index file. In the :code:`gmx make_ndx` prompt, do 

    .. code-block::  
        
        chain B & r 51 
        chain B & r 75 
        chain B & r 135 
 
#. Combine all the entries 

    .. code-block::  

        23|24|25

    This will create group number 26, which contains all the catalytic triad residues from entries created in the step above.

#. :code:`gmx select`

    .. code-block::  

        gmx select -s npt.tpr -f npt_processed.pdb -n index.ndx -on radius.ndx -select "group "Protein" and 0.5 within res_com of group 26"

    This will create an index file named :code:`radius.ndx` which contains all the residues within the radius of 0.5 nm from the COM of the catalytic triad. This can later be used as a reference when trying to centering the whole protein-ligand complex during post MD processing. 
