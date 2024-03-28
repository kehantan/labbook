Bradford assay
==============

**Objective:** To quantify concentration of protein in a sample.

**Requires**

* Microcentrifuge tube
* Distilled water, MilliQ water, or PBS
* Bovine serum albumin (BSA)
* Bradford reagent 
* 96 well plate, clear
* Microplate reader 
  
**Procedure**

#. Dilute BSA powder in distilled water to make stock solution of BSA (5 mg/mL). 
#. Prepare a series of BSA standard solutions of known concentrations (e.g. 0, 200, 400, 600, 800, and 1000 ug/mL) by diluting the BSA stock solution in distilled water.

    We would only need 10 uL/well, but I usually prepare around 100 uL for easier handling. 

#. In a clear 96 well plate, add 10 uL of BSA or protein sample into 190 uL of Bradford reagent. Mix well by repeat pipetting. 
#. Include wells for blank by pipette 200 uL of solvent (depends on what solvent you use for dissolving the BSA, can be distilled water, MilliQ water, or PBS) into empty wells. 
#. Incubated at room temperature, 5 mins.
#. Read absorbance at 590 nm and 450 nm. 

    We take 2 reading because we need to linearise the standard curve. See section below.  

Linearisation of Bradford assay 
-------------------------------

If we only read the absorbance at 590 nm and try to plot a standard curve, we would not get a linear graph as expected. At higher BSA concentration (approaching 1 mg/mL), the line would curved to a plateau near the 1000 ug/mL region. That is why we take 2 readings at different wavelength (590 and 450) and calculate the absorbance ratio of A\ :sub:`590`\ /A\ :sub:`450`\ . This approach correct the slightly curved line to a linear line. This modification is adopted from :cite:t:`ernst_linearization_2010`.

There are other wavelength used like 595 nm and 490 nm reported in other literature, but I find the standard curve calculated from readings with 590 nm and 450 nm wavelength works the best to give the highest R\ :sup:`2` value when plotted. 