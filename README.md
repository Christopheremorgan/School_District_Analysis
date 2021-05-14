# School_District_Analysis

## Overview
The Chief Data Scientist for the local school district has requested help preparing insights from test data to inform decisions at the district level including funding and strategic priorities.  The raw school and student data was provided in csv format and the summary analysis created with Python and Pandas package protects the anonymity of student identity.  This is an update of the original analysis due to concern of academic dishonesty at one of the high schools.  The scores for the 9th grade at Thomas High School have been removed from the original analysis.

## Results
In all the screenshots below, the original analysis is shown first, followed by the revised analysis with the Thomas High School 9th graders removed from the analysis.

### District Analysis
There was a slight impact to passing rates with biggest impact to overall passing rate dropping by 3/10ths of a percent.
![image_name](https://github.com/Christopheremorgan/School_District_Analysis/blob/main/Resources/DistrictSummaryOriginal.png)
![image_name](https://github.com/Christopheremorgan/School_District_Analysis/blob/main/Resources/DistrictSummaryThomasRevised.png)

### School Summary
After removing Thomas 9th grade scores, all passing rates for Thomas were lower as well as the math scores.  However, the reading scores were actually higher after dropping the 9th graders data.
![image_name](https://github.com/Christopheremorgan/School_District_Analysis/blob/main/Resources/HighSchoolSummaryOriginal.png)![image_name](https://github.com/Christopheremorgan/School_District_Analysis/blob/main/Resources/HighSchoolSummaryThomasRevised.png)

### Top School Rankings 
Although overall passing ratings were lower, it did not impact Thomas High School's ranking as the school with the 2nd best overall passing rate in the district.
![image_name](https://github.com/Christopheremorgan/School_District_Analysis/blob/main/Resources/TopSchoolsOriginal.png)![image_name](https://github.com/Christopheremorgan/School_District_Analysis/blob/main/Resources/TopSchoolsThomasEdits.png)

### Math & Reading Score Impacts
All scores for every school and every grade stay the same with the only exception of Thomas High School 9th graders where their dropped scores show up as 'nan'.

MATH SCORES
![image_name](https://github.com/Christopheremorgan/School_District_Analysis/blob/main/Resources/MathScoresByGradeOriginal.png)![image_name](https://github.com/Christopheremorgan/School_District_Analysis/blob/main/Resources/MathScoresByGradeThomasEdit.png)

READING SCORES
![image_name](https://github.com/Christopheremorgan/School_District_Analysis/blob/main/Resources/ReadingScoresByGradeOriginal.png)![image_name](https://github.com/Christopheremorgan/School_District_Analysis/blob/main/Resources/ReadingScoresByGradeThomasEdit.png)

### School Spending Summary
Schools with the highest scores had the lowest funding per student, while schools with the lowest scores had the highest funding per student.  Dropping Thomas 9th grade scores did not impact this summary analysis.
![image_name](https://github.com/Christopheremorgan/School_District_Analysis/blob/main/Resources/SpendSummaryOriginal.png)![image_name](https://github.com/Christopheremorgan/School_District_Analysis/blob/main/Resources/SpendSummaryThomasEdit.png)

### School Size Summary
Small and medium size schools score much higher than larger schools.  Dropping Thomas 9th grade scores did not impact this summary analysis.
![image_name](https://github.com/Christopheremorgan/School_District_Analysis/blob/main/Resources/SchoolSizeSummaryOriginal.png)![image_name](https://github.com/Christopheremorgan/School_District_Analysis/blob/main/Resources/SchoolSizeSummaryThomasEdit.png)

### School Type Summary
Charter schools score significantly higher than district schools.   Dropping Thomas 9th grade scores did not impact this summary analysis.
![image_name](https://github.com/Christopheremorgan/School_District_Analysis/blob/main/Resources/SchoolTypeSummaryOriginal.png)![image_name](https://github.com/Christopheremorgan/School_District_Analysis/blob/main/Resources/SchoolTypeSummaryThomasEdit.png)

## Summary
Removing Thomas High School 9th graders had a slight impact on math scores, reading scores, as well as math, reading and overall passing rates.  However, much of the analysis did not change.  Thomas still has the 2nd highest overall passing rate in the district and the summary analysis also did not change.  Thomas 9th grade scores end up being only a rounding error in the summary statistics. 

[Click here](https://github.com/Christopheremorgan/School_District_Analysis/blob/main/PyCitySchools_Challenge.ipynb)to view the code for the updated and original analysis.
