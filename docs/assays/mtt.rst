MTT assay
=========

Preface 
-------

This protocol uses the cell line that I worked with -- VERO cells as an example. If you are using other cell lines, refer to research article of other resources for some of the specific parameters. 

There are some parameters that you will need to find out before carrying out MTT assay. Some common questions you will immediately bump into when you first trying to do MTT assay including:

#. How many cells to seed?

    This is a question very difficult to answer. The best approach is to refer to the research articles related to the cell lines you are working with to get an idea on how many cells you should seed. If you cannot get the information you can do some optimisation yourself by trying out any range between 1000 to 5000 cells/well. Some general rule is that your negative control (untreated cells) well's absorbance should not be too high (exceeds 1.0) at the day of reading the plate. 

#. How many different concentrations you wanted to test with your compound? 

    Again, refer to literature for this part. If there are no information available, some optimisation would need to be made. If you have no idea what concentration you wanted to use, you can try out by using a larger range of concentrations first. I typically start with 200 ug/ml of concentration and half it for each dilution step (200 ug/mL, 100 ug/mL, 50 ug/mL). My rationale is that it is easier to find your compound's effective concentration by screening it with a larger range. If you screen your compound at a narrow range like 20 ug/mL, 40 ug/mL, 60 ug/mL, you might need to do more plates to find out the effective concentrations. 

#. How long I should incubate? How much reagent I should use? 

    Again, refer to literature whenever you can. I cannot list everything here because these parameters is some what related to the cell lines you are dealing with. For most part, the parameters should be transferrable from one cell line to another. Fortunately, there are a lot of resources you can refer online, or you can simply ask around other lab members. 

The whole MTT assay is a long procedure that can takes up multiple day. It takes 3 seperate days to complete 1 round of MTT. We need:

    * 1 day for trypsinise, cell count, and seeding
    * 1 day for treatment (treat the cells with compound)
    * 1 day for actual MTT and to read the absorbance

I divided this protocol into sections, so each sections indicates that procedure requires one day. It doesn't mean that particular procedure will take up the whole day, it's just after that procedure, you will have to wait another day to proceed to the next section. You can plan your experiments accordingly. 

The steps for one round of MTT assay including:

#. Trypsinise   
#. Cell count   
#. Cell seeding
#. Treatment
#. Actual MTT
#. Read absorbance

**Calculate how many cells and media we need**

Before we actually start the procedure, it is best to count the theoretical number of cells required before we start seeding. Our final goal is to have 100 uL of mixture that contains 10% DMEM + 1,500 cells in each well.

Assume we want to test 8 different concentrations (including negative control) of our compound on the cells, then 

    :code:`Total cells needed = 10 concentrations * 5 wells/concentration * 1,500 cells/well = 75,000 cells` 

You will notice that even we wanted to test 8 different concentration, the formula above state :code:`10 conecentrations`. This is due to slight deviations during pipetting and handling of liquids. If we prepare enough cell suspension for the exact number of concentrations we want, we might end up not having enough cells for the last few wells, so prepare a little bit extra amount. Usually adding 3 to 5 concentrations extra for some overhead is sufficient enough.

After the actual cell counting step in the procedure, double check if the cells is sufficient for seeding. 

Now we would need to calculate how much media we need. The concept is similar to the previous step

    :code:`Total media needed = 10 concentrations * 5 wells/concentration * 100 uL/well = 5,000 uL` 

:code:`10 concentrations` were used in calculation instead of 8 just for some extra volume. 

Section 1 - Trypsinise, cell count, seed cells
----------------------------------------------

**Trypsinise**

**Requires**

* :ref:`Complete DMEM (10%) <10 dmem>`
* TrypLE
* :ref:`Phosphate buffer saline (1x PBS) <pbs>`
* Centrifuge tube (15 mL)

Assume cells were cultured in a T25 flask to 70% to 90% confluency. 

First step is to detach the cells from the culture flask. Refer to :ref:`trypsinise <My target>`. 

**Cell counting**

**Requires**

* Cell counter
* Counting chamber
* 96 well plate for mixing cells with trypan blue

    You can use anything that works well for you, microcentrifuge tube, parafilm, etc. 

* Trypan blue
* Calculator 

We need to know the number of cells since we want to seed a specific number of cells into each well. Refer to :ref:`cell count <cell count>`.  

After counting the cells, we should get value of :code:`X cells/mL`. Compare the counted cell number before we begin the experiment and the calculated cells number. We should have sufficient cells for seeding. 

**Cell seeding**

We now need to seed specific number of cells into each well.

The final outcome we want = 100 uL of mixture of complete DMEM + 1,500 cells in each well

We know how much cells we have, we now need to know how much cells we need to take and dilute in complete DMEM to make the final mixture we want. What we should do now:

