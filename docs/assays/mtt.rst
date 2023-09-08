MTT assay
=========
MTT is a long procedure that can take multiple days. The steps including:

#. Trypsinise
#. Cell count
#. Cell seeding
#. Treatment
#. Actual MTT
#. Read absorbance

I divided this protocol into sections, so each sections indicates that particular process requires 1 day. You can plan your experiments accordingly. 

Before we actually start the procedure, it is best to count the theoretical cells required before start seeding. I usually prepare 100 uL of mixture that contains 10% DMEM + 1,500 cells into each well.

Assume we test 7 concentrations (including negative control) for our compound, then 

:code:`Total cells needed = 7 concentrations * 5 wells/concentration * 1,500 cells/well = 52,500 cells` 

After the cell counting step, double check if the cell required is sufficient for seeding. 

*Note: To avoid confusion, examples here uses the exact number of concentrations and number of wells. But during exact execution, we usually prepare extra. For example, if we wanted to do 7 concentrations, we would actually prepare for 10 concentrations. This is due to slight deviations during pipetting and handling liquids. If you prepare the exact number of concentrations you want, you might end up not having enough cells for the last few wells. So calculate a little bit extra accordingly. I would usually add 3-5 concentrations extra for overhead.*


Section 1 - Trypsinise, cell counting, cell seeding
---------------------------------------------------

Trypsinise
~~~~~~~~~~
Requires:

* Complete DMEM (10%)
* TrypLE
* Phosphate buffer saline (1x PBS)
* 15 ml centrifuge tube

Assume cells were cultured in a T25 flask. 

#. Remove media from culture flask. 
#. Dispense 600-800 uL of PBS into culture flask. 

    Swirl the flask to wash cells thoroughly. 

#. Remove PBS. 
#. Dispense 600-800 uL of TrypLE into culture flask. 

    Swirl the flask to make sure TrypLE covers all the cells. 

#. Incubate culture flask for 3-5 mins at 37C.

    Not more than 10 mins

#. Remove the culture flask from incubator. 
#. Slightly tapping the flask to mechanically detach the cells from flask. 
#. Dispense 10% DMEM in equal amount with TrypLE. Swirl the flask to properly neutralise TrypLE. 

    For example: if dispensed 600 uL of TrypLE, then dispense 600 uL of 10% DMEM

#. Transfer the suspension to 15 ml centrifuge tube. 
#. Centrifuge. 1500 rpm, 5 mins. 
#. Remove supernatant, but leave minimal amount of DMEM in the centrifuge tube. 
#. Flick or tap the centrifuge tube to resuspend the cell pellet into DMEM. 
#. Add 1 ml of 10% DMEM to the centrifuge tube. Pipette repeatedly to break the cell pellet. 

Cell counting
~~~~~~~~~~~~~
Requires:

* Cell counter
* Counting chamber
* 96 well plate for mixing cells with trypan blue
* Trypan blue
* Calculator 

#. Dispense 10 uL of trypan blue into one of the wells in the 96 well plate used for mixing. 
#. Dispense 10 uL of cells from the 15 ml centrifuge tube from the trypsinise phase into the same well with trypan blue. 
#. Mix well by repeat pipetting. 
#. Dispense 10 uL of trypan blue and cell mixture into counting chamber. 
#. Count the cells. 

After counting the cells, we should get value of :code:`X cells/ml`. Compare the counted cell number before we begin the experiment and the calculated cells number. We should have sufficient cells for seeding. 

Cell seeding
~~~~~~~~~~~~
Requires:

* 96 well plate 
* Cell reservoir
* Multi channel micropipette

The final outcome we want = 100 uL of mixture of complete DMEM + 1,500 cells in each well

We know how much cells we have, we now need to know how much cells we need to dilute. 
What we should do now:

* Calculate the volume of cell suspension we need to aspirate
* How much media we need 

To calculate the volume of cell suspension we need to aspirate, 

    Assume we have: :code:`150*10^4 cells/ml`
    
    But we only need: :code:`52,500 cells`
    
    So we first convert the :code:`52,500 cells` to the :code:`*10^4` 'format', which is :code:`5.25x10^4`
    
    Then, :code:`5.25/150` to know how much volume (in ml) of cell suspension we need to aspirate from the cell suspension in 15 ml centrifuge tube. 
    
    In this case, :code:`0.035 ml`. Convert to uL, then the volume we should take is :code:`35 uL`

To calculate how much media we need, 

    Assume we do 7 concentrations (including negative control), then

    :code:`7 concentrations * 5 well/concentration * 100 uL/well = 3,500 uL (3.5 ml)`

After all the calculations we can begin our procedure. 

#. Mix the cell suspension with either repeat pipetting or vortex. 
#. Dispense appropriate amount of complete DMEM into the cell reservoir. 

    In this example, we should dispense 3,500 uL (3.5 ml) of complete DMEM into the cell resesrvoir.

#. Aspirate required volume of cell suspension and mix with complete DMEM in the cell reservoir.

    In this example, add 35 uL of cell suspension into the cell reservoir.

#. Aspirate 100 uL of cells and complete DMEM mixture from the cell reservoir with multichannel micropipette. Seed the mixture into 96 well plate. 
#. Incubate the seeded 96 well plate for 24 hrs. 

*Note: Technically, adding 35 uL to 3,500 uL would be 3,535 uL, but we would treat it as a negligible difference*


Section 2 - Treatment of cells
------------------------------

Treatment
~~~~~~~~~
Before treatment, calculate the concentration of compound we need. Usually we do serial dilution, but we can also do each concentration seperately if it is too confusing. 

There are serial dilution calculator online that can help us to calculate the dilution. 

Requires:

* Multichannel micropipette 

#. Prepare different concentration of compound by diluting the compound in complete DMEM.

    Prepare 600 uL, 100 uL for each well, total of 5 well per concentration. Supposedly 5 wells * 100 uL should only requires 500 uL, but we usually prepare extra volume to compansate handling errors. In this case, we prepare 600 uL, a 100 uL extra  

#. Remove media from 96 well plate with multichannel micropipette. 
#. Dispense 100 uL of complete DMEM in blank and control wells. 
#. Dispense 100 uL of compound diluted in complete DMEM into respective wells. 
#. Incubate for 48 hrs. 


Section 3 - MTT, read absorbance
--------------------------------

MTT
~~~
Requires:

* MTT reagent
* DMSO

#. Add 10 uL of MTT into each well.

    Don't have to remove media

#. Incubate for 3 hrs at 37C, 5% CO2.
#. Remove media. 
#. Add 100 uL of DMSO into each well. 
#. Place 96 well plate on shaker, shake for 1 hr.
#. Read absorbance. 

Read absorbance
~~~~~~~~~~~~~~~
#. Read plate at 570 nm. 
