Molecular docking
=================
There are two place you can do molecular docking: running molecular docking at local machine (means your computer/laptop); OR using server (does not need your computer/laptop). There are of course pros and cons of using different ways. 

Running molecular docking using server
--------------------------------------

For easy work, I would suggest running molecular docking using server like `MTiOpenScreen <https://bioserv.rpbs.univ-paris-diderot.fr/services/MTiOpenScreen/>`_. Most of the work would be automated by the server, you just have to run and retrieve your results. Other advantages including able to run molecular docking with multiple protein receptor or ligands in one go. 

Scripting skill are not strictly required, but it can be really handy for navigating files and for result analysis a lot more easier if you have some knowledge of it. 

**Requires**

* MGLTools/AutoDockTools
* BIOVIA Discovery Studio Visualizer 

    You don't strictly have to use this one. There are other molecule visualiser out there you can try it out like PyMOL, Chimera, etc.)

Running molecular docking on local machine
------------------------------------------

If you wanted to run molecular docking on your own machine, a little bit of scripting skill are required. It is needed for navigating files and for result analysis.  

**Requires**

* Autodock Vina
* MGLTools/AutodockTools
* BIOVIA Discovery Studio Visualizer

**Workflow** 

#. Receptor prepare
#. Ligand prepare
#. Define box 
#. Molecular docking
#. Result analysis 

**FAQ**

*Q: How long does it take to run molecular docking?*

Depends on a lot of factors: number and size of protein receptor, number of ligands, performance of the machine, parameters your set (e.g.: exhaustiveness 8 vs 100) etc. 

But for reference purpose:

* 1 protein receptor of around 300 amino acid residues
* 1 ligand of around 50 atoms
* 5 years old computer
* default exhaustiveness of 8 in AutoDock Vina

should take less than 3 mins to complete 1 molecular docking procedure. 

*Q: I have a powerful laptop/computer, can I run molecular docking on my machine?*

Depends on the level of seriousness you wanted to run molecular docking on your own machine. Technically you can, but I would not encourage you to run serious molecular docking (e.g: molecular docking with large number of ligands, multiple large protein receptors,  that requires long running time) for below reasons: 

  * Workstations and servers are build for durability especially running for long hours at full blast speed. Workstations and servers also have effective heat dissipation system to cool the silicon chips. Consumer grade electronics usually does not have similar durability and efffectivity. This might affect the lifespan of your laptop/computer.
  * Molecular docking typically uses full power of your machine (uses 100% of cpu power). So if that is your only device, you may not be able to use it for other work or you may find it lagging even when doing simple task, because molecular docking is running in background. 

You can still do molecular docking on your machine if you just wanted to try it out and run a simple molecular docking which only takes like 5 mins.
