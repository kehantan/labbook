Open Babel
==========
Open Babel is a handy tool for computational chemistry which have multiple functions. Some of the functions that I regularly used including:

* convert between different file formats (e.g.: from .pdb to .mol)
* generate 3D coordinates with option ``--gen3d``
* energy minimise a molecule

Installation
------------
Open Babel is mainly a terminal tool, which you run in the terminal. There are GUI interface, but I am not familiar with it. 

There are multiple ways to install Open babel:

#. From repository 

    By typing ``sudo apt install openbabel`` into the terminal

#. From Anaconda

    By typing ``conda install -c conda-forge openbabel`` into the terminal 

*Note: If you want to use Open Babel on Windows, I would suggest installing it via Anaconda.*

Usage
-----
In the terminal, type 

    ``obabel -i <type of input file> <name of input file> -o <type of output file> -O <name of output file> [options]``

For example, 

    ``obabel -i pdb ligand.pdb -o mol2 -O ligand.mol2``

Sometimes when you download a ligand file in sdf format, it does have 3D coordinates. You can do 

    ``obabel -i sdf ligand.sdf -o pdb -O ligand.pdb --gen3d``

to generate a pdb file with 3D coordinates
