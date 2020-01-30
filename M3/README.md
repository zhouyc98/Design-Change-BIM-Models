# Background  
This folder contains 11 BIM models, one of them is the original model (i.e., M3), and the other 10 are derived models that include only one type of change from the original model. M3 is a Revit sample project named [rac_advanced_sample_project](http://www.autodesk.com/revit-rac-advanced-sample-project-2018-enu), the following figure shows a screenshot of it.  
The version of Revit files is Revit 2018, the version of IFC files is IFC 2x3.  

![image](https://github.com/Zhou-Yucheng/Design-Change-BIM-Models/blob/master/images/M3-screenshot.png)

# Design Change Information
The following table shows the design change information of this group of BIM model.  

|Model Name|Category of Data change<sup>a</sup>|Level of Design Change|Description of Changes|
|:--|:--|:--|:--|
|M3|-|-|The origin model|
|M3_All-A|Added in P, A and R|Instance|Add 1 plant (cherry tree) and 1 column|
|M3_All-D|Deleted in P, A and R|Instance|Delete some elements|
|M3_All-DA(M)|Deleted and then added in P, A and R|Model|Delete 2 columns at 01-Entry Level and recreate them|
|M3_A-MG|Geometry modified in A|Instance|Modify the sections of 2 columns|
|M3_A-MG(T)|Geometry modified in A|Type|Modify the "bf" of family M_W-Wide Flange-Column from 202 to 212|
|M3_A-ML|Location modified in A|Instance|Modify the location of 1 column at 01-Entry Level|
|M3_A-ML(M)|Location modified in A|Model|Exchange the locations of 2 columns at 01-Entry Level|
|M3_P-MV|Value modified in P|Instance|Modify a parameter (COMMENTS) in a column|
|M3_R-MI(M)|Instance modified in R|Model|Modify the elevation of a level (Parapet) from 12000 to 13000|
|M3_R-MR|Relationship modified in R|Instance|Modify the top level of a plate|

<sup>a</sup> P, A, R means Property data, Appearance data, Relationship data respectively.   
