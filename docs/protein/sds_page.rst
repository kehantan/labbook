.. _sds-page:

SDS-PAGE
========

**Objective:** To run SDS-PAGE and check for fractions with target protein in protein purification process. 

* A single run of SDS-PAGE will usually eats up a whole day. This does not include time required to prepare all the buffers and gathering all required reagent. So plan the experiment accordingly and prepare the buffers at least 1 day before the actual procedure. 
* SDS-PAGE for this protocol uses about 12-15% gel. I personally sticks to 12%. 

Prepare gel 
-----------

* Two gels need to be prepared: resolving gel and stacking gel. 
* The protocol can be found in BIO-RAD's 'Handcasting Polyacrylamide Gels' documentation 
* Depending on the number of gels to be run, we do not need to prepare the amount as stated in the documentation. We can half the amount stated in the documentation. 

**Requires**

* 30% Acrylamide/bis (PAGE Pre-solution)
* 0.5 M Tris-HCl, pH 6.8
* 1.5 M Tris-HCl, pH 8.8 
* :ref:`10% SDS <sds>`
* :ref:`10% APS <aps>`
* Distilled water
* TEMED 

**Procedure** 

#. Prepare 2 small beaker for resolving gel and stacking gel. Prepare 1 larger beaker for distilled water. 
#. Prepare the resolving and stacking gel solution according to the table, but leave out APS and TEMED.

    * The sequence is to cast resolving gel first then only cast stacking gel. 
    * Can prepare the resolving gel first, then prepare stacking gel immediately after. Another option is to prepare and cast the resolving gel first, then prepare the stacking gel while waiting for the resolving gel to solidify. 

Cast gel
--------

**Requires**

* Casting frame 
* Casting stand
* Tall and short glass plate
* Wash bottle filled with distilled water
* Comb

**Procedure**

**Setup**

Refer to YouTube videos on how to setup the gel casting apparatus. 

#. Put short glass plate infront of tall glass plate, with the gap sandwiched in the middle of the two plates. 
#. Place the glass plate sandwich into casting frame. 

    * Make sure the bottom of glass plates are aligned with the casting frame and flat. 
    * The glass plates should only be able to go into the casting frame in one orientation. 

#. Secure the casting frame on the casting stand with the clip on the top. 
#. With a wash bottle filled with distilled water, dispense small amount of distilled water to the bottom of the glass plates. 

    This step is to make sure there are no leakage and to make sure the setup is secured.

#. Remove the distilled water. 

    Can either remove with a filter paper or just decant the water into sink. 

#. After the distilled water was removed, the gel is ready to cast. 

**Casting resolving gel**

#. Add APS and TEMED into the resolving gel solution. 
#. Mix the resolving gel solution well by repeating pipette a few times. 
#. Pipette the resolving gel solution into the gap between the two glass plates.
#. Fill the resolving gel to about 2 cm from the top of the opening of the glass sandwich. 
#. Add distilled water on top of resolving gel. 
#. Let it sit for about 30 mins. The resolving gel should solidifies after 30 mins. 

    One way to check it is by looking through the casted gel. The distilled water and the gel should form 2 seperate layers, with a barely visible fine line between the layers.  

#. Remove the water on top of the resolving gel. 

    Can either remove with a filter paper of just decant the water into sink.

**Casting stacking gel**

#. Add APS and TEMED into the stacking gel solution. 
#. Mix the stacking gel solution well by repeating pipette a few times. 
#. Pipette the stacking gel solution into the gap between the glass plates.
#. Fill the stacking gel on top of the resolving gel until the opening of the glass sandwich.  
#. Make sure the well on the comb is the number of wells you need. Insert the comb into the stacking gel. 
#. Let it sit for about 30 mins. The stacking gel should solidifies after 30 mins. 
#. After 30 mins, slowly remove the comb. The gel should be ready to assemble and load with samples. 

Assemble setup
--------------

**Requires**

* Casted gel
* Dummy plate
* Buffer tank
* Cassette
* :ref:`Running buffer <running buffer>`

**Procedure**

#. Remove the casting frame that contains the casted gel from the casting stand. 
#. Release the clamp of casting frame and remove the glass plates from the casting frame.
#. Place the glass plates into one side of the cassette. If you are only running one gel, place a dummy plate on the other side of the cassette.

    Make sure the lower glass plate facing the inside of the cassette. Direction is important, this allows a closed circuit to form.  

