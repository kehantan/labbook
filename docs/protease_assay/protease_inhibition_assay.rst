Protease inhibition assay
=========================

**Objective:** To check the inhibition activity of a compound against the target protease. 

* Reference for protease assay protocol: :cite:p:`ihssen_fluorogenic_2021`. 
* There are several standard curve that need to be plotted before we carry out protease assay with the compounds that we wanted to test.  

    * **Protease activity curve** From protease activity assay, find out the Km value of protease activity curve, which dictates how much protease should be used for protease inhibition assay 

    * **Substrate optimisation curve** From substrate optimisation assay, find out the Km value of substrate optimisation curve, which dictates how much substrate should be used for protease inhibition assay.  

**Requires**

* Stock Tris-HCl buffer (1M, pH 8.5)
* MCA substrate stock solution (10 mM)
* DMSO 
* Microcentrifuge tube
* 384 black well plate
* Micropipette and tips  

**Procedure**

*Prepare working buffer*

To prepare 200 mM Tris-HCl working buffer from 1 M stock buffer:

#. Add 1 mL of 1M Tris-HCl into 4 mL of distilled water. 

    * Other volumes can be prepared by using 1:4 ratio of stock buffer to disilled water.  

#. Mix well. Vortex if necessary. 

*Prepare fluorogenic peptide substrate stock solution*

Follow instruction provided by manufacturer. Add DMSO into the substrate and mix well. 

*Prepare test compound*

* Test compound stock concentration ~ 20 mg/mL, in DMSO
* From stock prepare working stock = 10 mM, dilute in DMSO
* Serial dilute working stock in Tris-HCl 200 mM, pH 8.5 buffer.

+--------------------------+-----+-----+-----+-----+
| No                       | 1   | 2   | 3   | ... |
+--------------------------+-----+-----+-----+-----+
| Conc (uM)                | 800 | 400 | 200 | ... |
+--------------------------+-----+-----+-----+-----+
| From 10 mM stock (uL)    | 8   |     |     |     |
+--------------------------+-----+-----+-----+-----+
| Buffer (uL)              | 92  | 50  | 50  | ... |  
+--------------------------+-----+-----+-----+-----+
| Final conc. in well (uM) | 100 | 50  | 25  | ... |
+--------------------------+-----+-----+-----+-----+

*Inhibition assay*

#. Retrieve protease stock from -80 C and thaw at room temperature. 
#. Add correct amount of Tris-HCl buffer into each well.

    * Buffer to add = 40 uL - protease vol - substrate vol - compound vol
    * Becaue protease volume required for assay can fluctuate based on the concentration of protease stock after purification, so I cannot provide a fixed volume in this protocol. You will have to calculate the amount needed for your assay based on how much protease you get after purification. 
    * Anyhow, the final volume of liquid in each well should be 40 uL. Adjust the buffer volume accordingly.  

#. Add correct amount of protease into each well. 

    * According to Km from protease activity assay

#. Add 5 uL of diluted compound into wells assigned for different concentrations. 
#. Incubate, room temperature, 30 mins. 
#. Thaw substrate from -20 C. 
#. Dilute substrate from 10 mM stock to 1 mM working stock in assay buffer.  
#. Add correct amount of diluted substrate into each well.

    * According to Km from substrate optimisation

#. Read plate at 350 nm excitation and 440 nm emission every 2 mins over total of 60 mins.   

**Analysis**

:math:`\text{Inhibition (%)} = \frac{\text{NT}-\text{T}}{\text{NT}}\times 100\%`

* NT = Non-treated
* T = Treated