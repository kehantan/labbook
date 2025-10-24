Protease inhibition assay
=========================

* Reference for protease assay protocol: :cite:p:`ihssen_fluorogenic_2021`. 
* Do :ref:`enzyme progress curve <enzyme_progress>` before carry out inhibition assay to find out amount of enzyme and substrate needed. 
* Enzyme = 15 uM, substrate = 125 uM, incubation time = 120 mins 

**Materials**

* Stock Tris-HCl buffer (1M, pH 8.5)
* MCA substrate stock solution (10 mM)
* DMSO 
* Microcentrifuge tube
* 384 black well plate
* Micropipette and tips  

**Procedure**

*Prepare working buffer*

#. Prepare 100 mM Tris-HCl working buffer from 1 M stock buffer by adding 0.5 mL of 1M Tris-HCl into 4.5 mL of distilled water. 

    * Can adjust volume according to experiment needs 

#. Mix well. Vortex if necessary. 

*Prepare fluorogenic peptide substrate stock solution*

* Follow instruction provided by manufacturer. Add DMSO into the substrate and mix well. 
* Other concentrations can be prepared, but for convenient, prepare 10 mM. 

*Prepare test compound*

* Test compound stock concentration can range from ~ 10-50 mg/mL, dissolved in DMSO (or any other suitable solvent). This stock concentration is just a recommendation, the final stock concentration is depending on availability and solubility of compound. Some trial and error is required.  
* Prepare intermediate stock if the original stock solution is too concentrated or the volume to add to the serial dilution is too small.  
* Also check for final DMSO concentration in the wells, maximum concentration of DMSO should be <5%, preferably <1% (if possible). 
* Usually the max concentration to be tested is around 200 uM (can go higher, depends on the solubility and resulting DMSO concentration in each well). 
* Number of compound concentration to be tested usually ~7 (can do more, assuming the amount of enzyme and substrate is sufficient), 1 additional for non-treated control. 

*Enzyme inhibition assay*

#. Retrieve protease stock from -80 C and thaw at room temperature. 
#. Add correct amount of Tris-HCl working buffer into each well.

    * Buffer to add = 40 uL - protease vol - substrate vol - compound vol
    * Protease volume required for assay can fluctuate based on the concentration of protease stock after purification, so it is not possible to provide a fixed volume in this protocol. Calculate the amount needed for your assay based on how much protease you get after purification. 
    * The final volume of liquid in each well should be 40 uL. Adjust the buffer volume accordingly.  

#. Add correct amount of protease into each well. 
#. Add 4 uL of diluted compound into wells assigned for different concentrations. 

    * 4 uL is for convenient's sake, the final concentration is 10x diluted when added into the wells. It does not have to strictly be 4 uL, can adjust and calculate desired final volume to added into each well. 

#. Incubate, room temperature, 30 mins. 
#. Thaw substrate from -20 C. 
#. Dilute substrate from 10 mM stock to 1 mM working stock in assay buffer.  
#. Add 4 uL diluted substrate into each well.

    * Again, 4 uL is not a strict requirement, just for convenient. Adjust accordingly.  

#. Incubate, room temperature, 120 mins. 
#. Read plate at 380 nm excitation and 445 nm emission. 

**Analysis**

:math:`\text{Inhibition (%)} = \frac{\text{NT}-\text{T}}{\text{NT}}\times 100\%`

* NT = Non-treated
* T = Treated