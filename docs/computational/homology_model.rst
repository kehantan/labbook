Homology modelling
==================

`SWISS-MODEL <https://swissmodel.expasy.org/>`_ for homology modelling. The main purpose is to fix missing amino acid residues on protein receptor for molecular docking or molecular dynamics simulation works. 

Insert FASTA sequence and then choose from the list the template to use, usually select the target PDB ID.  

`SAVES <https://saves.mbi.ucla.edu/>`_ to validate the homology model.

Protein preparation
-------------------

For classical MD simulation, the charge and radii calculated is not really used during MD, just the proton position and renaming of residues to match the forcefield used is useful. 

#. Submit homology model to `pdb2pqr and apbs server <https://server.poissonboltzmann.org/>`_. Can run only :code:`pdb2pqr` to get the :code:`.pqr` file, no need to complete the whole procedure.
#. Convert :code:`.pqr` file to :code:`.pdb` file using :code:`openbabel`. Conversion is necessary because GMX does not read :code:`.pqr` directly. 
#. pdb2pqr server also help cap the terminal of protein, but the residue name is assigned to :code:`TER`. GMX will complain about this, so just change the :code:`TER` residue name to match the terminal residue's name. 

Ligand preparation
-------------------

* To do Amber GAFF, use ACPYPE. ACPYPE can be installed via conda and run locally
* To do CHARMM, Submit to CGenFF