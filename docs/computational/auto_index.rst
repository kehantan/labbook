Create index file in automation
===============================

To create index file in GROMACS without manual human input which is useful for automation. 

Create a file which contains all the input we want, i.e.: :code:`chain B & r 51`, :code:`chain B & r 75`, etc., and name the file :code:`index_entry.txt`. The :code:`index_entry.txt` file should look something like this 

.. code-block:: 

    chain B & r 51 
    chain B & r 75 
    chain B & r 135 
    23|24|25 
    q

*Note:* Remeber to put the :code:`q` at the end of the index entry file, or GROMACS will exit without actually creating the index group.  

Then run the :code:`make_ndx` module in GROMACS by supplying the :code:`index_entry.txt` file.

.. code-block:: 

    gmx make_ndx -f em.gro -o index.ndx < index_entry.txt