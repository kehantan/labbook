Antiviral assay
===============

* The protocol for antiviral had been published :cite:`lani2016antiviral,florez2022vitro,marin2021curcumin`. 
* This protocol was separated into different sections, each section indicates that after that procedure was completed, have to wait until the next day (or after 2 days) to proceed to the next section. 
* This protocol demonstrate plaque assay in 6 well plate. For plaque in 12 well plate or well plate of other sizes, the procedures are the same, just the volume of liquids, number of cells, and volume of reagents used are different. 
* Before starting antiviral assay, several informations are required.

    * Virus titer of the virus stock, in pfu/ml

        This information can be obtain from doing plaque assay using the virus stock.

    * MOI to use

        Refer to published articles for the MOI suitable for the experiments. Common MOI to use including 1, 0.5, 0.1.    

    * Concentration of compound to be tested

        This requires some trial and error. For organically synthesised small molecule compounds, I usually start with 50 ug/mL then serial dilute 1/2 to 6 to 7 concentrations. The concentration could be adjusted to higer value depends on the type of compounds to be tested, ie: peptides, plant extracts, etc. 

Section 1 - Trypsininse, cell count, seed cells
-----------------------------------------------

* For antiviral assay, cells should be at around 70% confluency at the day of infection and treatment. 

    * For 6 well plate, seed 450,000 cells for next day infection and treatment. 
    * For 12 well plate, seed 150,000 cells for next day infection and treatment. 

**Materials**

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

#. Add 1500 uL of complete DMEM into each well in the 6 well plate.

    * 1000 uL of 10% DMEM into each well if using 12 well plate 

#. Add correct amount of cells into each well. 
#. Tilt the well plate back and forth and side to side to distribute the cells evenly across the base of the wells. 
#. Incubate. 37 C, 24 hrs. 

Section 2 - Infection and treatment 
-----------------------------------

* Before starting any procedure, 

    * check the cell confluency in the 6 well plate under microscope. The cells should be around 70% confluency. 
    * plan well plate layout 
    * determine MOI to be used 
    * plan a 1/2 serial dilution for the compound to be tested

Plan well plate layout
~~~~~~~~~~~~~~~~~~~~~~

* Below is a layout of a 6 well plate 

(A1) (A2) (A3) 

(B1) (B2) (B3) 

    * A1 = Negative control (Cells without virus infection)
    * B1 = Virus control (Cells with virus infection, but not treated with compound)
    * A2, A3, B2, B3 = Cells infected with virus infection and treated with compound
    
* This is merely a suggestion, you can tailor the arrangement however you like according to the need of your experiments, but always remember to include negative control and virus control wells. 

Calculate virus volume to use for infection
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

:math:`\frac{\text{Virus need (MOI)}}{\text{Virus titer}} = X\ mL`

* MOI = multiplicity of infection

    * MOI = 1, 1 virus particle for each cell 
    * MOI = 0.5, 1 virus particle for every 2 cells 
    * MOI = 0.1, 1 virus particle for every 10 cells  

* If 450,000 cells seeded in each well, MOI = 0.1 is to be used, then 45,000 virus particles needed for each well  

    :math:`0.1 \times 450,000 = 45,000`

* Assume virus titer of the virus stock = :math:`1 \times 10^{10}\ \text{pfu}/mL`, then using the formula above, we can determined that we need to put 0.0045 uL of virus stock in each well. 

    :math:`\frac{45,000}{1 \times 10^{10}} = 4.5 \times 10^{-6} mL (0.0045 \mu L)`

* However, 0.0045 uL is not feasible to aspirate with micropipette, so to work around this issue, dilute the virus sample to a reasonable concentration. 
* Repeat the formula again, this time, use :math:`1 \times 10^{6}` for the virus titer.

    :math:`\frac{45,000}{1 \times 10^{6}} = 0.045 mL (45 \mu L)`

* 45 uL is a feasible volume to work with. So, from :math:`1 \times 10^{10}` to :math:`1 \times 10^{6}`, we need to do 10 times dilution for 4 times.

    :math:`1 \times 10^{10}` (Virus stock) > :math:`1 \times 10^{9}` > :math:`1 \times 10^{8}` > :math:`1 \times 10^{7}` > :math:`1 \times 10^{6}`

