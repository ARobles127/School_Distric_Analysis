# School_Distric_Analysis
Jupyter and Pandas applications 
## Overview of the school district analysis: 
The school board  has requested Maria and her team to conduct another analysis on the most recent report that evaluated the district’s high schools performance. They have found evidence of academic dishonesty on standardized test scores from Thomas High School 9th graders and have decided to uphold state-testing scores. The purpose of this analysis is to make the appropriate corrections and showcase trends in school performance that help the school board and superintendents make decisions regarding school budget and priorities.  													In order to complete this task we will modify our analysis by replacing the math and reading scores for Thomas High School with NaNs while keeping the rest of the data, 10th to 12th grades. After replacing the data our objective will be to repeat the school district analysis and identify the ways that this incident affected the district and school performance. 

## Results: 											
The following questions will help us to generate insights that will allow  the school board to implement the necessary changes. There were a total of 461 students removed from Thomas High School 9th grade. 

### How is the district summary affected?						
After removing 9th graders from the original analysis we found that the changes were not significant enough to impact the district summary results. The following two tables show the minimal differences that could be round to the next whole number and the results will be the same. 									

-- Original District Summary DataFrame						
![Original_District_Summary](https://github.com/ARobles127/School_Distric_Analysis/blob/main/Original_District_Summary.png)			

-- Updated District Summary DataFrame						
![Updated_District_Summary](https://github.com/ARobles127/School_Distric_Analysis/blob/main/Updated_District_Summary.png)							

### How is the school summary affected?						
After removing 9th graders from the original report we found that the school position among the rest of schools did not change, however the overall passing for both subjects, math and reading had a significant change from 93.18% to 66.91% and 97.01% to 69.66% respectively.								

-- Original School Summary 
![Original_School_Summary](https://github.com/ARobles127/School_Distric_Analysis/blob/main/Original_School_Summary.png)								

-- Updated School Summary 
![UpdatedSchool_Summary](https://github.com/ARobles127/School_Distric_Analysis/blob/main/Updated_School_Summary.png)		

### How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
Removing one grade affects Thomas High School in math, reading and overall passing  percentages. In consequence that might affect their school funding. 

### How does replacing the ninth-grade scores affect the following:

- Math and reading scores by grade
The next two tables show updates on the new report where Thomas High School 9th grade is replaced by a non assign value. 

-- Updated Math Scores 									
![Updated_Math_Scores](https://github.com/ARobles127/School_Distric_Analysis/blob/main/Updated_Math_Scores.png)

-- Updated Reading Scores 
![Updated_Reading_Scores](https://github.com/ARobles127/School_Distric_Analysis/blob/main/Updated_Reading_Score.png)

- Scores by school spending									
Thomas High School spending range per student is categorized at $631-$645. After modifying the data the school  is still in the category. 

-- Scores by School Spending  
![Updated_Spending_Summary](https://github.com/ARobles127/School_Distric_Analysis/blob/main/Updated_Spending_Summary.png)

- Scores by school size										
Thomas High School is categorized as a medium school size with a total of 1635 students, of which 461 are 9th graders.  

-- Scores by School Size 
![Updated_Size_Summary](https://github.com/ARobles127/School_Distric_Analysis/blob/main/Updated_Size_Summary.png)

- Scores by school type										
Thomas High School is classified as a charter school type.

-- Scores by  School Type 
![Updated_Type_Summary](https://github.com/ARobles127/School_Distric_Analysis/blob/main/Updated_Type_Summary.png)

## Summary: Summarize four changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.
1. The updated math and reading score tables will show a “nan” replacing the 9th grades. This is the appropriate way to replace a grade since adding a zero would affect the results.
2. This high school had a high percentage on the overall passing, after the modifications that number was reduced to 65%.
3. There are slight changes in the district summary not greater than 1% on each metric.
4. The school is still ranked in the same position, number 13th out of 15 schools. 




