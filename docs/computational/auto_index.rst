Create index file in automation
===============================

To create index file in GROMACS without human input which is useful for automation. 

Create a file which contains all the input we want, i.e.: :code:`chain B & r 51` and name the file :code:`index_entry.txt` 

.. code-block:: 

    gmx make_ndx -f em.gro -o index.ndx < index_entry.txt