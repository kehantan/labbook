MTT assay
=========

**Objective:** To find the toxicity level of a compound toward a cell line. 

MTT assay is a very common assay, you can find a lot of published articles that optimised MTT assays for different purposes. You don't have to strictly follow the parameters in this protocol. The parameters used in this protocol are the ones that is good enough for my experiments with Vero cells. If you are using other cell lines, refer to other sources for different parameters like: the amount of different reagent being used, the time of incubation, etc. 

The general protocol for MTT with Vero cells was described by :footcite:t:`guillen2022effect,marin2021curcumin`.

There are some parameters that you will need to find out before starting MTT assay. Some common questions you will immediately bump into when you first trying to do MTT assay including:

#. *How many cells to seed in each well?*

    The common approach is to refer to the published research articles related to the cell lines you are working with to get an idea on how many cells you should seed. If you cannot get the information you can do some optimisation yourself by trying out any range between 1,000 to 10,000 cells/well. Some general rule is that your negative control (untreated cells) well's absorbance should not be too high (exceeds 1.0) at the day of reading the plate. Some published research articles uses cell confluency as a guidelines instead of number of cells seeded. 

#. *How many different concentrations you wanted to test with your compound?*

    If you have no idea what concentration you wanted to use, you can try out by using a larger range of concentrations first. I typically start with 200 ug/mL and half it for each dilution step (200, 100, 50 ug/mL, etc.). My rationale is that it is easier to find your compound's optimum concentration by screening it with a wider range. If you screen your compound at a narrower range like 20, 40, 60 ug/mL, etc., you might need to do more assays to find out the optimum concentration. So start from wider range, then narrow down if necessary. 

#. *Other common questions including 'How long I should incubate? How much reagent I should use?'*

    The list of questions are non-exhaustive and can be difficult answer as these parameters are related to multiple factors like what cell lines you are dealing with, what is the purpose of the experiments, etc. Fortunately, there are a lot of resources you can refer online, or you can simply ask around other lab members who had experience with cell lines that you are using. For most part, the parameters should be transferrable from one cell line to another. 

The whole MTT assay is a long procedure that can takes up multiple day. It takes 3 seperate days to complete 1 round of MTT. We need:

    * 1 day for trypsinise, cell count, and seeding
    * 1 day for treatment (treat the cells with compound)
    * 1 day for actually adding the MTT reagent and to read the absorbance

I divided this protocol into sections, so each sections indicates that procedure requires one day. This doesn't mean that particular procedure will take up the whole day, it's just after that procedure, you will have to wait until another day to proceed to the next steps. With this information you can plan your experiments accordingly. 

The general workflow for one round of MTT assay:

#. Trypsinise   
#. Cell count   
#. Cell seeding
#. Treatment
#. Actually adding the MTT reagent
#. Read absorbance

Planning
--------

Before we actually start the procedure, there are several things we need to plan out. 

* Number of cells we need 
* Amount of media we need 

**Number of cells we need**

Our goal is to have 100 uL of mixture that contains 10% DMEM + 5,000 cells in each well.

Assume we want to test 8 different concentrations (including negative control) of our compound on the cells, then 

    .. code-block:: 
        
        Total cells needed = 10 concentrations * 5 wells/concentration * 5,000 cells/well = 250,000 cells

You will notice that even we wanted to test 8 different concentration, the formula above state :code:`10 concentrations`. This is due to the inevitable deviations during pipetting and handling of liquids. If we prepare just enough cell suspension for the exact number of concentrations we want, we might end up not having enough cells for the last few wells, so prepare a little extra amount for some headroom. Usually adding 3 to 5 concentrations extra is sufficient enough.

**Amount of media we need**

Now we need to calculate how much media we need. The concept is similar to the previous step

    :math:`\text{Total media needed} = \text{10 concentrations} \times \text{5 wells/concentration} \times 100  \mu\ L/well = 5,000 \mu L` 

Similar to above, :code:`10 concentrations` were used in calculation instead of 8 for some extra headroom. 

Section 1 - Trypsinise, cell count, seed cells
----------------------------------------------

**Trypsinise**

First step is to detach the cells from the culture flask. Refer to :ref:`trypsinise <My target>`. 

**Cell counting**

We need to know the number of cells since we want to seed a specific number of cells into each well. Refer to :ref:`cell count <cell count>`.  

After counting the cells, we should get value of :code:`X cells/mL`. Compare the counted cell number before we begin the experiment and the calculated cells number. We should have sufficient cells for seeding. 

**Cell seeding**

We now need to seed specific number of cells into each well.

Each well should have final volume of 100 uL of liquid, which contains a mixture of complete DMEM + 5,000 cells.

