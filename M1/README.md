# Background  
This folder contains 11 BIM models, one of them is the original model (i.e., M1), and the other 10 are derived models that include only one type of change from the original model. M1 is a simple structure frame, the following figure shows a screenshot of it.  
The version of Revit files is Revit 2018, the version of IFC files is IFC 2x3.   

![image](https://github.com/Zhou-Yucheng/Design-Change-BIM-Models/blob/master/images/M1-screenshot.png)

# Design Change Information
The following table shows the design change information of this group of BIM model.  

|Model Name|Category of Data change<sup>a</sup>|Level of Design Change|Description of Changes|
|:--|:--|:--|:--|
|M1|-|-|The origin model|
|M1_All-A|Added in P, A and R|Instance|Add 2 beams and 2 columns (new category)|
|M1_All-D|Deleted in P, A and R|Instance|Delete 2 beams and 4 columns|
|M1_All-DA(M)|Deleted and then added in P, A and R|Model|Delete 2 beams and 4 columns and recreate them|
|M1_A-MG|Geometry modified in A|Instance|Modify the sectional dimensions of 2 beams|
|M1_A-MG(T)|Geometry modified in A|Type|Modify the section of family of a beam from 400×800 to 800×400|
|M1_A-ML|Location modified in A|Instance|Modify the location of 4 columns and 2 beams|
|M1_A-ML(M)|Location modified in A|Model| Exchange the location of 2 pairs of columns and 1 pair of beams|
|M1_P-MV|Value modified in P|Instance|Modify a parameter (COMMENTS) in a beam|
|M1_R-MI(M)|Instance modified in R|Model|Modify the elevation of a level (Level3)|
|M1_R-MR|Relationship modified in R|Instance|Modify the top level of 4 columns|

<sup>a</sup> P, A, R means Property data, Appearance data, Relationship data respectively.   
  
  
The following figure shows the design change information of this group of BIM model.  
![image](https://github.com/Zhou-Yucheng/Design-Change-BIM-Models/blob/master/images/M1-Changes.png)