* Virus need is supposedly the number of cells in each well at the day of infection, but it is impractical to count the cells in each well, so we just assumes that the number of cells in the well is the number of cells seeded, although that is not true. 

Plan serial dilution of compounds
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

* Assume stock solution of compound to be tested was prepared at concentration of 20,000 ug/mL (20 mg/mL).
* We would perform 1/2 serial dilution with 50 ug/mL as highest concentration and final volume of 1500 uL. 

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
* Vortex
* Rack

**Procedure**

**Virus dilution** 

#. Label 4 microcentrifuge tube with different dilution factor.

    V1 - 10:sup:`-9`, V2 - 10:sup:`-8`, V3 - 10:sup:`-7`, V4 - 10:sup:`-6`

#. Add 450 uL of 2% DMEM into each microcentrifuge tube.
#. From the virus stock, transfer 50 uL virus into the microcentrifuge tube labelled V1. Mix well by repeat pipetting or using a vortex. 
#. Transfer 50 uL from V1 to V2. Mix well by repeat pipetting or using a vortex. 
#. Repeat the process until the last tube. 50 uL from V4 can be discard.   
#. Set the tubes aside for later use. 

**Compound dilution** 

#. Prepare and label four 15 mL centrifuge tube. 

    C1 - 50, C2 - 25, C3 - 12.5, C4 - 6.25

#. Add 3000 uL of 2% DMEM into C1, add 1500 uL of 2% DMEM into C2, C3, and C4. 
#. From stock solution of compound (20,000 ug/mL), transfer 7.5 uL into C1. Mix well by repeat pipetting or using a vortex. 
#. Transfer 1500 uL of solution from C1 to C2. Mix well by repeat pipetting or using a vortex. 
#. Repeat the process for the remaining centrifuge tube. 
#. Set the centrifuge tube aside for later use. 

**Infection and treatement** 

#. Label each well on the 6 well plate. 

    +----+----+----+
    | NC | C1 | C3 |
    +----+----+----+
    | VC | C2 | C4 |
    +----+----+----+
    
    * NC = Negative control; VC = Virus control

#. Remove existing media from the 6 well plate. 
#. Wash cells with PBS. 
#. Add 300 uL of 2% DMEM into NC and VC well. 
#. Transfer 300 uL of solution from centrifuge tube C1 into well labelled C1. Repeat for C2, C3, and C4. 
#. Add the calculated amount of diluted virus stock to assigned wells.

    * In this example, 45 uL of V4 into each well, except NC well. 
    * Use different pipette tips for each well. 

#. Incubate. 37 C, 1 hr. Tilt well plate every 20 mins. 
#. After 1 hr, remove the well plate from incubator. 
#. Remove existing media in the well plate.

    * Use different pipette tips for each well. 

#. Wash cells with PBS. 
#. Add 1000 uL of 2% DMEM into NC and VC well. 
#. Add 1000 uL of solution from centrifuge tube C1 into well labelled C1. Repeat for C2, C3, and C4. 
#. Incubate. 37 C, 48 hr. 

Section 3 - Harvest
-------------------

* Observe the well plate every 24 hrs for formation of CPE and detachment of cells. 
* The media in the well plates can be harvested at 48 hours. 

**Requires**

* Micropipette (1000 uL)
* Micropipette tips
* Microcentrifuge tube
* Waste beaker

**Procedure**

#. Label 4 microcentrifuge tube VC-1, VC-2, VC-3, VC-4. Include date and name initials on the tube. 
#. In each microcentrifuge tube labelled VC-1, VC-2, VC-3, and VC-4, transfer 250 uL of existing media in VC well into each tube.
#. Repeat the same steps for each concentration, except for NC well. Media in NC well can be discarded. 
#. Snap freeze all the microcentrifuge tube in liguid nitrogen. 
#. Store at -80 C. 

Plaque assay
------------

* Do a regular :ref:`plaque assay <plaque assay>` with media harvested from each well in the antiviral assay. Then quantify by manually counting the number of plques. 
* Get the pfu/mL from the plaque assay. 

Calculate percentage of inhibition
----------------------------------

:math:`\text{Percentage of inhibition (%)}=\frac{C-T}{C}\times 100\%`

C = Virus control; T = Treated

Reference for this calculation: :cite:`low2021antiviral` 

