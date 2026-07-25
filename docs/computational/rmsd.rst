RMSD multichain protein
===

Preprocess
-----

* Multichain protein may jump no matter which chain used as center (only chain A, only chain B, or use whole protein, outcome is the same). Therefore, multi step centering was used

#. Center to one chain first, select :code:`chA` for centering

    :code:`gmx trjconv -s md.tpr -f trajout.xtc -n index.ndx -o trajout_chainA.xtc -pbc mol -ur compact -center`

#. Center the output from previous step to another chain, select :code:`chB` for centering

    :code:`gmx trjconv -s md.tpr -f trajout_chainA.xtc -n index.ndx -o trajout_chainB.xtc -pbc mol -ur compact -center`

#. Align structure 

    :code:`gmx trjconv -s md.tpr -f trajout_chainB.xtc -n index.ndx -o trajout_fit.xtc -fit rot+trans`

Outcome 
----

* If only centering to chain A

.. image:: computational_images/rrmsd_chA_bb_lsf_bb_traj_center_protein
    :width: 300