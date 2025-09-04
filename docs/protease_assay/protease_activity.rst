Protease activity assay
=======================

**Objective:** To quantify the activity of the purified protease. 

We need to determine:

* the concentration of purified protease stock
* the volume of substrate to add to each well 
* Product standard curve (AMC) -- to convert RFU into reaction velocity
 
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

*Assay buffer*

#. Add 1 mL of 1 M Tris-HCl stock buffer solution into 4 mL of distilled water to obtain 200 mM of Tris-HCl assay buffer solution at pH 8.5. 

    * Adjust the volume if necessary. The ratio of 1 M Tris-HCl to distilled water needed is 1:4 to make 200 mM Tris-HCl

#. Mix well. Vortex if necessary. 

*Substrate dilution*

#. Dilute substrate stock from 10 mM to 1 mM using assay buffer 200 mM Tris-HCl, pH 8.5. 

    * Add 20 uL of substrate stock into 180 uL of assay buffer

*Protease activity*

#. Thaw the purified protease stored in -80 C. 
#. Do a 2 fold serial dilution of protease with working buffer to a final volume sufficient for 32 uL per well.

    * Calculate sufficien volume for at least duplicate, triplicate if possible. 
    * 2 fold Serial dilute by adding 200 uL of protease into 200 uL of assay buffer. Carry out ~7 dilution. 

#. In a 384 well black plate, add 32 uL of the serial diluted protease into different wells.
#. In the blank well, add 32 uL of buffer. 
#. Add 8 uL of diluted substrate into each well, including the blank well. 
#. Read plate at 350 nm excitation and 440 nm emission every 10 mins for total duration of 60 mins. 

**Results**

* The Michaelis-Menten curve can be plot directly using relative fluoresence unit (RFU) directly, Km value can still calculate the Km and Vmax. But the RFU can also be converted into reaction velocity for better data presentation.  

:math:`\text{Reaction velocity}(\mu M/min) = \frac{\frac{S-NC}{m}}{t}`

S = Sample 

NC = Negative control 

m = Gradient of product standard curve 

t = Time of incubation 

#. Subtract all RFU values from negative control (0 uM of protease, only have buffer and substrate).
#. Divide the value with the gradient of substrate standard curve. 
#. Divide the value with incubation time, in mins (30 mins, 60 mins, 120 mins, etc.). 

    * If the RFU values were obtained at 60 mins mark, then divide all values by 60  

#. Analyse using non-linear regression model, Michaelis-Menten module in GraphPad Prism. 

* The graphpad prism will automatically calculate the Vmax and Km value for us. We will need the Km value for substrate optimisation. 
* If you plot the Michaelis-Menten plot using both RFU and reaction velocity, both graph should give you the same Km value.
* Ideally, the curve should have at least 3 points on plateau. 
* After getting the protease optimisation curve, we can proceed to do the substrate optimisation curve. 