* Calculate the volume of cell suspension we need to aspirate
* How much complete DMEM we need 

To calculate the volume of cell suspension we need to aspirate, 

    Assume we have: :code:`150*10^4 cells/mL`
    
    But we only need: :code:`75,000 cells` <-- Remember we calculate this value before we begin the procedure 
    
    So we first convert the :code:`75,000 cells` to the :code:`10^4` 'format', which is :code:`7.5x10^4`

    Then, :code:`5.25/150` to know how much volume (in mL) of cell suspension we need to aspirate from the cell suspension in 15 mL centrifuge tube. 
    
    In this case, :code:`0.035 mL`. Convert to uL, then the volume we should take is :code:`35 uL`

To calculate how much media we need, 

    Assume we do 7 concentrations (including negative control), then

    :code:`7 concentrations * 5 well/concentration * 100 uL/well = 3,500 uL (3.5 mL)`

After all the calculations we can begin our cell seeding procedure. 

**Requires**

* 96 well plate 
* Cell reservoir
* Multi channel micropipette

**Procedure**

#. Mix the cell suspension with either repeat pipetting or vortex. 
#. Dispense appropriate amount of complete DMEM into the cell reservoir. 

    In this example, we should dispense 3,500 uL (3.5 mL) of complete DMEM into the cell resesrvoir.

#. Aspirate required volume of cell suspension and mix with complete DMEM in the cell reservoir.

    In this example, add 35 uL of cell suspension into the cell reservoir.

#. Aspirate 100 uL of cells and complete DMEM mixture from the cell reservoir with multichannel micropipette. Seed the mixture into 96 well plate. 
#. Incubate the seeded 96 well plate for 24 hrs. 

*Note:* Technically, 35 uL + 3,500 uL = 3,535 uL. If we want to be absolute accurate we should be doing 35 + 3,465 uL = 3,500 uL. But for convenience's sake, we would treat it as a negligible difference.

Section 2 - Treatment of cells
------------------------------

Treatment is where we treat our seeded cells with compound we wanted to test. 

Before treatment, calculate the concentration of compound we need. Usually we do serial dilution, but we can also do each concentration seperately if it is too confusing. There are serial dilution calculator online that can help us to calculate the dilution. Refer to :ref:`serial dilution <serial dilution>` section. 

Prepare the compounds with different concentrations before removing media from the 96 well plate, so we can immediately dispense the compound into the 96 well plate after removing the media. If the cells are left too long whithout media they would dry up and dies. 

**Requires**

* Multichannel micropipette 
* Microcentrifuge tube

**Procedure**

#. Prepare different concentration of compound by diluting the compound in complete DMEM.

    We need 100 uL for each well, total of 5 well per concentration. Supposedly :math:`5 wells \times 100 \mu L` should only requires 500 uL, but we would prepare extra volume to compansate handling errors. In this case, we prepare 600 uL, a 100 uL extra.  

#. Remove media from 96 well plate with multichannel micropipette. 
#. Dispense 100 uL of fresh complete DMEM in negative control wells. 
#. Dispense 100 uL of compound diluted in complete DMEM into respective wells. 
#. Incubate for 48 hrs. 

Section 3 - MTT, read absorbance
--------------------------------

**Add MTT**

This is the step where the actual MTT was added. 

This procedure can be carried out either in the biosafety cabinet or at bench. 

**Requires**

* :ref:`MTT working solution <mtt stock>`
* DMSO
* Multichannel micropipette

**Procedure**

#. Take MTT working solution from freezer and warm to room temperature in water bath before use. 
#. Add 10 uL of MTT into each well.

    Don't have to remove media on this step

#. Incubate. 37 :math:`^{\circ}`\ C, 5% CO2, 3 hrs.

    There are no strict rules for how long the incubation period should be. You can try to optimise, or reduce the incubation time if you find 3 hrs is too long. 

#. After 3 hrs, remove the 96 well plate from incubator.

    You can observe the 96 well plate under microscope to see the formation of formazan crystals. 

#. Remove media along with remaining MTT solution.  
#. Add 100 uL of DMSO into each well. 
#. Place 96 well plate on shaker and shake for 1 hr.

    This step is to solubilise the formazan crystal

#. Read absorbance after shaking for 1 hr. 

**Read absorbance**

Read the absorbance with plate reader. 

**Requires**

* Plate reader

**Procedure**

#. Read plate at 570 nm. 

**Note**

MTT assay is a very commonly used assay, you can find a lot of articles that optimised MTT assays for different purposes. You can refer to other sources for different parameters like: the amount of different reagent being used, the time of incubation, etc. You don't have to strictly follow the parameters in this protocol. The parameters used in this protocol are the ones that is good enough for our lab use. 