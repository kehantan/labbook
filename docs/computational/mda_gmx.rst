MDAnalysis vs GROMACS
=====================

* MDA least square fit to the group that we want to calculate the RMSD, the RMSD value will appears lower.  

Remove PBC and center complex in MDA 
----

* MDA is not really good in remove PBC and centering proteins in box, especially for multiple chain proteins. GMX still does a better job in this regard
* For stubborn complexes, things that does not works: 

    * centering on one chain then on another
    * centering on larger chain 
    * centering on protein-ligand 
    * centering on protein only 
    * :code:`transformations.NoJump(check_continuity=True)` can greatly reduce the spaghetti, but still some small problem, which in the end will affect the RMSD calculation
    * So, to get good RMSD calculations, either fix the problem completely, or find some other ways, half ass fixing the problem will not do any good 
