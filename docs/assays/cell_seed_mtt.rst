.. _cell seed mtt:

Cell seeding for MTT assay
==========================

**Objective:** Seed cells for MTT assay.

Estimated time needed: 1 hr

After we know how much cells we have, we now need to know how much cells we need to take from the cell suspension and dilute in complete DMEM to make the final mixture we want. We need to:

* Calculate the volume of cell suspension we need to take
* Calculate the amount of complete DMEM we need 

To calculate the volume of cell suspension we need to take, 

    Assume after counting the cells, we have: :math:`150 \times 10^4 \text{cells}/mL`
    
    But we only need: *:math:`25 \times 10^4 \text{cells}`* <-- Remember we calculate this value before we begin the procedure 

    :math:`25 \times 10^4 \text{cells/mL}`

    So, :code:`25/150` to know how much volume (in mL) of cell suspension we need to aspirate from the cell suspension in the 15 mL centrifuge tube. 
    
    In this case, :code:`0.167 mL`. Convert to uL, then the volume we should take is :code:`167 uL`

To calculate how much media we need, 

    Assume we do 10 concentrations (supposedly 8, but we prepare 10 for some headroom), then use the formula given above:

    .. code-block::
        
        Total media needed = 10 concentrations * 5 wells/concentration * 100 uL/well = 5,000 uL <-- This was also calculated before we begin the procedure

To summarise, we need to put **167 uL of cell suspension** into **5,000 uL of complete DMEM**. 

After all the calculations we can begin our cell seeding procedure. 

**Materials**

* 96 well plate 
* Cell reservoir
* Micropipette
* Multichannel micropipette
* Pipette tips 
* Serological pipette 
* Pipette gun 

**Procedure**

#. Mix the cell suspension with either repeat pipetting or vortex. 
#. Add appropriate amount of complete DMEM into the cell reservoir. 

    * In this example, we should dispense 5,000 uL (5 mL) of complete DMEM into the cell resesrvoir.

#. Take required volume of cell suspension and mix with complete DMEM in the cell reservoir.

    * In this example, add 167 uL of cell suspension into the cell reservoir.

#. Mix the cells and media evenly by repeat pipetting using multichannel micropiptte. 
#. Take 100 uL of cells and complete DMEM mixture from the cell reservoir with multichannel micropipette and add into 96 well plate. 
#. Incubate the seeded 96 well plate for 24 hrs. 

*Note:* Technically, 167 uL of cell suspension + 5,000 uL of complete DMEM = 5,167 uL. If we want to be absolute accurate we should be doing 167 uL cell suspension + 4,833 uL complete DMEM = 5,000 uL. But for convenience's sake, we would assume the small difference is negligible.
