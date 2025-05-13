Protease activity assay
=======================

**Objective:** To quantify the activity of the purified protease. 

We need to know:

* the volume of protease stock needed to serial dilute into different concentrations and 
* the volume of MCA solution to add to each well (final volume of each well is 40 uL for 384 well plate)

**Requires** 

* Stock buffer (Tris-HCl, pH 8.5, 1M)
* Purified protease with known concentrations 
* MCA substrate stock solution (10 mM)
* 384 well black plate 

**Procedure**

*Prepare working buffer*

To prepare 200 mM from 1 M of Tris-HCl:

#. Add 200 uL of 1M Tris-HCl into 800 uL of distilled water. 
#. Mix well. Vortex if necessary. 

*Protease activity assay*

#. Thaw the purified protease stored in -80 C. 
#. Do a 1/2 fold serial dilution starting from maximum of 20 uM with working buffer. 
#. In a 384 well black plate, add calculated amount of protease.
#. Add substrate into each well that have protease. 
#. Incubate. 37 C, 120 mins. 
#. Read plate at 350 nm excitation and 440 nm emission. 

**Analysis**

You can plot a curve using the relative fluoresence unit (RFU) directly, graphpad prism will still calculate a Km value for you. But since we have to process the data anyway, we just convert all the RFU into reaction velocity.  

#. In MS Excel, arrange the values accordingly. 
#. First step is to minus all RFU values from other wells with the RFU from the well with 0 uM of protease (means the wells that only have buffer and substrate).
#. Divide the value with the gradient of substrate standard curve. 
#. Divide the value with time, in mins (30 mins, 60 mins, 120 mins, etc.). 

    * If the RFU values were obtained at 60 mins mark, then divide all values by 60.
    * Values obtained from this step will be the reaction velocity, with the unit of uM/mins.  

#. Copy the value into GraphPad Prism. Analyse using non-linear regression, Michaelis-Menten module. 
#. Ideally, the curve should have at least 3 points on plateau. 
#. Plot the reaction velocity in GraphPad Prism, analyse using non-linear regression, Michaelis-Menten module. 

    * The graphpad prism will automatically calculate the Vmax and Km value for us. We will need the Km value for substrate optimisation. 
    * If you plot the Michaelis-Menten plot using both RFU and reaction velocity, both graph should give you the same Km value.

After getting the protease optimisation curve, we can proceed to do the substrate optimisation curve. 