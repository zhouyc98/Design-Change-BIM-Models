# Background  
This folder contains 11 BIM models, one of them is the original model (i.e., M2), and the other 10 are derived models that include only one type of change from the original model. M2 is an example house and contains architectural and structural building information, the following figure shows a screenshot of it (Note that the roof of M2 has been removed).  
The version of Revit files is Revit 2018, the version of IFC files is IFC 2x3.  

![image](https://github.com/Zhou-Yucheng/Design-Change-BIM-Models/blob/master/images/M2-screenshot.png)

# Design Change Information
The following table shows the design change information of this group of BIM model.  

|Model Name|Category of Data change<sup>a</sup>|Level of Design Change|Description of Changes|
|:--|:--|:--|:--|
|M2|-|-|The origin model|
|M2_All-A|Added in P, A and R|Instance|Add 2 windows and 1 beam on 3F (the 3rd floor)|
|M2_All-D|Deleted in P, A and R|Instance|Delete 1 beam on 3F; delete 2 windows on 1F& 2F, respectively|
|M2_All-DA(M)|Deleted and then added in P, A and R|Model|Delete 3 windows and recreate them|
|M2_A-MG|Geometry modified in A|Instance|Modify the height of 5 columns|
|M2_A-MG(T)|Geometry modified in A|Type|Modify the section of family of a beam from 300×600 to 300×650|
|M2_A-ML|Location modified in A|Instance|Modify the location of 2 windows and 1 sofa|
|M2_A-ML(M)|Location modified in A|Model| Exchange the location of 2 pairs of windows and 1 pair of column foundation|
|M2_P-MV|Value modified in P|Instance|Modify a parameter (COMMENTS) in a beam|
|M2_R-MI(M)|Instance modified in R|Model|Modify the elevation of a level (Level4) from 9.3 to 9.5|
|M2_R-MR|Relationship modified in R|Instance|Modify the top level of 2 columns|

<sup>a</sup> P, A, R means Property data, Appearance data, Relationship data respectively.   
  
  
The following figure shows the design change information of this group of BIM model.  

![image](https://github.com/Zhou-Yucheng/Design-Change-BIM-Models/blob/master/images/M2-Changes.png)
