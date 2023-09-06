MTT assay
=========

Requires
--------
* Micropipette (100-1000 uL and 10-100 uL)
* Micropipette tips 
* Waste beaker
* Cell counter
* Counting chamber
* 10% DMEM (in 50 ml centrifuge tube)
* 96 well plate 
* Trypan blue
* Calculator 
* 70% Ethanol in spray bottle
* Paper towel
* 96 well plate for mixing cells with trypan blue
* 15 ml centrifuge tube
* Seropipette (5ml and 10 ml)
* TrypLE
* Phosphate buffer saline (1x PBS)
* Cell reservoir
* Multi channel micropipette

Before seeding
--------------
Count the theoretical cells required before start seeding. 

I usually seed 1,500 cells/well and 100 uL of media/well.

Assume we do 7 concentrations (including negative control), then 

:code:`Total cells needed = 7 concentrations * 5 wells/concentration * 1,500 cells/well = 52,500 cells` 

After the cell counting step, double check if the cell required is sufficient for seeding. 

Trypsinise
----------
Assume cells were culture in a T25 flask. 

#. Remove media from culture flask. 
#. Dispense 600-800 uL of PBS into culture flask. 

    Swirl the flask to wash cells thoroughly. 

#. Remove PBS. 
#. Dispense 600-800 uL of TrypLE into culture flask. 

    Swirl the flask to make sure TrypLE covers all the cells. 

#. Incubate culture flask for 3-5 mins at 37C. 
#. Remove the culture flask from incubator. 
#. Slightly tapping the flask to mechanically detach the cells from flask. 
#. Dispense 10% DMEM in equal amount with TrypLE. Swirl the flask to properly neutralise TrypLE. 

    For example: if dispensed 600 uL of TrypLE, then dispense 600 uL of 10% DMEM

#. Transfer the suspension to 15 ml centrifuge tube. 
#. Centrifuge. 1500 rpm, 5 mins. 
#. Remove supernatant, but leave minimal amount of DMEM in the centrifuge tube. 
#. Flick the centrifuge tube to resuspend the cell pellet into DMEM. 
#. Add 1 ml of 10% DMEM to the centrifuge tube. Pipette repeatedly to break the cell pellet. 

Cell count
----------
#. Dispense 10 uL of Trypan blue into one of the wells in the 96 well plate used for mixing. 
#. Dispense 10 uL of cells from the 15 ml centrifuge tube from the trypsinise phase into the same well with trypan blue. 
#. Mix well by repeat pipetting. 
#. Dispense 10 uL of Trypan blue and cell mixture into counting chamber. 
#. Count the cells. 

After counting the cells, we should get value of :code:`X cells/ml`. Cross check the counted cell number and the calculated cells number. We should have sufficient cells for seeding. 

Seeding
-------
We know how much cells we have, we now need to know how much cells we need to dilute. 
What we should do now:

* Calculate the volume of cell suspension we need to aspirate
* How much media we need 

To calculate the volume of cell suspension we need to aspirate, 

    Assume we have: :code:`150*10^4 cells/ml`
    
    But we only need: :code:`52,500 cells`
    
    So we first convert the :code:`52,500 cells` to the :code:`*10^4` 'format', which is :code:`5.25x10^4`
    
    Then, :code:`5.25/150` to know how much volume (in ml) of cell suspension we need to aspirate. 
    
    In this case, :code:`0.035 ml`. Convert to uL, then :code:`35 uL`

To calculate how much media we need, 

    Assume we do 7 concentrations (including negative control), then

    :code:`7 concentrations * 5 well/concentration * 100 uL/well = 3,500 uL (3.5 ml)`

#. Mix the cell suspension with either repeat pipetting or vortex. 
#. Aspirate required number of cells and mix with required amount of 10% DMEM in cell reservoir.

    In this example, add 35 uL of cell suspension into 3,500 uL of 10% DMEM

#. Aspirate 100 uL of cells and DMEM mixture from the cell reservoir with multichannel micropipette. Seed the mixture into 96 well plate. 
#. Incubate the seeded 96 well plate for 24 hrs. 

Treatment
---------
#. Prepare different concentration of compound by diluting the compound in complete DMEM.

    Prepare 600 uL, 100 uL for each well, total of 5 well per concentration. 

#. Remove media from 96 well plate. 
#. Dispense 100 uL of complete DMEM in blank and control wells. 
#. Dispense 100 uL of compound diluted in complete DMEM into respective wells. 
#. Incubate for 48 hrs. 

MTT
---
#. Add 10 uL of MTT into each well.
#. Incubate for 3 hrs at 37C, 5% CO2.
#. Remove media. 
#. Add 100 uL of DMSO into each well. 
#. Place 96 well plate on shaker, shake for 1 hr.
#. Read absorbance. 

Read absorbance
---------------
#. Read plate at 570 nm. 
