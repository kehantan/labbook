Protease activity assay
=======================

**Objective:** To quantify the activity of the purified protease. 

We need to know/have:

* the volume of protease stock needed to serial dilute into different concentrations
* the volume of substrate to add to each well 
* Product standard curve

**Materials** 

* Tris-HCl stock buffer (1M, pH 8.5)
* Purified protease (with known concentrations in ug/mL or uM) 
* MCA substrate stock solution (10 mM)
* DMSO
* 384 well black plate 
* Micropipette 
* Micropipette tips
* Microcentrifuge tube/PCR tube 

**Procedure**

*Prepare working buffer*

#. Add 1 mL of 1 M Tris-HCl stock buffer solution into 4 mL of distilled water to obtain 200 mM of Tris-HCl working buffer  solution at pH 8.5. 

    * Adjust the volume if necessary. The ratio of 1 M Tris-HCl to distilled water needed is 1:4 to make 200 mM Tris-HCl

#. Mix well. Vortex if necessary. 

*Protease activity assay*

#. Thaw the purified protease stored in -80 C. 
#. Do 1/2 fold serial dilution of protease with working buffer to a final volume sufficient for 39 uL per well.

    * Calculate sufficien volume for at least duplicate, triplicate if possible. 

#. In a 384 well black plate, add 39 uL of the serial diluted protease into each well.
#. In the blank well, add 39 uL of buffer. 
#. Add 1 uL of substrate into each well. 
#. Read plate at 350 nm excitation and 440 nm emission every 30 mins for total duration of 60 mins. 

**Results**

* The Michaelis-Menten curve can be plot directly using relative fluoresence unit (RFU) directly, Km value can still calculate the Km and Vmax. But the RFU can also be converted into reaction velocity for better data presentation.  

:math:`\text{Reaction velocity}(\mu M/min) = \frac{\frac{S-NC}{m}}{t}`

S = Sample 

NC = Negative control 

m = Gradient of product standard curve 

t = Time of incubation 

#. Subtratct all RFU values from negative control (0 uM of protease, only have buffer and substrate).
#. Divide the value with the gradient of substrate standard curve. 
#. Divide the value with incubation time, in mins (30 mins, 60 mins, 120 mins, etc.). 

    * If the RFU values were obtained at 60 mins mark, then divide all values by 60  

#. Analyse using non-linear regression model, Michaelis-Menten module in GraphPad Prism. 

* The graphpad prism will automatically calculate the Vmax and Km value for us. We will need the Km value for substrate optimisation. 
* If you plot the Michaelis-Menten plot using both RFU and reaction velocity, both graph should give you the same Km value.
* Ideally, the curve should have at least 3 points on plateau. 
* After getting the protease optimisation curve, we can proceed to do the substrate optimisation curve. 