Molecular docking
=====

Molecular docking can be done either at local machine (means your computer/laptop) OR using server (does not need your computer/laptop).

Server
----

* More user friendly, less scripting/command typing involve 
* Example: `MTiOpenScreen <https://bioserv.rpbs.univ-paris-diderot.fr/services/MTiOpenScreen/>`_. 
* Most work will be automated by the server, just have to run and retrieve results
* Other advantages including able to run molecular docking with multiple protein receptor or ligands in one go

**Requires**

* MGLTools/AutoDockTools
* Molecular viewere (eg: BIOVIA Discovery Studio Visualizer, Chimera, PyMOL, etc.)

Local machine (Laptop/PC)
----

* Some scripting/command typing involved. Needed for running molecular docking navigating files, result analysis, troubleshooting, etc. 

**Requires**

* Autodock Vina
* MGLTools/AutodockTools
* Molecular viewere (eg: BIOVIA Discovery Studio Visualizer, Chimera, PyMOL, etc.)

**Workflow** 

#. Receptor prepare
#. Ligand prepare
#. Define box 
#. Molecular docking
#. Result analysis 