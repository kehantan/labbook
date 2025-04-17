.. _bradford std:

Bradford assay standard 
=======================

**Objective:** To plot a standard graph for protein concentration quantification and calculate the concentration of protein in a given sample.

* The standard plot only need to be done once, after the standard plot is established, use the standard plot to determine the concentration of protein in purified protein sample. 

**Requires**

* Microcentrifuge tube
* Distilled water, MilliQ water, or PBS
* Bovine serum albumin (BSA)
* Bradford reagent 
* 96 well clear plate
* Microplate reader 
  
**Procedure**

#. Dilute BSA powder in distilled water to make stock solution of BSA (5 mg/mL). 
#. Prepare a series of BSA standard solutions of known concentrations starting from 0, 200, 400, 600, 800, and up to 1000 ug/mL by diluting the BSA stock solution in distilled water with the final cocentration of 50 uL.
#. In a 96 well clear plate, add 10 uL of BSA or protein sample into 190 uL of Bradford reagent. Mix well by repeat pipetting. 
#. Include wells for blank by pipette 200 uL of distilled water. 

    * The blank should be depending on what solvent you use for dissolving the BSA, can be distilled water, MilliQ water, or PBS. 
    * Distilled water was used for blank instead of bradford reagent. This decision was made according to the reference below.  

#. Incubated at room temperature, 5 mins.
#. Read absorbance at 590 nm and 450 nm. 

Linearisation of Bradford assay 
-------------------------------

* If we try to plot a standard curve from only 590 nm wavelength, we would not get a linear graph as expected. At higher BSA concentration (approaching 1 mg/mL), the line would curve to a plateau near the 1000 ug/mL region. 
* So 2 readings at different wavelength, 590 nm and 450 nm was taken and calculate the absorbance ratio of A\ :sub:`590`\ /A\ :sub:`450`\ . 
* This approach correct the slightly curved line to a linear line, giving more accurate results. This modification is adopted from :cite:t:`ernst_linearization_2010`.
* There are other wavelength used like 595 nm and 490 nm reported in other literature, but I find the standard curve calculated from readings with 590 nm and 450 nm wavelength works the best to give the highest R\ :sup:`2` value when plotted. 

#. Divide the absorbance value of each BSA concentration at 590 nm by absorbance value at 450 nm.
#. Plot the graph. 
#. Obtain the formula :math:`y=mx+c` 

Bradford assay for protein sample
---------------------------------

#. Add 10 uL of protein sample into 190 uL of Bradford reagent. 
#. Rread absorbance at 590 nm and 450 nm. 
#. Divide the absorbance value at 590 nm by absorbance value at 450 nm. 
#. Plug the value into the formula obatined from BSA standard curve. Find the corresponding protein concentration from BSA standard curve.
#. If the absorbance value for the protein sample exceeds the range of the BSA standard curve, dilute the protein sample and measure again. 

References
----------

.. footbibliography::