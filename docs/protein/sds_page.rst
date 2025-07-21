.. _sds-page:

SDS-PAGE
========

**Objective:** To run SDS-PAGE and check for fractions with target protein in protein purification process. 

* A single run of SDS-PAGE will usually eats up a whole day. This does not include time required to prepare all the buffers and gathering all required reagent. So plan the experiment accordingly and prepare the buffers at least 1 day before the actual procedure. 
* https://wisc.pb.unizin.org/biochemistry551online/chapter/procedure-3/

Prepare gel 
-----------

* Two gels need to be prepared: resolving gel and stacking gel. 
* The protocol can be found in BIO-RAD's 'Handcasting Polyacrylamide Gels' documentation 
* Depending on the number of gels to be run, the amount stated in the documentation can be halved. 

**Materials**

* 30% Acrylamide/bis (PAGE Pre-solution)
* :ref:`Stacking buffer <stacking>` (0.5 M Tris-HCl, pH 6.8)
* :ref:`Resolving buffer <resolving>` (1.5 M Tris-HCl, pH 8.8)
* :ref:`10% SDS <sds>`
* :ref:`10% APS <aps>`
* Distilled water
* TEMED 
* Micropipette (1000 uL, 100 uL, 10 uL)
* Micropipette tips (1000 uL, 100 uL, 10 uL)
* Small volume beaker (25 mL)
* Microcentrifuge tube
* Waste beaker 

**Procedure** 

#. Prepare APS before preparing gel. 

    * APS can be prepared earlier and store in -20, but I like to prepare APS fresh. 

#. Prepare 2 small beaker for resolving gel and stacking gel.
#. Prepare the resolving and stacking gel solution according to the table, but leave out APS and TEMED.

    * The sequence is to cast resolving gel first then only cast stacking gel. 
    * Can prepare the resolving gel first, then prepare stacking gel immediately after. 
    * Another option is to prepare and cast the resolving gel first, then prepare the stacking gel while waiting for the resolving gel to solidify. 

Cast gel
--------

**Materials**

* Casting frame 
* Casting stand
* Tall and short glass plate
* Wash bottle filled with distilled water
* Comb

**Procedure**

*Gel casting setup*

* Can refer to YouTube videos on how to setup the gel casting apparatus. 

#. Put short glass plate infront of tall glass plate, with the gap sandwiched in the middle of the two plates. 
#. Place the glass plate sandwich into casting frame. 

    * Make sure the bottom of glass plates are aligned with the casting frame and flat. 
    * The glass plates should only be able to go into the casting frame in one orientation. 

#. Secure the casting frame on the casting stand with the clip on the top. 
#. With a wash bottle filled with distilled water, dispense small amount of distilled water to the bottom of the glass plates. Make sure the setup is secured and there are no leakage at the bottom.
#. Remove the distilled water by decanting the water directly into the sink or using a filter paper. 
#. After the distilled water was removed, the gel is ready to be cast. 

*Casting resolving gel*

#. Add APS and TEMED into the resolving gel mixture. Mix well by repeating pipette. 
#. Add resolving gel mixture into the gap between the two glass plate.
#. Fill the resolving gel to about 2 cm from the top of the opening of the glass sandwich. 
#. Add distilled water on top of resolving gel. 
#. Let it sit for about 45 to 60 mins. The resolving gel should solidifies after 45 mins. 

    * One way to check it is by looking through the casted gel. The distilled water and the gel should form 2 seperate layers, with a barely visible fine line between the layers.
    * Another way is to tilt the casting frame a bit, you should see the water on top of resolving gel flow out and the resolving gel forming a solid layer.   

#. Remove the water on top of the resolving gel by decanting the water into sink or with a filter paper. 

*Casting stacking gel*

#. Add APS and TEMED into the stacking gel solution. Mix well by repeating pipette. 
#. Add stacking gel mixture into the gap between the glass plates.
#. Fill the stacking gel on top of the resolving gel until the opening of the glass sandwich.  
#. Make sure the well on the comb is the number of wells you need. Insert the comb into the stacking gel. 
#. Let it sit for about 30 mins. The stacking gel should solidifies after 30 mins. 
#. After 30 mins, slowly remove the comb. The gel should be ready to assemble and load with samples. 

Assemble setup
--------------

**Materials**

* Casted gel
* Dummy plate
* Buffer tank
* Cassette
* :ref:`Running buffer <running buffer>`

**Procedure**

#. Remove the casting frame from the casting stand. 
#. Release the clamp of casting frame and remove the glass plates from the casting frame.
#. Place the glass plates into one side of the cassette. If you are only running one gel, place a dummy plate on the other side of the cassette.

    * There are two types of cassette. If you are running only one gel, use the cassette with the electrode sticking out. If you use the one without electrode sticking up, the gel won't run, the power supply will give error when you press start.  
    * Make sure the lower glass plate facing the inside of the cassette. If using dummy plate, there are texts engraved on the plate to indicate which side of the plate should be facing inwards. Direction is important, this allows a closed circuit to form.  

#. Secure the glass plates and the dummy plate with the clamps on both sides. 
#. Insert the cassette into the buffer tank. Match the colour, black to black, red to red. 
#. Fill the inner compartment of the cassete (the space between glass plates and dummy plate) with running buffer until the brim. Fill the buffer tank (outside of the cassette) with running buffer until the marker on the buffer tank. 

    * The marker on the buffer tank shows the buffer level for at least 2 plates. I usually just fill up to the '2 gel' marker even I am only running 1 gel.
    * Buffer can be recover and reused, but not recommend to reuse for too many times. Recommend reuse 3-5 times only.  

Prepare sample
--------------

**Materials**

* PCR tubes
* Thermal cycler
* Sample buffer
* :math:`{\beta}`-mercaptoethanol (BME)

