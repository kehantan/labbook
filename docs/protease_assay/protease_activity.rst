Protease activity assay
=======================

* We need to determine:
    * the concentration of purified protease stock
    * the volume of substrate to add to each well 
    * *Optional:* Product (AMC) standard curve -- to convert RFU into reaction velocity

* See visual guide `here <https://docs.google.com/presentation/d/1O6VPsSYFLs5cjVarc6VdVJuFf3HdmGxObDM3o2Vy8zw/edit?usp=sharing>`_

**Materials** 

* Tris-HCl stock buffer (1M, pH 8.5)
* Purified protease (with known concentrations in μg/mL or μM) 
* MCA substrate stock solution (10 mM)
* DMSO
* 384 well black plate 
* Micropipette 
* Micropipette tips
* Microcentrifuge tube/PCR tube 

**Procedure**

*Assay buffer*

#. Add 0.5 mL of 1 M Tris-HCl stock buffer solution into 4.5 mL of distilled water to obtain 100 mM of Tris-HCl assay buffer solution at pH 8.5. 

    * May adjust the volume if necessary.

#. Mix well. Vortex if necessary. 

*Substrate dilution*

Dilute substrate stock from 10 mM to 1 mM using assay buffer. 

#. Add 20 μL of substrate stock into 180 μL of assay buffer to a final volume of 200 μL. 

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

    * Final volume of protease in each well = 32 μL/well.
    * Calculate sufficient final volume of serial dilution that is sufficient for at least duplicate, triplicate if possible. 
   
#. In a 384 well black plate, add 32 μL of the serial diluted protease into different wells.
#. In the 'Blank' wells, add 32 μL of assay buffer. 
#. Add 8 μL of 1mM substrate into each well, including the 'Blank' wells. 
#. Read plate at 350 nm excitation and 440 nm emission every 5 mins for total duration of 60 mins. 

**Results**

* The Michaelis-Menten curve can be plot directly using relative fluoresence unit (RFU) directly, Km value can still be  calculated. But the RFU can be convert into reaction velocity (μM/min) for better data presentation because it tells how much product was formed within the given incubation time. 

:math:`\text{Reaction velocity}(\mu M/min) = \frac{\frac{S-B}{m}}{t}`

S = Sample 

B = Blank 

m = Gradient of product (AMC) standard curve 

t = Time of incubation (30, 60, 120 mins, etc.)

* Analyse data using non-linear regression model, Michaelis-Menten module in GraphPad Prism. 
* The graphpad prism will automatically calculate the Vmax and Km value. Km value is required for substrate optimisation. 
* If the Michaelis-Menten graph was plotted using both RFU and reaction velocity, both graph should give the same Km value.
* Ideally, the curve should be approaching plateau at the end of the curve and have at least 3 points on plateau. 
* After getting the protease optimisation curve, can proceed to do the substrate optimisation curve. 