Screen ChEMBL database for chalcone
===

* If only draw chalcone with double bond, and query by substructure, the database will return results of about 150 molecules. 
* This is because double bond can have E/Z conformations, drawing double bond will return only trans conformation, so to include all E and Z conformations, need to use the cis/trans representation on the double bond. 
* However, if use the cis/trans representation and query by substructure, the database will also return results that consists of cyclised chalcone structure. 
* Of course, we can use similarity query instead of substructure query. However, if using similarity query, how many percentage of similarity should we use? would higher percentage still include cyclised chalcone? will lower percentage miss some of the chalcones?
* So to mitigate this problem, the idea is to first download all the molecules queried by using substructure search. This will include cyclised chalcones. Then we will process the whole thing in RDKit and filter out 'unqualified' chalcones. 
* The main idea is to take the Smiles of chalcone, add explicit hydrogen atoms only to the double bond and use the structure as a reference pattern. 
* Adding hydrogen atoms to the whole chalcone means the ring will also have the hydrogen atoms, which will rule out any other derivatives, potentially return zero substructure match. Therefore, only add hydrogen atoms on the double bond.  
* Extract Smiles from the csv file downloaded from ChEMBL, then add explicit hydrogen atoms to each of the whole molecule. 
* Then search the chalacone substructure within the molecule. 
* Cyclised molecule will not found match because their double bone does not have hydrogen bond attached to it. This can filter out the non useful chalcones. 
* All this was executed in Jupyter Notebook using RDKit.  