**Procedure**

#. Prepare PCR tube and label them. 
#. Add sample and sample buffer into the PCR tubes at a 1:1 ratio. 

    * 10 uL of sample + 10 uL of sample buffer. 

#. Add BME to each sample. 5% of total sample volume.

    * E.g.: 5% of 20 uL of final sample volume (10 uL sample + 10 uL sample buffer) = 1 uL BME
    * BME has strong fishy smell and is toxic. Prepare sample in fume hood. Turn on ventilation fan, fan inside lab, and switch on fume hood fan few mins before adding BME to sample.

#. Spin down with a PCR centrifuge for about 15 secs.
#. Load the PCR tubes with samples into the thermal cycler. 
#. Set the thermal cycler. 95 C, 5 mins. 
#. Run the thermal cycler.

Sample loading
--------------

* Depends on the gel you casted (there are different thickness for the gels), the volume of the sample wells can varies. 
* I usually just use 10 uL of the sample prepare on previouse steps. 

**Materials**

* Ladder 
* Micropipette (10 uL)
* Micropipette tips (10 uL)

**Procedure**

#. Add 3 uL of ladder into the first well in the gel. 
#. Add 10 uL of the prepared sample into each remaining well.   

Running gel
-----------

**Materialss**

* Electrodes
* Power supply unit 

**Procedure**

#. Make sure the electrodes are correctly attached.

    * Red to red, black to black.
    * Make sure the cassette is in the correct slot. The top cover can only go in one orientation. 

#. Set the power supply unit. 

    * 300 V, 50 amp, 75 mins.
    * For some older units, the voltage might not be constantly sitting at 300 V. It is alright as long as the amp is stable. 

#. Start the electrophoresis. 
#. Observe the progress of the eletrophoresis about every 15 to 20 mins to make sure not to overrun. Stop the electrophoresis when the ladder reaches about 1 cm from the bottom of the gel. 

Remove gel
----------

**Materials**

* Small plastic container that can fit the gel
* Squeeze bottle with distilled water

**Procedure**

#. Lift the cassette from the tank. 
#. Release the clamp. 
#. Remove the dummy plate. 
#. Decant buffer from inner compartment into the tank. 
#. Remove the glass plates. 
#. Carefully pry open the glass plates and lift the shorter glass plate. 
#. Remove the stacking gel by slicing it off with the glass plate. 
#. Rinse with distilled water using a squeeze bottle. 
#. Hold the glass plate with gel above a plastic container. Carefully seperating the gel from the glass plate by lifting the gel with a pipette tip. Rinse with distilled water at the same time. 
#. Tilt the glass plate at an angle and rinse with distilled water, the gel should slide into the plastic container.

Fixing
------

* Protocol for Coomassie staining of SDS-PAGE can be found `here <https://www.aatbio.com/resources/application-notes/protocol-for-coomassie-staining>`_.

**Materials**

* :ref:`Fixing solution <gel-fixing>`
* Rocking platform 

**Procedure**

#. After transferring the gel into the plastic container, cover the gel with fixing solution.
#. Place the containeer on rocking platform for about 10 mins to 1 hr.
#. Remove fixing solution.

Washing
-------

**Materials**

* :ref:`Gel-washing solution <gel-washing>`
* Rocking platform 

**Procedure**

#. Cover the gel with gel washing solution.
#. Place the container on the rocking platform. 
#. Let the washing solution sit for about 2 hrs to overnight. 
#. Remove washing solution.   

Staining
--------

**Materials**

* :ref:`Coomassie blue staining solution <coomassie>`
* Rocking platform

**Procedure**

#. Cover the gel with Coomasie blue stain.
#. Place the container on the rocking platform. 
#. Stain the gel for about 30 mins to 3 hrs.  
#. Remove the staining solution. 

Destaining
----------

**Materials**

* :ref:`Destaining solution <destaining>`
* Kim wipes 
* Rocking platform

**Procedure**

#. Cover the gel with destaining solution.
#. Surround the gel with Kim wipes.
#. Place the plastic container on the rocking platform.
#. Destain overnight. 
#. Decant the destaining solution. 

Storage
-------

* For long term storage, it is best to store the gel in gel-storing solution. 
* It is normal for the edges of the gel to deformed when it dries out. 

**Materials**

* :ref:`Gel-storage solution <gel-storage>`
* Plastic container 

**Procedure**

#. Cover the gel with storage solution. 

Clean up
--------

* The remaining gel solution in the small beaker from resolving gel and stacking gel would solidify over time. When this happens, break the gel (with any stuff you could find, like pipette tips or spatula) then dispose in the yellow bin. **DO NOT** throw in the sink, the solidified gel will clog up the piping system. 
* Running buffers can be pour back into a bottle and reuse, but I do not recommend using it more than 5 times. 
* The buffer can be discard into the sink. 
* Wash all apparatus and leave it to dry at the rack beside the sink.

Item checklist
--------------

* 30% Acrylamide/bis (PAGE Pre-solution)
* Tris-HCl powder
* NaOH
* SDS powder
* APS powder
* Distilled water
* TEMED 
* Mdicropipette and tips (1000 uL, 100 uL, 10 uL)
* Beaker (25 mL)
* Microcentrifuge tube (1.5 mL)
* Waste beaker 
* Power supply 
* Buffer tank
* SDS-PAGE Glass plate 
* Glass plate clamp 
* SDS-PAGE cassette 
* Tris base powder
* Glycine powder 
* Coomassie blue powder
* Methanol
* Ethanol 
* Acetic acid 
* Distilled water or MilliQ water 
* Measuring cylinder
* Bottle (500 mL)
* Filter (0.45 um)
* Syringe 
* Glycine
* Tris-base
* SDS