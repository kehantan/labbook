Protease optimisation
====

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

*Protease optimisation*

* Fixed substrate concentration = 100 μM
* Substrate concentration can be adjusted accordingly. 

#. Do a 2 fold serial dilution of protease using working buffer solution. 
#. Add 36 uL of diluted protease into 384 well black plate. 
#. Dilute substrate stock (10 mM) to 1,000 μM using working buffer solution. 
#. Add 4 uL of diluted substrate stock into each well. 
#. Read plate at 350 nm excitation and 440 nm emission every 10 mins over 120 mins.

**Results**

* Plot Michaelis-Menten plot. x-axis = protease concentration, y-axis = RFU or reaction velocity 
* In GraphPad Prism, analyse the result using :code:`Nonlinear regression -> Enzyme kinetics - Velocity as a function of substrate -> Michaelis-Menten`.
* GraphPad Prism will calculate Km value. Km value of protease optimisation will be used as the protease concentration for substrate optimisation and protease inhibition assay.
* Graph should looks like a typical Michaelis-Menten plot with plateau. If no plateau observed/not obvious, can try to prolong incubation time or reduce substrate concentration. Usually reduce substrate concentration by 2 fold is a good starting point. 
* Can carry out the optimisation at different substrate concentration in a single experiment to save time and be more efficient. 