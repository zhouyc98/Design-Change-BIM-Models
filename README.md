# Design-Change-BIM-Models

This repo contains testing BIM models for the paper entitled "Classification and Exemplary BIM Models Development of Design Changes" and "Semantic Classification and Hash Code Accelerated Detection of Design Changes in BIM Models".   

Use the following data to reference this repo or the paper:  
Lin, J. R., Zhou, Y. C., Zhang, J. P., & Hu, Z. Z. (2019). Classification and Exemplary BIM Models Development of Design Changes. ISARC. Proceedings of the International Symposium on Automation and Robotics in Construction, 36, 122–127.
Lin, J.-R., & Zhou, Y.-C. (2020). Semantic classification and hash code accelerated detection of design changes in BIM models. Automation in Construction, 115, 103212. https://doi.org/10.1016/j.autcon.2020.103212


# Background and Objectives

Detection of design changes is essential for collaboration and version management in the design process of buildings. However, current detection methods based on Building Information Modeling (BIM) usually cause unreliable or meaningless results. This is because most of the current researches look at the question from a data change view, which sometimes is meaningless from a designer’s view.  
To overcome this problem, this research classifies and identifies meaningful (semantic) design changes from a designer's view, and develops exemplary BIM models of typical design changes. The test of two BIM tools (Autodesk BIM360 and IFCdiff) with developed BIM models shows that the detection results for changes at instance level are perfect while detection results for type and model level still need to be further improved. 

# Contributions

This work contributes a new definition of design changes and an approach to efficient design change detection with hash-code-based acceleration, and also sets up a baseline model database for further development and validation of relevant methods and tools.

# Information of Models

Folder M1, M2, and M3 contain three groups of BIM models, where each group of BIM models has 11 models: one of them is the original model, and the other 10 are derived models that include only one type of change from the original model. The names of the original models of these three groups are M1, M2, and M3. M1 is a simple structure frame; M2 is an example house and contains architectural and structural building information; and M3 is a Revit sample project named [rac_advanced_sample_project](http://www.autodesk.com/revit-rac-advanced-sample-project-2018-enu).   
Each folder (M1, M2, and M3) contains:
- a README for their desctiptions and change records
- 11 Revit models (Revit 2018)
- an "IFC" folder which stores some models in IFC format (IFC 2x3).

The following table shows the design change information of the three groups of BIM models M1 - M3. It is also the naming rule for models in M1 - M3.  

|Model Name<sup>a</sup>|Category of Data change<sup>b</sup>|Level of Design Change|
|:--|:--|:--|
|Mx|-|-|
|Mx_All-A|Added in P, A and R|Instance|
|Mx_All-D|Deleted in P, A and R|Instance|
|Mx_All-DA(M)<sup>c</sup>|Deleted and then added in P, A and R|Model|
|Mx_A-MG|Geometry modified in A|Instance|
|Mx_A-MG(T)|Geometry modified in A|Type|
|Mx_A-ML|Location modified in A|Instance|
|Mx_A-ML(M)<sup>c</sup>|Location modified in A|Model|
|Mx_P-MV|Value modified in P|Instance|
|Mx_R-MI(M)|Instance modified in R|Model|
|Mx_R-MR|Relationship modified in R|Instance|

<sup>a</sup> Mx denotes M1, M2, or M3.  
<sup>b</sup> P, A, and R denotes Property data, Appearance data, and Relationship data, respectively.  
<sup>c</sup> These two models contain only meaningless changes (delete and recreate the same instances or exchange locations). 
