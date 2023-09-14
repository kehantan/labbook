Homology modelling
==================
I use `SWISS-MODEL <https://swissmodel.expasy.org/>`_ to do homology modelling. The main purpose is to fix missing amino acid residues on protein receptor for molecular docking or molecular dynamics simulation works. 

To validate the homology model, I use `SAVES <https://saves.mbi.ucla.edu/>`_

You can also consider using other software (if you have access to them) or other approaches such as *ab initio* modelling or alphafold. I would suggest alphafold, it is new and fancy ＼(＾▽＾)／

But for real, alphafold2 had shown good results in CASP 14, and you do not need to run on your machine. You can use Alphafold2 with MMseqs2 on Google Colaboratory, but there is a limit on how many amino acid residues you are allowed to run at a time if you using the free service. 
