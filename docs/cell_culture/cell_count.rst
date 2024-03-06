.. _cell count:

Cell count
==========

**Objective:** To get an estimation of how many cells we had collected from a culture flask. 

Purpose of cell counting is important for knowing if we have enough cells for our experiments, or count how many cells we need to put into each well in our well plates. 

**Requires**

* Counting chamber
* Counter
* Trypan blue
* 96 well plate (for mixing trypan blue and the cell suspension)

    You can use anything that works well for you, microcentrifuge tube, parafilm, etc. 

**Procedure**

#. Before cell counting, you need to trypsinise your cells from the culture flask. Refer to :ref:`trypsinise <My target>`.
#. Pipette 10 uL of trypan blue into one well of the 96 well plate.
#. Pipette 10 uL of cell suspension obtained from trypsinisation to the well that have trypan blue. Mix by repeat pipetting. 

    This example uses 1:1 ratio of cell suspension (10 uL) vs trypan blue (10 uL) for dilution. Refer below for more details on different approach in diluting the cell suspension for cell counting. 

#. Take 10 uL of the trypan blue and cell mixture and dispense into the counting chamber.

    A counting chamber set up typically consist of a counting chamber with a glass cover slip on top. Dispense the trypan blue + cell mixture from the edge of cover slip. The capillary action will spread the mixture evenly across the counting area. 

#. Count the cells using microscope. 

The formula for calculating number of cells exists in 1 mL of cell suspension

:math:`\frac{\text{sum of cells from 4 quadrant} \times 10^4 \times \text{Dilution factor}}{4} =` :code:`X cells/mL`

After counting the cells, we should get value of :code:`X cells/mL`. Compare the number of cells required you calculated before you begin the experiment and the number of cells you just calculated. You should have sufficient cells for seeding. 

In case there are not sufficient cells for all your experiments, you might want to consider lower the number of cells to seed, or reduce the number of plates you wanted to seed. 

**Dilution for cell count**

Counting large number of cells under microscope can be tiring and strain your eyes, so to mitigate this issue, we can dilute the cell suspension to ease the process of cell counting. There are two approach for dilution:

* Dilute the cell suspension by adding more fresh DMEM

    * At the end of :ref:`trypsinise <My target>` section, the protocol advice resuspend the cell pellet in 1 mL of fresh complete DMEM. 
    * You can add more fresh complete DMEM to the cell suspension to final volume of 2 or 3 mL.
    * For these cases, the :code:`X cells/mL` is the number of cells in 1 mL of cell suspension. To know the total number of cells in the cell suspension, you will have to :math:`\times 2` or :math:`\times 3` depending on how much volume of complete DMEM you added. 

* Dilute with trypan blue 

    * Add 10 uL of cell suspension into 40 uL of trypan blue, this is 1:4 ratio of cell suspension (10 uL) vs trypan blue (40 uL), the dilution factor is 5. You can use other ratio you like. 
    * This approach reduce the amount of fresh complete DMEM used.
    * If using this approach, just use :math:`\times 5` for dilution factor in the formula. Insert the correct dilution factor into the formula if other dilution factor was used.  

**Note:**

This protocol is not a strict instruction, just some suggestions which can help ease your workflow. You can of course, adjust the volume of cell suspension according to your need. 