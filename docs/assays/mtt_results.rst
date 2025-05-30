MTT results
===========

* The raw reading you obtain is the absorbance reading. 
* Depending on which machine you use, most machine allows the results to be easily export to Microsoft Excel file. If not you will have to convert them manually into an Excel sheet, or you can directly input them into whatever software you use (e.g.: GraphPad Prism). 
* How to put the results together is purely up to your own preference. I usually use Excel. 

#. Average all the reading from the 3 wells of each concentrations (including blank and negative control wells). 
#. Subtract the absorbance value for blank from absorbance value of each well. This is to remove the background noise generated by DMSO (which we used as a blank).
#. Devide absorbance reading of each well by the absorbance reading of negative control, then times the value by 100. 

:math:`\text{Inhibition} (%) = \frac{T}{NC} \times 100\%` 

T = Treated
NC = Negative control 

#. Plot the graph. 

Optional
--------

#. Copy the values into GraphPad Prism and plot the graph.
#. Find IC50 and R2 value.   

* Under typical condition, negative control should have the highest absorbance reading. Followed by reduced absorbance reading as the concentration of compound used to treat the cells going up, due to toxicity of the tested compounds against the cells. However, this will not always be the case.
* Final interpretation of the results depends on experiment design and what to expect from the cytotoxicity results. 
