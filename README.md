# Design-Change-BIM-Models
These exemplary BIM models can be used as test cases, for further development and validation of relevant methods and tools.

The detailed information of exemplary BIM models in folder M1 is shown in the Table below.

|Model Name|Category of Data change<sup>a</sup>|Level of Design Change|Description of Changes|Meaningful<sup>b</sup>|
|:--|:--|:--|:--|:--|
|M1|-|-|The origin model|O|
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
