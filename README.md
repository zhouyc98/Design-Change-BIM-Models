# Design-Change-BIM-Models

This repo contains testing BIM models for the paper entitled "Classification and Exemplary BIM Models Development of Design Changes".  

Use the following data to reference this repo or the paper:  
Lin, J., Zhou, Y., Zhang, J. and Hu, Z., Classification and Exemplary BIM Models Development of Design Changes. International Symposium on Automation and Robotics in Construction, 2019. (submitted)

# Background and Objectives

Detection of design changes is essential for collaboration and version management in the design process of buildings. However, current detection methods based on Building Information Modeling (BIM) usually cause unreliable or meaningless results. This is because most of the current researches look at the question from a data change view, which sometimes is meaningless from a designer’s view.  
To overcome this problem, this paper first classifies and identifies meaningful design changes from a designer's view, and develops exemplary BIM models of typical design changes. The test of two BIM tools (Autodesk BIM360 and IFCdiff) with developed BIM models shows that the detection results for changes at instance level are perfect while detection results for type and model level still need to be further improved. 

# Contributions

This work contributes a new view and classification method of design changes, and also sets up a baseline model database for further development and validation of relevant methods and tools.

# Information of Models

Folder M1 contains two folders IFC and RVT, both of which have 11 BIM models (the contents of the files have the same name are the same). The detailed information of exemplary BIM models in folder M1 is shown in the Table below.  

|Model Name|Category of Data change<sup>a</sup>|Level of Design Change|Description of Changes|Meaningful<sup>b</sup>|
|:--|:--|:--|:--|:--|
|M1|-|-|The origin model| |
|M1_All-A|Added in P, A and R|Instance|Add 2 beams and 2 columns (new category)|O|
|M1_All-D|Deleted in P, A and R|Instance|Delete 2 beams and 4 columns|O|
|M1_All-DA(M)|Deleted and then added in P, A and R|Model|Delete 2 beams and 4 columns and recreate them|X|
|M1_A-MG|Geometry modified in A|Instance|Modify the sectional dimensions of 2 beams|O|
|M1_A-MG(T)|Geometry modified in A|Type|Modify the section of family of a beam from 400×800 to 800×400|O|
|M1_A-ML|Location modified in A|Instance|Modify the location of 4 columns and 2 beams|O|
|M1_A-ML(M)|Location modified in A|Model| Exchange the location of 2 pairs of columns and 1 pair of beams|X|
|M1_P-MV|Value modified in P|Instance|Modify a parameter (COMMENTS) in a beam|O|
|M1_R-MI(M)|Instance modified in R|Model|Modify the elevation of a level (Level3)|O|
|M1_R-MR|Relationship modified in R|Instance|Modify the top level of 4 columns|O|

<sup>a</sup> P, A, R means property data, appearance data, relationship data respectively.  
<sup>b</sup> O and X means the change is meaningful and meaningless respectively.
