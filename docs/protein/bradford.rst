.. _bradford std:

Bradford assay
==============

BSA standard curve
------------------

* Bovine serum albumin (BSA) would be used as a standard for Bradford assay 
* The standard curve only need to be done once, after the standard curve is established, use the standard curve to determine the concentration of protein in subsequent purified protein sample. 

**Materials**

* Microcentrifuge tube
* Any suitable solvent for diluting protein sample and BSA (eg: Distilled H2O, PBS, buffers, etc.)
* Bovine serum albumin (BSA)
* Bradford reagent (BioRad)
* 96 well plate, clear
* Microplate reader 

**Procedure**

#. Dilute BSA powder in distilled water to make stock solution of BSA (10 mg/mL). 
#. Prepare a series of BSA standard solutions of known concentrations of 0, 200, 400, 600, 800, 1000, 1200, and 1400 μg/mL by diluting the BSA stock solution in distilled H2O (or any suitable solvent/buffer) to final volume of 50 μL.

    * Volume can be adjusted depends on how many replications we want to do. 

#. In a 96 well clear plate, add 10 μL of BSA prepared in previous step into 190 μL of Bradford reagent. Mix well. 
#. Add 10 μL of distilled H2O into 190 μL of bradford reagent as blank. 
#. Incubated at room temperature, 5 mins.
#. Read absorbance at 595 nm. 

    * Reduce as much bubble as possible from the wells to reduce absorbance interference

**Note:** Dist H2O can be used, but it is preferable to use the solvent used to dissolve the target protein we are going to quantify (eg: PBS, buffer, etc.) as solvent for dilution for more accurate results. 

Protein sample
--------------

**Procedure**

#. Perform a 2 fold serial dilution of protein sample using dist H2O. 
#. Add 10 uL of diluted protein samples into 190 uL of Bradford reagent. Mix well. 
#. Incubated at room temperature, 5 mins. 
#. Read absorbance at 595 nm. 

Results 
---

* Plot the data of BSA std curve in GraphPad Prism or MS Excel.
* If using GraphPad Prism, use the linear regression model and fit the standard line into the data.
* Examine plot, trendline should be linear, better if R\ :sup:`2` is close to to 0.99.
* Obtain the formula that describe the line of best fit of BSA standard cruve, :code:`y=mx+c` 
#. Plug the absorbance value obtained from measuring the protein sample into :code:`y` of the formula :code:`y=mx+c` and find the value for :code:`x`.  
#. If the absorbance value for the protein sample exceeds the range of the BSA standard curve, dilute the protein sample and measure again. 
    
    * Optimal range of absorbance value for bradford assay should falls between 0.1 and 1.0 for an accurate representation of protein concentration. 

Linearisation of Bradford assay 
-------------------------------

* Adapted from :cite:p:`ernst_linearization_2010`
* This is a more advanced technique to get more accurate results from Bradford assay. Detailed protocol can be found `here <https://www.protocols.io/view/bradford-protein-assay-protein-concentration-measu-kqdg3pd9ql25/v1?step=3&u=%2Fview%2Fbradford-protein-assay-protein-concentration-measu-kqdg3pd9ql25%2Fv1>`_.
* The main reasoning for doing this is that if we try to plot a standard curve from only 595 nm wavelength, we would not get a linear graph as expected. At higher BSA concentration, the line would curve to a plateau when concentraion of BSA approaching 1000 ug/mL range. 
* So 2 readings at different wavelength, 590 nm and 450 nm was taken and calculate the absorbance ratio of A\ :sub:`590`\ /A\ :sub:`450`\ . 
* There are other wavelength used like 595 nm and 490 nm reported in other literature, but I find the standard curve calculated from readings with 590 nm and 450 nm wavelength works the best to give the highest R\ :sup:`2` value when plotted. 