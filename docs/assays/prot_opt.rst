Protease & substrate optimisation
====

**Materials**

* 384 well black plate
* :ref:`MCA stock (Boc-Gly-Arg-Arg-MCA, 10 mM) <mca>`
* :ref:`Stock buffer (1M Tris-HCl, pH 8.0) <tris-hcl>`
* Purified protease with known concentrations 
* :ref:`Assay buffer <assay>`

Protease optimisation
----

* Fixed substrate concentration = 100 μM
* Substrate concentration can be adjusted accordingly. 

**Procedure**

#. Do a 2 fold serial dilution of protease using working buffer solution. 
#. Add 36 uL of diluted protease into 384 well black plate. 
#. Dilute substrate stock (10 mM) to 1,000 μM using working buffer solution. 
#. Add 4 uL of diluted substrate stock into each well. 
#. Read plate at 350 nm excitation and 440 nm emission every 10 mins over 120 mins.

**Protease optimisation results**

* Plot Michaelis-Menten plot. x-axis = protease concentration, y-axis = RFU or reaction velocity 
* In GraphPad Prism, analyse the result using :code:`Nonlinear regression -> Enzyme kinetics - Velocity as a function of substrate -> Michaelis-Menten`.
* GraphPad Prism will calculate Km value. Km value of protease optimisation will be used as the protease concentration for substrate optimisation and protease inhibition assay.
* Graph should looks like a typical Michaelis-Menten plot with plateau. If no plateau observed/not obvious, can try to prolong incubation time or reduce substrate concentration. Usually reduce substrate concentration by 2 fold is a good starting point. 
* Can carry out the optimisation at different substrate concentration in a single experiment to save time and be more efficient. 

Substrate optimisation 
----

**Procedure**

*Substrate dilution*

* Concentration of substrate to be tested: 200, 100, 50, 25, 12.5, 6.25, 3.125, 0 μM 
* Intermediate substrate stock concentration to be prepared: 2,000, 1,000, 500, 250, 125, 62.5, 31.25 μM
* Vol of substrate added into each well = 4 μL (10x diluted from intermediate stock)

#. Dilute stock substrate (10 mM) to first intermediate stock concentration (2,000 μM). 
#. Do a 2 fold serial dilution from 2,000 μM using working buffer solution. 

*Substrate optimisation*

* Vol of protease to be added into each well can is dependant on Km of protease optimisation. 
* Calculate the volume of protease and working buffer needed for each well.  

#. Add calculated amount of working buffer solution into 384 well black plate. 
#. Add fixed amount of protease into 384 well black plate. 

    * According to the Km value obtained from protease activity assay

#. Add 4 μL of diluted substrate into their respective wells. 
#. Read plate at 350 nm excitation and 440 nm emission every 10 mins over 120 mins.

**Substrate optimisation results**

* Plot Michaelis-Menten plot. x-axis = substrate concentration, y-axis = RFU or reaction velocity 
* In GraphPad prism, analyse the result using :code:`Nonlinear regression -> Enzyme kinetics - Velocity as a function of substrate -> Michaelis-Menten`. 
* GraphPad Prism will calculate Km value. Km value of protease and substrate optimisation will be used as the protease and substrate concentration for protease inhibition assay.
* Graph should looks like a typical Michaelis-Menten plot with plateau. If no plateau observed/not obvious, can try to prolong incubation time or might need to go back to protease optimisation step.

Reference
----

:cite:`tomlinsonSubstrateInhibitionKinetic2008`