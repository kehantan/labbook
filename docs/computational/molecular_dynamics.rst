Molecular dynamics
==================

Visual guide from `google drive <https://drive.google.com/drive/folders/108psm8MTCf70OTOE96ehjELQ3mR2w1v2?usp=sharing>`_ on how to run MD (Not exactly up to date). 

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

There are native tools built into GROMACS that can be used for MD analysis, there are also external tools. Choice of tools used is personal preference. There are plenty of external tools, such as `MDAnalysis <https://www.mdanalysis.org/>`_. 

Pros of using external tools like MDAnalysis: 

* Easier to handle multiple trajectories
* Don't have to install GROMACS on laptop/computer if I just want to run analysis and not running actual MD on local machine 
* It is operating system agnostic (meaning can run analysis on either Linux, Windows, or MacOS), because it is written in Python programming language, which is also OS agnostic (mostly). 
* Since it is written in Python, MDAnalysis can be used together with other Python-based packages in the same environment (by installing them using Anaconda), making it a complete ecosystem for analysis of MD trajectories. Some example including:  
  
  * Jupyter notebook - an interface that uses the internet browser, which makes writing python scripts for analysis easier than in terminal, because the output/results will be displayed in the browser and any necessary adjustments can be made easily
  * Matplotlib - Can be loaded into Jupyter notebook. Main function is to plot nicer and more consistent graph from the results of MDAnalysis
  * NGLview - Good for generating a movie or show structural information from the MD trajectories. Another advantage is that no need to use external visualisation software like VMD or PyMOL to view MD trajectories