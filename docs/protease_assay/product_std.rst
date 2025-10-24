.. _prod_std: 

Product (AMC) standard curve
============================

* AMC MW = 175.18 g/mol

**Materials**

* Tris-HCl stock buffer solution (Tris-HCl, 1M, pH 8.5)
* 7-amino-4-methylcoumarin (AMC) stock solution (10 mg/mL)
* 384 well black plate
* Micropipette 
* Micropipette tips  
* Microcentrifuge tube/PCR tube
* Waste beaker 
* DMSO 
* Weighing balance 
* Weighing boat
* Spatula 

**Procedure**

*Prepare AMC stock*

#. Weight 10 mg (0.01 g) of AMC powder into a microcentrifuge tube. 
#. Add 1 mL of DMSO into the microcentrifuge tube. Final AMC stock solution concentration = 10 mg/mL (57,084.14202535 uM). 

*Prepare working buffer*

#. Add 0.5 mL of stock buffer solution into 4.5 mL of distilled water, resulting in 100 mM of Tris-HCl buffer of pH 8.5.

*AMC Serial dilution*

#. Prepare 7 microcentrifuge tube. 
#. Add 95.6 uL of working buffer into the first tube. 
#. Add 4.4 uL of AMC stock into the first tube. Mix well using vortex or repeat pipetting. 
#. Transfer 50 uL of mixture from first tube to second tube. Mix well using vortex or repeat pipetting. Transfer 50 uL of mixture from second tube to third tube. Mix well using vortex or repeat pipetting. Repeat the process until last tube. 

+---------------------------------+------+------+------+-------+
| Tube no.                        | 1    | 2    | 3    | . . . | 
+---------------------------------+------+------+------+-------+
| Working buffer vol. (uM)        | 95.6 | 50   | 50   | . . . |
+---------------------------------+------+------+------+-------+
| AMC stock (uL)                  | 4.4  | \-   | \-   | \-    |
+---------------------------------+------+------+------+-------+
| Conc. (uM)                      | 2500 | 1250 | 625  | . . . | 
+---------------------------------+------+------+------+-------+
| Final conc. in each well (uM)   | 250  | 125  | 62.5 | . . . |
+---------------------------------+------+------+------+-------+

* Transfer volume = 50 uL

*In 384 well plate* 

#. Add 36 uL of Tris-HCl working buffer into 384 well black plate according to number of concentrations of AMC to be tested. 
#. Add 4 uL of each concentration of serial diluted AMC into designated wells. 
#. Read plate at 380 nm for excitation and 445 nm for emission.

**Results** 

* Graph can be plotted using GraphPad Prism or MS Excel. 
* The graph plotted should be linear. 
* Use simple linear regression model to fit the line of best fit into the data points. 

**Calculations** 

Adding AMC stock directly into the 384 well plate to get the desired concentration will result in pipetting extremely small volume and introduce error. Therefore an additional intermediate concentration was prepared. 

* AMC MW = 175.18 g/mol
* 10 mg/mL = 57,084.1420 uM

We would focus on the first concentration of the serial dilution. 

.. code-block:: 

    C1V1 = C2V2
    57,084.142 uM * V1 = 2,500 uM * 100 uL
    V1 = 4.4 uL + 95.6 uL working buffer

Only add 4 uL of the AMC prepared on previous step into each well in the 384 well black plate, meaning the concentration of AMC is further diluted. 

.. code-block:: 
    
    C1V1 = C2V2
    2,500 uM * 4 uL = C2 * 40 uL
    C2 = 250 uM