Protease activity assay
=======================

**Objective:** To quantify the activity of the purified protease. 

* We need to determine:
    * the concentration of purified protease stock
    * the volume of substrate to add to each well 
    * Product standard curve (AMC) -- to convert RFU into reaction velocity

* See visual guide `here <https://docs.google.com/presentation/d/1O6VPsSYFLs5cjVarc6VdVJuFf3HdmGxObDM3o2Vy8zw/edit?usp=sharing>`_

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

Dilute substrate stock from 10 mM to 1 mM using assay buffer. 

#. Add 20 uL of substrate stock into 180 uL of assay buffer to a final volume of 200 uL. 

*Protease dilution*

#. Prepare 9 microcentrifuge tube. 

+-----------------+---+-----+-----+-----+------+------+------+-------+-------+
| Tube no.        | 1 | 2   | 3   | 4   | 5    | 6    | 7    | 8     | 9     | 
+-----------------+---+-----+-----+-----+------+------+------+-------+-------+
| Buffer (uL)     | 0 | 120 | 120 | 120 | 120  | 120  | 120  | 120   | 120   |  
+-----------------+---+-----+-----+-----+------+------+------+-------+-------+
| Dilution factor | 0 | 1/2 | 1/4 | 1/8 | 1/16 | 1/32 | 1/64 | 1/128 | 1/256 | 
+-----------------+---+-----+-----+-----+------+------+------+-------+-------+

* Transfer volume = 120 uL 

*Protease activity assay*

#. Retrieve the purified protease from -80 C and thaw at room temperature. 
#. Do a 2 fold serial dilution of protease with working buffer. 

    * Final volume of protease in each well = 32 uL/well.
    * Calculate sufficient final volume of serial dilution that is sufficient for at least duplicate, triplicate if possible. 
   
#. In a 384 well black plate, add 32 uL of the serial diluted protease into different wells.
#. In the blank well, add 32 uL of assay buffer. 
#. Add 8 uL of 1mM substrate into each well, including the blank well. 
#. Read plate at 350 nm excitation and 440 nm emission every 2 mins for total duration of 60 mins. 

**Results**

* The Michaelis-Menten curve can be plot directly using relative fluoresence unit (RFU) directly, Km value can still be  calculated. But the RFU can also be converted into reaction velocity (uM/min) for better data presentation.  

:math:`\text{Reaction velocity}(\mu M/min) = \frac{\frac{S-NC}{m}}{t}`

S = Sample 

NC = Negative control 

m = Gradient of product (AMC) standard curve 

t = Time of incubation 

#. Subtract all RFU values from negative control (0 uM of protease, only have buffer and substrate).
#. Divide the value with the gradient of substrate (AMC) standard curve. 
#. Divide the value with incubation time, in mins (30 mins, 60 mins, 120 mins, etc.). 

    * If the RFU values were obtained at 60 mins mark, then divide all values by 60  

#. Analyse using non-linear regression model, Michaelis-Menten module in GraphPad Prism. 

* The graphpad prism will automatically calculate the Vmax and Km value. Km value is required for substrate optimisation. 
* If the Michaelis-Menten graph was plotted using both RFU and reaction velocity, both graph should give the same Km value.
* Ideally, the curve should have at least 3 points on plateau. 
* After getting the protease optimisation curve, can proceed to do the substrate optimisation curve. 