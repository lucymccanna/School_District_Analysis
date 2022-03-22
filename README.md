# School_District_Analysis
Module 4 - Python
## Overview
The purpose of this analysis is to repeat the school district analysis after replacing the math and reading scores for all ninth graders at Thomas High School with NaN values due to suspected academic dishonesty. After the scores are updated, the school district analysis will be repeated to analyze and showcase trends in school performance based on school funding and student standardized test scores. 

## Results

**District Summary Results**
When the new district analysis that contains NaN values for all ninth grader scores at Thomas High School is compared to the original district analysis, there is no affect on the average and passing percentage numbers. When rounded to the same digits, there are no discrepancies identified between the two analyses. 


**School Summary Results**
Looking at the new school summary for Thomas High School, it is noted that the average math and reading scores remained the same, however the percentages of students passing both math and reading are significantly different. In the original analysis, the percentages of students passing math and reading were 93% and 97%, respectively. After replacing the ninth grader scores with NaN, the passing percentages dropped to 67% for math and 70% for reading. 

Replacing the ninth graders' scores drops the overall passing percentage of Thomas High School from 91% to 65%. The high school drops from the second highest overall passing percentage to the ninth place overall.
    
    Original Thomas High School Summary:
![This is an image](https://github.com/lucymccanna/School_District_Analysis/blob/main/Resources/original_school_summary_ThomasHigh.png)
   
    New Thomas High School Summary: 
![This is an image](https://github.com/lucymccanna/School_District_Analysis/blob/main/Resources/new_school_summary_ThomasHigh.png)


   
**How does replacing the ninth-grade scores affect the following:**

- Math and reading scores by grade
When the math and reading scores are displayed by grade, "nan" appears in the math and reading dataframes for ninth graders at Thomas High School.
                
- Scores by school spending
                Thomas High School is in the $631-645 spending range. Updating the ninth grader scores had no affect on the overal averages and passing percentages.
                
- Scores by school size
                Thomas High School is in the medium school size range. Updating the ninth grader scores had no affect on the overal averages and passing percentages.
                
- Scores by school type
                Thomas High School is grouped with the Charter schools. Updating the ninth grader scores had no affect on the overal averages and passing percentages.
                
## Summary

Updating the Thomas High ninth graders' scores to NaN values significantly changed the overall high school's math and reading averages, dropping from 93% to 67% and 97% to 70%, for math and reading respectively. Additionally, the overall passing percentagesof students dropeed from 91% to 65%. Thomas High School dropped from second overall to ninth overall out of the 15 schools in the district. 
