Substrate optimisation
======================

* References: :cite:p:`tomlinson2008substrate` 

**Materials**

* 384 well black plate
* Substrate stock (Boc-Gly-Arg-Arg-MCA, 10 mM) 
* Stock buffer (1M Tris-HCl, pH 8.5)
* Purified protease with known concentrations 
* Distilled H2O 

**Procedure**

*Substrate stock* 

#. Add correct amount of DMSO to substrate according to manufacturer instruction to make final substrate stock concentration of 10 mM. 
#. Store at -20 C.

*Working buffer solution*

#. Add 1 mL of 1 M Tris-HCl into 4 mL of distilled water to obtained 200 mM of Tris-HCl working solution at pH 8.5. 

    * Adjust the volume if necessary. The ratio of 1 M Tris-HCl to distilled water needed is 1:4 to make 200 mM Tris-HCl

#. Mix well. Vortex if necessary. 

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

**Results**

* Plot Michaelis-Menten plot. x-axis = substrate concentration, y-axis = RFU or reaction velocity 
* In GraphPad prism, analyse the result using :code:`Nonlinear regression -> Enzyme kinetics - Velocity as a function of substrate -> Michaelis-Menten`. 
* GraphPad Prism will calculate Km value. Km value of protease and substrate optimisation will be used as the protease and substrate concentration for protease inhibition assay.
* Graph should looks like a typical Michaelis-Menten plot with plateau. If no plateau observed/not obvious, can try to prolong incubation time or might need to go back to protease optimisation step.