After we know how much cells we have, we now need to know how much cells we need to take from the cell suspension and dilute in complete DMEM to make the final mixture we want. What we should do now:

* Calculate the volume of cell suspension we need to aspirate
* How much complete DMEM we need 

To calculate the volume of cell suspension we need to aspirate, 

    Assume we have: :code:`150*10^4 cells/mL`
    
    But we only need: :code:`250,000 cells` <-- Remember we calculate this value before we begin the procedure 
    
    So we first convert the :code:`250,000 cells` to the :code:`10^4` 'format', which is :code:`25x10^4`

    Then, :code:`25/150` to know how much volume (in mL) of cell suspension we need to aspirate from the cell suspension in 15 mL centrifuge tube. 
    
    In this case, :code:`0.167 mL`. Convert to uL, then the volume we should take is :code:`167 uL`

To calculate how much media we need, 

    Assume we do 10 concentrations (supposedly 8, but we prepare 10 for some headroom), then

    .. code-block::
        
        10 concentrations * 5 well/concentration * 100 uL/well = 5,000 uL (5 mL)`

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

*Note:* Technically, 35 uL + 3,500 uL = 3,535 uL. If we want to be absolute accurate we should be doing 35 + 3,465 uL = 3,500 uL. But for convenience's sake, we would assume the small difference is negligible.

Section 2 - Treatment
---------------------

Treatment is where we treat our seeded cells with the compounds we wanted to test. 

Before treatment, calculate the concentration of compound we need. Usually we do serial dilution, but we can also do each concentration seperately if it is too confusing. There are serial dilution calculator online that can help us to calculate the dilution. Refer to :ref:`serial dilution <serial dilution>` section. 

Prepare the compounds with different concentrations before removing media from the 96 well plate, so we can immediately dispense the compound into the 96 well plate after removing the media. If the cells are left too long whithout media they would dry up and dies. 

**Requires**

* :ref:`Complete DMEM <10 dmem>`
* Multichannel micropipette 
* Microcentrifuge tube

**Procedure**

#. Prepare different concentration of compound by diluting the compound in complete DMEM.

    We need 100 uL for each well, total of 5 well per concentration. Supposedly :math:`\text{5 wells} \times 100 \mu L` should only requires 500 uL, but we would prepare extra volume to compansate handling errors. In this case, we prepare 600 uL, a 100 uL extra.  

#. Remove media from 96 well plate with multichannel micropipette. 
#. Dispense 100 uL of fresh complete DMEM in negative control wells. 
#. Dispense 100 uL of compound diluted in complete DMEM into respective wells. 
#. Incubate. 37 :math:`^{\circ}`\ C.

    Incubate for how long depends on your study. You can optimise by doing different timepoint, e.g.: 12, 24, 36, 48 hrs and compare the results.     

Section 3 - MTT, read absorbance
--------------------------------

* This is the step where the actual MTT reagent will be added. 
* This procedure can be carried out either in the biosafety cabinet or at bench.
* Remember to reduce as much light source as possible (i.e.: turn off lights in lab or in BSC) as MTT is light sensitive. 

**Requires**

* :ref:`MTT working solution <mtt stock>`
* DMSO 
* Multichannel micropipette
* Aluminium foil

**Procedure**

#. Take MTT working solution from freezer and warm to room temperature in water bath before use. 
#. Add 10 uL of MTT into each well.

    * Don't have to remove media on this step.
    * The MTT concentration we used in this lab is 5 mg/mL.
    * There are other concentrations of MTT used, find out from the literature whichever that suits your experiments. 

#. Wrap well plate in aluminium foil to keep the MTT from light. 
#. Incubate. 37 :math:`^{\circ}`\ C, 5% CO2, 3 hrs.

    There are no strict rules for how long the incubation period should be. You can try to optimise. For my experiment, I use 3 hrs. Reduce the incubation time if you think 3 hrs is too long. 

#. After 3 hrs, remove the 96 well plate from incubator.

    You can observe the 96 well plate under microscope to see the formation of formazan crystals. 

#. Remove media along with remaining MTT solution.  
#. Add 100 uL of DMSO into each well. 
#. Place 96 well plate on shaker and shake for 1 hr.

    This step is to solubilise the formazan crystal. You can reduce the time for shaking, as long as the crystals are completely dissolve in DMSO. You can observe the plate under microscope to see if there are undissolved crystals. 

Read absorbance
~~~~~~~~~~~~~~~

Read the absorbance with a plate reader. 

**Requires**

* Plate reader

**Procedure**

#. Read plate at 570 nm. 

    There are different protocols that uses different wavelength, you may adjust according to literature. 

Clean up
--------

* After reading the absorbance, the plate can be disposed into the yellow bin in the lab. 

**References**

.. footbibliography:: 