#. Secure the glass plates and the dummy plate with the clamps on both sides. 
#. Insert the cassette into the buffer tank.
#. Fill the inner compartment of the cassete (the space between glass plates and dummy plate) with running buffer until the brim. Fill the buffer tank (outside of the cassette) with running buffer until the marker on the buffer tank. 

    The marker on the buffer tank shows the buffer level for at least 2 plates. I usually just fill up to the '2 gel' marker even I am only running 1 gel.

Prepare sample
--------------

**Requires**

* PCR tubes
* Thermal cycler
* Sample buffer
* :math:`{\beta}`-mercaptoethanol/BME

**Procedure**

#. Prepare PCR tube and label them. 
#. Aliquot sample and sample buffer into the PCR tubes at a 1:1 ratio. 

    E.g.: 10 uL of sample + 10 uL of sample buffer

#. Add BME to each sample. 5% of total sample volume.

    * E.g.: 5% of 20 uL of final sample volume (10 uL sample + 10 uL sample buffer) = 1 uL BME
    * BME has strong fishy smell and is toxic. Prepare sample in fume hood. 

#. Spin down with a PCR centrifuge for about 15 secs.
#. Load the PCR tubes with samples into the thermal cycler. 
#. Set the thermal cycler. 95 :math:`^{\circ}`\ C, 5 mins. 
#. Run the thermal cycler.

*Note:* It is best to prepare the sample just before loading. From experience, it will be easier to load when the sample is stil warm. It will be more difficult to load the samples after they cooled down. 

Sample loading
--------------

* Depends on the gel you casted (there are different thickness for the gels), the volume of the sample wells can varies. 
* I usually just use 10 uL of the sample prepare on previouse steps. 

**Requires**

* Ladder 

**Procedure**

#. Aspirate 5 uL of ladder with micropipette. 
#. Place the micropipette tip directly on the top of the first well of the gel. 
#. Dispense the sample slowly. The ladder sample should drop directly into the wells.
#. Repeat the steps again, aspirate 10 uL of the prepared sample and dispense into each well.   

Running gel
-----------

**Requires**

* Electrodes
* Power supply unit 

**Procedure**

#. Make sure the electrodes are correctly attached.

    Red to red, black to black

#. Set the power supply unit. 

    * 300 V, 50 amp, around 60 mins.
    * For some older units, the voltage might not be constantly sitting at 300 V. It is alright as long as the amp is stable. 

#. Start the electrophoresis. 

    Many tiny bubbles will bee seen raising from the bottom of the gel to the surface.

#. Observe the progress of the eletrophoresis every 15 mins to make sure not to overrun. Stop the electrophoresis when the ladder reaches about 1 cm from the bottom of the gel. 

Remove gel
----------

Remove gel from the glass plate 

**Requires**

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

**Requires**

* :ref:`Fixing solution <fixing>`

**Procedure**

#. After transferring the gel into the plastic container. Fill the container with fixing solution. 
#. Remove fixing solution. 

Staining
--------

**Requires**

* :ref:`Coomassie blue staining solution <coomassie>`
* Rocking platform

**Procedure**

#. Fill the plastic container with Coomasie blue stain to about 1 cm of height.
#. Place the container on the rocking platform. 
#. Stain the gel for about 30 mins.  
#. Remove the staining solution after 30 mins. 

*Note:* Can pour the staining solution back into the centrifuge tube for reuse.  

Destaining
----------

**Requires**

* :ref:`Destaining solution <destaining>`
* Kim wipes 
* Distilled water
* Rocking platform

**Procedure**

#. Fill the plastic container with distilled water. 
#. Put Kim wipes at the side of the container.
#. Place the plastic container on the rocking platform.
#. Destaining overnight. 

Clean up
--------

* The remaining gel solution in the small beaker from resolving gel and stacking gel would solidify over time. When this happens, break the gel (with any stuff you could find, like pipette tips or spatula) then dispose in the yellow bin. **DO NOT** throw in the sink, the solidified gel will clog up the piping system. 
* Buffers can be flush down the sink. 
* Wash all apparatus and leave it to dry at the rack beside the sink.
* Distilled water used for destaining can be discard into the sink. 