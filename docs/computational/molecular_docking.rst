Molecular docking
=================
There are two ways to do molecular docking: either running molecular docking at local machine (means your computer/laptop) or using server (does not need your computer/laptop). There are of course pros and cons of using different ways. 

For easy work, I would suggest running molecular docking using server, like `MTiOpenScreen <https://bioserv.rpbs.univ-paris-diderot.fr/services/MTiOpenScreen/>`_. Most of the work would be automated by the server, you just have to run and retrieve your results. 

Running molecular docking using server
--------------------------------------
Requires
~~~~~~~~
* MGLTools/AutoDockTools
* BIOVIA Discovery Studio Visualizer (You don't strictly have to use this one. There are other molecule visualiser out there you can try it out like PyMOL, Chimera, etc.)

Running molecular docking on local machine
------------------------------------------
Requires
~~~~~~~~
* Autodock Vina
* MGLTools/AutodockTools
* BIOVIA Discovery Studio Visualizer

Workflow 
~~~~~~~~
#. Receptor prepare
#. Ligand prepare
#. Define box 
#. Molecular docking
#. Analysis 

FAQ
---
*Q: How long does it take to run molecular docking?*

Depends on a lot of factors: number and size of protein receptor, number of ligands, performance of the machine, parameters your set (e.g.: exhaustiveness 8 vs 100) etc. 

But for reference purpose:

* 1 protein receptor of around 300 amino acid residues
* 1 ligand of around 50 atoms
* 5 years old computer
* default exhaustiveness of 8 in AutoDock Vina

should take less than 3 mins to complete 1 molecular docking process. 

*Q: I have a powerful laptop/computer, can I run molecular docking on my machine?*

Depends on the level of seriousness you wanted to run molecular docking on your own machine. Technically you can, but I would not encourage you to run serious molecular docking (e.g: molecular docking with large number of ligands that requires long running time) for below reasons. 

* Workstations and servers are build for durability especially running for long hours at full blast speed, consumer grade electronics usually does not have similar durability. This might affect the lifespan of your laptop/computer
* Molecular docking typically uses full power of your machine (uses 100% of cpu power). So if that is your only device, you may not be able to use it for other work or you may find it lagging even when doing simple task, because molecular docking is running in background. 

You can still do molecular docking on your machine if you just wanted to try it out and run a simple molecular docking which only takes like 5 mins.
