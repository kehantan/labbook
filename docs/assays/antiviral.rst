Antiviral assay
===============

**Objective:** To test antiviral properties of a compound using cell based assay. 

The protocol for antiviral had been published :footcite:p:`lani2016antiviral,florez2022vitro,marin2021curcumin`. 

This protocol was separated into different sections, each section indicates that after that procedure was completed, have to wait until the next day (or after 2 days) to proceed to the next section. 

This protocol demonstrate plaque assay in 6 well plate. For plaque in 12 well plate or well plate of other sizes, the procedures are the same, just the volume of liquids, number of cells, and volume of reagents used are different. 

Before starting antiviral assay, several informations are required.

    * Virus titer of the virus stock, in pfu/ml

        This information can be obtain from doing plaque assay using the virus stock.

    * MOI to use

        Refer to published articles for the MOI suitable for the experiments. Common MOI to use including 1, 0.5, 0.1.    

    * Concentration of compound to be tested

        This requires some trial and error. For organically synthesised small molecule compounds, I usually start with 50 ug/mL then serial dilute 1/2 to 6 to 7 concentrations. The concentration could be adjusted to higer value depends on the type of compounds to be tested, ie: peptides, plant extracts, etc. 

Section 1 - Trypsininse, cell count, seed cells
-----------------------------------------------

For antiviral assay, cells should be at around 70% confluency at the day of infection and treatment. 

    * For 6 well plate, seed 450,000 cells for next day infection and treatment. 
    * For 12 well plate, seed 150,000 cells for next day infection and treatment. 

**Requires**

* :ref:`Complete DMEM <10 dmem>`
* Trypsin 
* :ref:`Phosphate buffer saline (PBS) <pbs>`
* Clear 6 well plate
* Micropipette (10 uL to 1000 uL)
* Micropipette tips
* Waste beaker 
* Serological pipette (5 mL, 10 mL)
* Counter
* Cell counting chamber  

**Procedure**

#. Trypsinise the cells in culture flask. Refer to :ref:`trypsinise <My target>`.
#. Count the number of cells. Refer to :ref:`cell count <cell count>`. 

    * Check if there are enough cells for seeding in a 6 well plate at 450,000 cells/well. 
    * :code:`6 well * 450,000 cells = 2,700,000 cells needed`
    * If there are not enough cells, consider seed at another day, or seed less wells.  

#. Dispense 1.5 mL of 10% DMEM in each well in the 6 well plate.

    * 1 mL of 10% DMEM in each well if using 12 well plate 

#. Dispense correct amount of cells into each well. 
#. Tilt the well plate back and forth and side to side to distribute the cells evenly across the base of the wells. 
#. Incubate. 37 C, 24 hrs. 

Section 2 - Infection
---------------------

Before infection, 

* check the cell confluency in the 6 well plate. The cells should be around 70% confluency. 
* plan well plate layout 
* determine MOI to be used 
* serial dilute the compound to be tested

Planning well plate layout
~~~~~~~~~~~~~~~~~~~~~~~~~~

It is always best to plan the layout of the well plate before starting the antiviral assay. 

Below shows a layout of a 6 well plate 

(A1) (A2) (A3) 

(B1) (B2) (B3) 

I would typically do 

* A1 = Negative control (Cells without virus infection)
* B1 = Virus control (Cells with virus infection, but not treated with compound)
* A2 = Compound X concentration 1 (Cells with virus infection and treated with compound)
* B2 = Compound X concentration 2 (Cells with virus infection and treated with compound)
* A3 = Compound X concentration 3 (Cells with virus infection and treated with compound)
* B3 = Compound X concentration 4 (Cells with virus infection and treated with compound)

This is merely a suggestion, you can tailor the arrangement however you like according to the need of your experiments, but always remember to include negative control and virus control wells. 

Calculate virus volume to use for infection
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

:math:`\frac{\text{Virus need (MOI)}}{\text{Virus titer}} = X mL`

MOI = multiplicity of infection

    * MOI = 1, 1 virus particle for each cell 
    * MOI = 0.5, 1 virus particle for every 2 cells 
    * MOI = 0.1, 1 virus particle for every 10 cells  

If 450,000 cells seeded in each well, MOI = 0.1 is to be used, then 45,000 virus particles needed for each well  

    :math:`0.1 \times 450,000 = 45,000`

Assume virus titer of the virus stock = :math:`1 \times 10^{6}\ \text{pfu}/mL`, then using the formula above, we can determined that we need 45 uL of virus stock in each well. 

    :math:`\frac{45,000}{1 \times 10^{6}} = 0.045 mL (45 \micro L)`

Virus need is supposedly the number of cells in each well at the day of infection, but it is impractical to count the cells in each well, so we just assumes that the number of cells in the well is the number of cells seeded, although that is not true. 

**Requires**

* :ref:`2% DMEM <2 dmem>`
* Microcentrifuge tube 
* Centrifuge tube (15 mL)
* :ref:`Agarose (5%) <agarose>`
* Virus stock
* :ref:`Phosphate buffer saline (PBS) <pbs>`
* Serological pipette (5 mL, 10 mL)
* Micropipette (1000 uL)
* Micropipette tips 
* Waste beaker 

Infection and treatment
-----------------------

Before the actual infection and treatment, we need have 2 information ready: 

#. Different concentrations of the compound we wanted to test. 

    We would dilute the compounds we wanted to test to the desired concentrations with 2% DMEM. The final volume of the compound we prepare should be 1500 uL. This volume is sufficient for a 6 well plate, we can be reduce the volume accordingly if we are using well plates of smaller sizes.

#. Dilution of virus stock to the concentration we wanted to work with. 

    We need to know the pfu/mL of the virus stock and determine the MOI we wanted to use in order for this to work. We usually to 10 times dilution with 2% DMEM to the diluted concentration of virus stock we wanted to work with. 

**Procedure**

#. Remove existing media from well plate. 
#. Wash cells with PBS. 
#. Add 350 uL of diluted compound into their assigned wells.
#. Add the calculated amount of diluted virus stock to assigned wells. 
#. Incubate. 37C, 1 hr. Tilt well plate every 20 mins. 
#. After 1 hr, remove the well plate from incubator. 
#. Remove existing media in the well plate. 
#. Wash cells with PBS. 
#. Add the 1000 uL of compound-containing media into their assigned wells. 
#. Incubate. 37C, 48 hr. 

Section 3 - Harvest
-------------------

* Observe the well plate every 24 hrs for formation of CPE. 
* The media in the well plates can be harvested at 48 hours. 

**Procedure**

#. Label microcentrifuge tube. 
#. Aliquot the existing media in the well plates into different microcentrifuge tube.

    * Distributing the media in each well into multiple microcentrifuge tube so we do not have to thaw and freeze the sample repeatedly when we need to do plaque assays. 

#. Snap freeze the microcentrifuge tube in liguid nitrogen. 
#. Store at -80 C. 

Plaque assay
------------

Do a regular :ref:`plaque assay <plaque assay>` with media harvested from each well in the antiviral assay. Then quantify by manually counting the number of plques. Get the pfu/mL from the plaque assay. 

Calculate percentage of inhibition
----------------------------------

:math:`\text{Percentage of inhibition (%)}=\frac{C-T}{C}\times 100\%`

C = Virus control; T = Treated

Citation for this calculation had been published :footcite:p:`low2021antiviral`.

References 
----------

.. footbibliography::