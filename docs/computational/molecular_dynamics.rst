Molecular dynamics
==================

Molecular dynamics (MD) is very much different from molecular docking. The MD engine I am using is GROMACS, there are other MD engine you can use like AMBER or NAMD.   

Visual guide from my `google drive <https://drive.google.com/drive/folders/108psm8MTCf70OTOE96ehjELQ3mR2w1v2?usp=sharing>`_ on how to run MD. 


**Workflow**

#. Protein/receptor preparation
#. Ligand preparation
#. Define new box and solvation
#. Add ions and water molecules
#. Energy minimisation
#. Equilibration
#. Production

**Analysis**

Common analysis for MD simulation including:

* Root mean square deviation (RMSD)
* Root mean square fluctuation (RMSF)
* Free binding energy (**M**\ olecular **M**\ echanics **P**\ oisson-\ **B**\ oltzmann **S**\ urface **A**\ rea, MMPBSA)
* Hydrogen bond interactions

There are native tools built into GROMACS that can be used for MD analysis, but I run most of the analysis using external tools. There are plenty of external tools, the one that I am using is `MDAnalysis <https://www.mdanalysis.org/>`_. 

The choice of using builtin tools or external tools are strictly personal preference. I use MDAnalysis simply because:

* I find it easier to handle multiple trajectories in MDAnalysis.  
* I don't have to install GROMACS on my computer if I just want to run analysis and not running actual MD on my machine. 
* It is operating system agnostic (means I can run my analysis on either Linux or Windows), because it is written in Python programming language, which is also OS agnostic. 
* Since it is written in Python, MDAnalysis can be used together with other Python-based packages in the same environment (by installing all of them using Anaconda), making it a complete ecosystem for analysis of MD trajectories. Some example including:  
  
  * Jupyter notebook - an interface that runs on internet browser, which makes writing python scripts for analysis easier than in terminal, because I can view the output results in the browser itself and make any necessary adjustments within Jupyter notebook. 
  * Matplotlib - Can be loaded into Jupyter notebook. Main function is to plot nicer and more consistent graph from the results of MDAnalysis. 
  * NGLview - I rarely use this, but this is good for generating a movie or show structural information from the MD trajectories. An advantage of this is that I don't have to use external visualisation software like VMD or PyMOL for trajectories. 

**FAQ**

The anser for FAQ is mostly the same as in molecular docking.

*Q: How long does it take to run molecular dynamics?*

    Depends on a lot of factors: number of atoms for the whole system (including protein receptor, ligands, water molecules, ions, etc.), performance of the machine, time scale for simulation, etc. 

*Q: I have a powerful laptop/computer, can I run molecular docking on my machine?*

    For some context, if you just wanted to energy minimise the protein-ligand complex structure, it could take maybe, like a minute or so. If you wanted to do some equilibration, it could be taking 15 to 30 mins. If you wanted to run serious productions with tens and hundreds of nanoseconds, it could take hours or even up to days depending on how many atoms there are in the simulated system and the performance of the machine. 

    Back to the question. Technically you can run MD on your system, but I would not encourage. The reasons are similar to molecular docking. 

      * Workstations and servers are build for durability especially running for long hours 24/7 (days or even months) at full blast speed. Consumer grade electronics usually does not have similar durability. Running MD on your machine might affect its lifespan. 
      * MD simulation typically uses full power of your machine (uses 100% of cpu power). So if that is your only device, you may not be able to use it for other work or you may find it lagging even when doing simple task, because MD is running in background. 

    Depends on which step and how serious you are going to do it. If you wanted to, you can do some energy minimisation for the protein-ligand complex; or if you just wanted to try out MD, you can run MD with a very small protein. I would not recommend running MD on your machine with large number of atoms in the simulated system and a for very long time scale. 
