# School_District_Analysis
Module 4 Panda Practice and Challenge
# Overview of the school district analysis
This analysis is to help Maria, the chief data scientist for a city school district, to prepare the analysis report of school performance based on student funding and students' standardized test scores of math and reading.

Due to the evidence of academic dishonesty, Maria needs to re-analyze the data by replacing the math and reading scores of ninth-grade student from Thomas High School with NaNs, to see how the results would be changed.

  - Purpose: Remove the false data and keep the analysis correct. This analysis report is to show the trends of school performance based on funding, grade, school size, and type to assist the school board and superintendent in making decisions regarding the school budgets and priorities.
# Results
  - Changes on the *District Summary*
     - The **Average Math Score**, **%Passing Math**, **%Passing Reading**, and **%Overall Passing** drops slightly as follows:
     
     ![The district summary-before edition](https://github.com/xueying-lin/School_District_Analysis/blob/5625ddaa3dc0ee51752501dba8d24d17994d4313/Resources/The%20district%20summary-original.PNG)
     
     ![The district summary-after edition](https://github.com/xueying-lin/School_District_Analysis/blob/5625ddaa3dc0ee51752501dba8d24d17994d4313/Resources/The%20district%20summary-updated.PNG)
     
  - Changes on the *School summary*
      - The **Average Math Score**, **%Passing Math**, **%Passing Reading**, **%Overall Passing** drops slightly, but the **Average Reading Score** arise slightly as follows:
      
      ![The School Summary-before edition](https://github.com/xueying-lin/School_District_Analysis/blob/09f1d7bb9a86720c12ea8194d7e65a26ff340a41/Resources/The%20school%20summary-original.PNG)
      
      ![The School Summary-after edition](https://github.com/xueying-lin/School_District_Analysis/blob/09f1d7bb9a86720c12ea8194d7e65a26ff340a41/Resources/The%20school%20summary-updated.jpg)
      
  - After removing the ninth-grade scores, the performance of Thomas High School **did not change relative to the other schools.** Because the rank of Thomas High School remains after the replacement:
  
     ![The top five school-original](https://github.com/xueying-lin/School_District_Analysis/blob/3d698a1c25e083256660e8cc1c57a61e592277ce/Resources/top%20five-original.PNG)
     
     ![The top five school-updated](https://github.com/xueying-lin/School_District_Analysis/blob/3d698a1c25e083256660e8cc1c57a61e592277ce/Resources/top%20five-updated.PNG)
     
 - Replacing the ninth-grade scores lead to:
     - The **average reading and math scores for ninth-grade** in Thomas High school becomes **NaN** as the pictures show:
     
      ![The math score by grade-before](https://github.com/xueying-lin/School_District_Analysis/blob/7bac4d368dbd87b8c524fa538c4d4b62b595162d/Resources/math_by_grade_original.jpg)
      
      ![The math score by grade-after](https://github.com/xueying-lin/School_District_Analysis/blob/7bac4d368dbd87b8c524fa538c4d4b62b595162d/Resources/math_by_grade_updated.jpg)
      
      ![The reading score by grade-before](https://github.com/xueying-lin/School_District_Analysis/blob/7bac4d368dbd87b8c524fa538c4d4b62b595162d/Resources/reading_by_grade_original.jpg)
      
      ![The reading score by grade-after](https://github.com/xueying-lin/School_District_Analysis/blob/7bac4d368dbd87b8c524fa538c4d4b62b595162d/Resources/reading_by_grade_updated.jpg)

     - Nothing changes on scores by school spending, school size, and school type.
      
      ![Scores by school spending-before](https://github.com/xueying-lin/School_District_Analysis/blob/7bac4d368dbd87b8c524fa538c4d4b62b595162d/Resources/spending%20ranges-before.PNG)
      
      ![Scores by school spending-after](https://github.com/xueying-lin/School_District_Analysis/blob/7bac4d368dbd87b8c524fa538c4d4b62b595162d/Resources/spending%20ranges-after.PNG)
      
      ![Scores by school size-before](https://github.com/xueying-lin/School_District_Analysis/blob/7bac4d368dbd87b8c524fa538c4d4b62b595162d/Resources/school_size_before.PNG)
      
      ![Scores by school size-after](https://github.com/xueying-lin/School_District_Analysis/blob/7bac4d368dbd87b8c524fa538c4d4b62b595162d/Resources/school_size_after.PNG)
      
      ![Scores by school type-before](https://github.com/xueying-lin/School_District_Analysis/blob/7bac4d368dbd87b8c524fa538c4d4b62b595162d/Resources/school_type_before.PNG)
      
      ![Scores by school type-after](https://github.com/xueying-lin/School_District_Analysis/blob/7bac4d368dbd87b8c524fa538c4d4b62b595162d/Resources/school_type_after.PNG)
      
# Summary
 Four changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.
1. The **Average Math Score**, **%Passing Math**, **%Passing Reading**, and **%Overall Passing** of the *District Summary* drops slightly, so the performance of district drops.
2. The **Average Math Score**, **%Passing Math**, **%Passing Reading**, **%Overall Passing** of the Thomas High School drops slightly.
3. The **Average Reading Score** of Thomas High School arise slightly.
4. The **Average reading and math scores** for ninth-grade in Thomas High school becomes **NaN**
