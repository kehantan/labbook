.. _bradford std:

Bradford assay
==============

*Bradford assay standard curve*

* Bovine serum albumin (BSA) would be used as a standard for Bradford assay 
* The standard curve only need to be done once, after the standard curve is established, use the standard curve to determine the concentration of protein in subsequent purified protein sample. 

**Materials**

* Microcentrifuge tube
* Distilled water, PBS, or suitable buffer
* Bovine serum albumin (BSA)
* Bradford reagent 
* 96 well plate, clear
* Microplate reader 
* Micropipette 
* Micropipette tips 
* Waste beaker

**Procedure**

#. Dilute BSA powder in distilled water to make stock solution of BSA (5 mg/mL). 

    * It is adviced to dilute the BSA into solvent that is same as our protein sample for more accurate results.  

#. Prepare a series of BSA standard solutions of known concentrations starting from 0, 200, 400, 600, 800, and up to 1000 ug/mL by diluting the BSA stock solution in distilled water to final volume of 50 uL.
#. In a 96 well clear plate, add 10 uL of BSA or protein sample into 190 uL of Bradford reagent. Mix well. 
#. Include wells for blank by pipette 200 uL of distilled water. 

    * The blank should be depending on what solvent you use for dissolving the BSA, can be distilled water, PBS, or buffer. 
    * Distilled water was used for blank instead of bradford reagent. This decision was made according to the reference below.  

#. Incubated at room temperature, 5 mins.
#. Read absorbance at 595 nm. 

Quantification of protein sample
--------------------------------

#. Add 10 uL of protein sample into 190 uL of Bradford reagent. 
#. Read absorbance at 595 nm. 
#. Plug the value into the formula obatined from BSA standard curve. Find the corresponding protein concentration from BSA standard curve.
#. If the absorbance value for the protein sample exceeds the range of the BSA standard curve, dilute the protein sample and measure again. 

*Note:* Optimal range of absorbance value for bradford assay should falls between 0.1 and 1.0 for an accurate representation of protein concentration. 

Linearisation of Bradford assay 
-------------------------------

* Adapted from :cite:p:`ernst_linearization_2010`
* This is a more advanced technique to get more accurate results from Bradford assay. Detailed protocol can be found `here <https://www.protocols.io/view/bradford-protein-assay-protein-concentration-measu-kqdg3pd9ql25/v1?step=3&u=%2Fview%2Fbradford-protein-assay-protein-concentration-measu-kqdg3pd9ql25%2Fv1>`_.
* The main reasoning for doing this is that if we try to plot a standard curve from only 590 nm wavelength, we would not get a linear graph as expected. At higher BSA concentration, the line would curve to a plateau when concentraion of BSA approaching 1000 ug/mL range. 
* So 2 readings at different wavelength, 590 nm and 450 nm was taken and calculate the absorbance ratio of A\ :sub:`590`\ /A\ :sub:`450`\ . 
* There are other wavelength used like 595 nm and 490 nm reported in other literature, but I find the standard curve calculated from readings with 590 nm and 450 nm wavelength works the best to give the highest R\ :sup:`2` value when plotted. 

#. Divide the absorbance value of each BSA concentration at 590 nm by absorbance value at 450 nm.

    * :math:`\frac{A_590}{A_450}`

#. Plot the graph in GraphPad Prism or Microsoft Excel.

    * If using GraphPad Prism, use the linear regression model and fit the standard line into the data, better if R\ :sup`2` = 0.99.

#. Obtain the formula that describe the line of best fit of BSA standard cruve, :math:`y=mx+c` 