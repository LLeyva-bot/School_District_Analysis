# Module_Four_Challenge_School_District_Analysis

## Project Overview
The school board requested all standardized test data be prepared for analysis, reporting, and presentation to provide insights about performance trends and patterns. After completing the intial analysis, the school board found evidence of academic dishonesty; specifically, reading and math grades for Thomas High School ninth graders appear to have been altered. Although the school board does not know the full extent of the academic dishonesty, they want to uphold state-testing standards and requested to replace the math and reading scores for Thomas High School ninth graders with NaNs while keeping the rest of the data intact.

1. Replace the math and reading scores for Thomas High School with NaNs.
2. Recreate tables presenting the following metrics:
  - District Summary
  - School Summary
  - Top 5 and bottom 5 performing schools, based on the overall passing rate.
  - The average math score received by students in each grade level at each school.
  - The average reading score received by students in each grade level at each school.
  - School performance based on the budget per student.
  - School performance based on the school size. 
  - School performance based on the type of school.
3. Describe how these changes affected the overall analysis.

## Resources
- Data Source: schools_complete.csv, students_complete.csv
- Software: Python, Jupyter Notebook, Pandas, Numpy
- 
## Results
- District Summary:
  - The "Average Math Score" decreased by 0.1 when the math scores for Thomas High School ninth graders were replaced with NaNs.
  - The "% Passing Math" decreased by 0.2% when the math scores for Thomas High School ninth graders were replaced with NaNs.
  - The "% Passing Reading" decreased by 0.1% when the reading scores for Thomas High School ninth grader were replaced with NaNs.
  - The "% Overall Passing" decreased by 0.3% when the math and reading scores for Thomas High School ninth graders were replaced with NaNs.
![District_Summary](https://github.com/LLeyva-bot/School_District_Analysis/blob/main/Resources/District_Summary.PNG)

- School Summary:
  - The "Average Math Score", for Thomas High School, decreased by 0.067412 when the math scores for Thomas High School ninth graders were replaced with NaNs.
  - The "Average Reading Score", for Thomas High School, increased by 0.04715 when the reading scores for Thomas High School ninth graders were replaced with NaNs.
  - The "% Passing Math", for Thomas High School, decreased by 0.08648% when the math scores for Thomas High School ninth graders were replaced with NaNs.
  - The "% Passing Reading", for Thomas High School, decreased by 0.29013% when the reading scores for Thomas High School ninth graders were replaced with NaNs.
  - The "% Overall Passing", for Thomas High School, decreased by 0.31769% when the math and reading scores for Thomas High School ninth graders were replaced with NaNs.
![School_Summary](https://github.com/LLeyva-bot/School_District_Analysis/blob/main/Resources/School_Summary.PNG)

- Top 5 performing schools, based on the overall passing rate:
  - Thomas High School remained the second top performing school when the math and reading scores for Thomas High School ninth graders were replaced with NaNs.
![High_Performing](https://github.com/LLeyva-bot/School_District_Analysis/blob/main/Resources/High_Performing.PNG)

- Bottom 5 performing schools, based on the overall passing rate:
  - The bottom 5 performing schools remained the same when the math and reading scores for Thomas High School ninth graders were replaced with NaNs.
![Low_Performing](https://github.com/LLeyva-bot/School_District_Analysis/blob/main/Resources/Low_Performing.PNG)

- The average math score received by students in each grade level at each school:
    - All average math scores, except for Thomas High School ninth graders, remained the same.
![Math_Scores](https://github.com/LLeyva-bot/School_District_Analysis/blob/main/Resources/Math_Scores.PNG)

- The average reading score received by students in each grade level at each school:
    - All average reading scores, except for Thomas High School ninth graders, remained the same.
![Reading_Scores](https://github.com/LLeyva-bot/School_District_Analysis/blob/main/Resources/Reading_Scores.PNG)

- School performance based on the budget per student:
  - School performance based on the budget per student remained the same when the math and reading scores for Thomas High School ninth graders were replaced with NaNs.
![School_Spending](https://github.com/LLeyva-bot/School_District_Analysis/blob/main/Resources/School_Spending.PNG)

- School performance based on the school size:
  - School performance based on the school size remained the same when the math and reading scores for Thomas High School ninth graders were replaced with NaNs.
![School_Size](https://github.com/LLeyva-bot/School_District_Analysis/blob/main/Resources/School_Size.PNG)

- School performance based on the type of school:
  - School performance based on the type of shcool remained the same when the math and reading scores for Thomas High School ninth graders were replaced with NaNs.
![School_Type](https://github.com/LLeyva-bot/School_District_Analysis/blob/main/Resources/School_Type.PNG)

## Summary

Excluding the Thomas High School ninth graders math and reading scores made a very small negative impact on the overall analysis of the test data. The "Average Math Score" for Thomas High School decreased by 0.67412 while the "Average Reading Score" increased by 0.04715.  This change caused the "Average Math Score" for the District to decrease by 0.2 and the "Average Reading Score" for the District to remain the same. The overall percentage of Thomas High School students passing math and reading decreased by .31769% but the change was so small that it did not ipmact the rank of Thomas High School within the district.  Thomas High School remains the second top performing school in the district.  The percentage of students passing math and reading in the district decreased and the combined overall decrease was 0.3%.  Again, the negative change was so small it did not impact the school performance based on budget per student, school size, and type of school. 
