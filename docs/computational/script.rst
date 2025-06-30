Bash command for processing MTiOpenScreen results
=================================================

Since ZINC database is down, converting MTiOpenScreen :code:`output.pdbqt` to SMILES using OpenBabel. 

*Workflow*

#. Use :code:`vina_split` to separate the total output files into individual files. 
#. use :code:`awk` to print specific field from the output file and the converted output. 

    * :code:`grep` :code:`ZINC` from the docking output, then :code:`awk` only the :code:`ZINC` part 
    * SMILES output converted using OpenBabel will give the SMILES string first then have the file name appended behind, so :code:`awk` the SMILES string only
    * pass the whole thing in the format :code:`[ZINC ID] [SMILES string]` into a new file
    * However, this will have duplicates, since MTiOpenScreen give 3 conformations in their :code:`output.pdbqt`
    * so finally use :code:`awk '!seen[$1]++' test.smi` to remove the duplicates 