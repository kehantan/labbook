.. _cell count:

Cell count
==========

Cell counting is to get an estimation of how many cells are there in a culture flask, so we can know if we have enough cells for our experiments. 

**Requires**

* Centrifuge tube (15 mL)
* Counting chamber
* Counter
* Trypan blue
* 96 well plate (for mixing trypan blue and the cell suspension)

    You can use anything that works well for you, microcentrifuge tube, parafilm, etc. 


**Procedure**

**Trypsinise**

Before cell counting, you need to trypsinise your cells from the culture flask. Refer to :ref:`trypsinise <My target>`.

**Cell counting**

#. Pipette 10 uL of trypan blue into one well of the 96 well plate.
#. Pipette 10 uL of cell suspension from centrifuge tube to the well that have trypan blue. Mix by repeat pipetting. 

    * You can use higher volume of trypan blue or cell suspension if desired 
    * I recommend using 1:1 ratio (e.g.: 10 uL of trypan blue + 10 uL of cell suspension) for easy calculation later
    * You can always refer to other sources (internet, textbooks, etc.) for other approach to cell count if you find those approaches more convenient or easier to understand. As long as the ultimate objective is to know how many cells in a single culture flask. 

#. Take 10 uL of the trypan blue and cell mixture, and dispense into the counting chamber.

    A counting chamber set up typically consist of a counting chamber with a glass cover slip on top. Dispense the trypan blue + cell mixture from the edge of cover slip. The capillary action will spread the mixture evenly across the counting area. 

#. Count the cells. 

The formula for calculating number of cells in 1 mL of cell suspension

:math:`\frac{\text{sum of cells from 4 quadrant} \times 10^4 \times 2}{4} =` :code:`X cells/mL`

After counting the cells, we should get value of :code:`X cells/mL`. Compare the counted cell number before we begin the experiment and the calculated cells number. We should have sufficient cells for seeding. 


*Note:* 

At the end of :ref:`trypsinise <My target>` section, the protocol shows resuspend the cell pellet in 1 mL of fresh complete DMEM. There are several modifications you can do. Assume you wanted to proceed to cell counting: 

  For T25 that has cell confluency of 90% or above, or T75 that has cell confluency of 70% or above, you can add more fresh complete DMEM, to a cell suspension volume of 2 mL or 3 mL. The purpose is to make the cell counting easier, so you don't have to count large number of cells under microscope, which may strain your eyes. 

  For T25 with cell confluency of 90% or above, I would recommend to add complete DMEM until the cell suspension is 2 mL. 
  
  For T75 with cell confluency of 70% or above, I would recommend to add complete DMEM until the cell suspension is 3 mL. 

For these cases, the :code:`X cells/mL` is the number of cells in 1 mL of cell suspension. To know the total of cells, you will have to :math:`\times 2` or :math:`\times 3` depending on how much of complete DMEM you added. 

These are not strict instructions, just some suggestions which can help ease your workflow. You can of course, adjust the volume of cell suspension according to your need. Under certain circumstances, like when you wanted to cryopreserve the cells, you might not want to add more complete DMEM, because you want the highest number of cells in a smaller volume to ensure cell viability when reviving. 
