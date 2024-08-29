Protease inhibition assay
=========================

**Objective:** To check the inhibition activity of a compound against the target protease. 

Reference for protease assay protocol: :cite:p:`ihssen_fluorogenic_2021`. 
There are several standard curve that need to be plotted before we carry out protease assay with the compounds that we wanted to test.  

    **Protease activity curve**

        From protease activity assay, we can find out the Km value of protease activity curve, which dictates how much protease to use for protease inhibition assay 

    **Substrate optimisation curve**

        From substrate optimisation assay, we can findout the Km value of substrate optimisation curve, which dictates how much substrate we should use for protease inhibition assay.  

**Requires**

* Stock buffer
* Substrate (MCA)
* DMSO 
* Microcentrifuge tube 

**Procedure**

    **Prepare working buffer**

        Prepare working buffer (200 mM, pH 8.0) from stock buffer. 

    **Prepare working MCA**

        Prepare working MCA by diluting stock MCA with DMSO.

    **Prepare working compound**

        Prepare working compound serial diluted to various concentration using DMSO from compound stock solution.

#. Calculate how much volume of protease needed in each well, subtract that volume from 100 uL, then subtract further volume of substrate (10 uL) and compound (10 uL) to be added, the remainder will be the volume needed to top up with buffer.  
#. Add calculated volume of buffer into each well. 
#. Add calculated volume of protease into each well. 
#. Add calculated volume of compound to be tested into their respective well according to their concentrations.   
#. Mix the mixture in each well by repeat pippetting. 
#. Incubate for 30 mins. 
#. Add substrate of fixed concentration (10 uL). 
#. Incubate for 30 mins. 
#. Read plate at 350 nm excitation and 440 nm emission. 
#. Incubate another 30 mins, then read the plate again. Repeat until 120 mins. 

The final volume of liquid in each well should be 100 uL. You can adjust to 200 uL since the well can fit, but beware that you will also need to increase the amount of protease (which is very precious), amount of compound, amount of substrate, which might not be very sufficient for 200 uL. 

If I wanted to test the compound at 1,600, 800, 400, and 200 ug/mL, I will prepare different tube by diluting stock solution of the compound to concentration of 16,000, 8,000, 4,000, and 2,000 ug/mL with DMSO. This is so that when I add 10 uL of the 1,600 ug/mL, it will be diluted by 10 times by the protease, buffer, and substrate, which makes the final volume of the compound to become 1,600 ug/mL. This is same with substrate. This is to make the volume consistant, where only 10 uL of compound and 10 uL of substrate will be added in each experiment.   

**Analysis**

#. Minus the RFU of the non-treated wells (0 ug/mL compound) to all the RFU of the treated wells. 
#. Divide all the values of the treated wells (after minus from non-treated) to the RFU of the non-treated wells. 
#. Convert the values into percentage by :math:`\times 100`. 
