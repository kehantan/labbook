Protease activity assay
=======================

**Objective:** To quantify the activity of the purified protease. 

We need to know/have:

* the volume of protease stock needed to serial dilute into different concentrations
* the volume of substrate to add to each well 
* Substrate standard curve

**Materials** 

* Stock buffer (Tris-HCl, pH 8.5, 1M)
* Purified protease with known concentrations 
* MCA substrate stock solution (10 mM)
* 384 well black plate 
* Micropipette 
* Micropipette tips

**Procedure**

*Prepare working buffer*

To prepare 200 mM from 1 M of Tris-HCl:

#. Add 200 uL of 1 M Tris-HCl into 800 uL of distilled water. 

    * Adjust the volume if necessary. The ratio of 1 M Tris-HCl to distilled water should be 1:4 to make 200 mM Tris-HCl

#. Mix well. Vortex if necessary. 

*Protease activity assay*

#. Thaw the purified protease stored in -80 C. 
#. Do a 1/2 fold serial dilution with working buffer. 
#. In a 384 well black plate, add the serial diluted protease.
#. Add correct amoount substrate into each well. 
#. Incubate, 37 C. 
#. Read plate at 350 nm excitation and 440 nm emission every 30 mins. 

**Analysis**

The Michaelis-Menten curve can be plot directly using relative fluoresence unit (RFU) directly, Km value can still calculate the Km and Vmax. But the RFU can also be converted into reaction velocity for better data presentation.  

:math:`\text{Reaction velocity}(\mu M/min) = \frac{\frac{S-NC}{m}}{T}`

S = Sample 

NC = Negative control 

m = Gradient of substrate standard curve 

T = Time of incubation 

#. Subtratct all RFU values from negative control (0 uM of protease, only have buffer and substrate).
#. Divide the value with the gradient of substrate standard curve. 
#. Divide the value with time, in mins (30 mins, 60 mins, 120 mins, etc.). 

    * If the RFU values were obtained at 60 mins mark, then divide all values by 60  

#. Analyse using non-linear regression model, Michaelis-Menten module in GraphPad Prism. 

* The graphpad prism will automatically calculate the Vmax and Km value for us. We will need the Km value for substrate optimisation. 
* If you plot the Michaelis-Menten plot using both RFU and reaction velocity, both graph should give you the same Km value.
* Ideally, the curve should have at least 3 points on plateau. 
* After getting the protease optimisation curve, we can proceed to do the substrate optimisation curve. 