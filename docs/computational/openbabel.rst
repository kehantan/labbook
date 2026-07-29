Open Babel
==========

Open Babel is a very handy tool for computational chemistry which have multiple functions. 

* convert between different file formats (e.g.: from .pdb to .mol)
* generate 3D coordinates 
* energy minimise a molecule

**Installation**

* Open Babel is mainly a terminal tool, but there are also a GUI interface, Open Babel-GUI. 
* There are multiple ways to install Open babel:

    #. From repository 

        By typing ``sudo apt install openbabel`` into the terminal

    #. From Anaconda

        By typing ``conda install -c conda-forge openbabel`` into the terminal 

*Note: To use Open Babel on Windows, the recommended way is to install via Anaconda.*

Ligand file downloaded may be in sdf format, which does not contains 3D coordinates for its atoms. The ``--gen3d`` option can be used to generate a pdb file with 3D coordinates 

    ``obabel -i sdf ligand.sdf -o pdb -O ligand.pdb --gen3d``