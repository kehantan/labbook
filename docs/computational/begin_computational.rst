Before we begin computational work...
=====================================

There are several things we need to get straight before diving into computational stuff

#. Molecular docking and molecular dynamics simulations are not **MAGIC BLACK BOX**, do not treat them as such.
#. **RUBBISH IN, RUBBISH OUT.** Data generated from computational calculations can get exponentially large, but not all of them are useful. You will also need to know how to extract the useful parts. 
#. Molecular docking and molecular dynamics simulations cannot work when you do not know the specific protein target you wanted to look into.

    Example: Yes, you know the specific genes, you get the gene names, but those genes translate into which specific protein? What about post-translational modification?...

Some questions to ask before begin molecular docking and molecular dynamics:

* Is the protein target you want to study available on Protein Data Bank (PDB)?
* If not available, is there a close family member of the protein of interest available in PDB? 
* If close family member of the protein of interest is available, what is the similarities? Can you generate a homology model from that close family member?
* If close family member of the protein of interest is not available, what are the other approach to generate a protein structure? AlphaFold? Ab initio? 
* Is the generated structure valid? How to verify the validity? 
* If the protein target is available on PDB, is there any known binding site or interaction site? If it is a large protein, is the part available in PDB the part that you wanted to study? 

Like any other wet lab experiments, computational work **IS ALSO EXPERIMENT**. You will still need to read a lot, hands-on, trial and error, to understand much of the inner workings of computational stuff and know its limitations. 