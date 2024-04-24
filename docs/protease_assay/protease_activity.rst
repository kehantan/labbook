Protease activity assay
=======================

**Objective:** To quantify the activity of the purified protease. 

This step is required before we do protease inhibition assay with compounds.  

Prepare stock solutions and buffers before we actually start the procedure, preferably one day before the experiment day. Usually the buffers and stock solutions can be stored in 4 C for future use. 

Before we begin the procedure we need to 

* find out the concentration of protease we purified, in uM. 
* Prepare MCA stock solution 

Usually MCA comes in powder form, stored in a brown coloured glass vial. 

To prepare the MCA solution, just resuspend the MCA powder in DMSO. Amount of DMSO to add into the vial can refer to manufacturer manual that comes with the glass vial.  

Then we need to do some calculations to know:

* the volume of protease stock needed to serial dilute into different concentrations and 
* the volume of MCA solution to add to each well (final volume is 100 uL)

**Requires** 

* Buffer (Tris-HCl, pH 8.0, 200 mM)
* Purified protease
* MCA substrate
* Black 96 well plate 

**Procedure**

#. Purified protease is stored in -80 C. Thaw before use.
#. Prepare different concentrations of protease (0 to 20 uM) by diluting the protease stock with buffer. 
#. In a black 96 well plate, add substrate into protease of different concentrations based on calculations. 
#. Incubate. 37 C, 30 mins. 
#. Read plate at 350 nm excitation and 440 nm emission. 
#. If the curve does not reach a plateau, incubate another 30 mins, then read the plate again. 

**Analysis**

Plot the curve of protease activity, find the Vmax and Km value. Use the Km value as the concentration for substrate optimisation.

#. In MS Excel, minus all RFU from the well with 0 uM of protease (means the wells that only have buffer and substrate)
#. Copy the value into GraphPad Prism. Analyse using non-linear regression, Michaelis-Menten module. 
#. The curve should have at least 3 points on plateau. 
#. Go back to MS Excel, using the values after minus blank, devide all value by the slope of MCA standard curve. 
#. Then devide the values by time, e.g.: 30 mins, 45 mins, etc. 
#. That is the reaction velocity. 
#. Plot the reaction velocity in GraphPad Prism, analyse using non-linear regression, Michaelis-Menten module. 
#. Km from reaction velocity should be the same as the Km from the RFU. 