Prepare files for molecular docking 
====

There are two ways of using ADT, either using the graphical user interface (GUI) as demonstrated in most tutorials, or use the python script to convert receptor or ligand from pdb/mol2 to pdbqt in batch. 

Protein receptor
----

* ADT

:code:`/opt/mgltools_x86_64Linux2_1.5.7/bin/pythonsh /opt/mgltools_x86_64Linux2_1.5.7/MGLToolsPckgs/AutoDockTools/Utilities24/prepare_receptor4.py receptor.pdb -A bonds_hydrogens`

Ligand
----

* OpenBabel
* ADT

**OpenBabel**

:code:`obabel -i pdb lig.pdb -o pdbqt -O lig.pdbqt`

Ligand generated this way can exeed the torsion limit of 32. But whether AutoDock Vina will actually apply all the torsions when the number of torsions is more than 32 is not known (most probably not, to keep it safe check torsion in ``.pdbqt`` file before running docking). 

**ADT**

:code:`/opt/mgltools_x86_64Linux2_1.5.7/bin/pythonsh /opt/mgltools_x86_64Linux2_1.5.7/MGLToolsPckgs/AutoDockTools/Utilities24/prepare_ligand4.py lig.pdb -A bonds_hydrogens`