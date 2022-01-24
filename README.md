# School_District_Analysis

## Overview of the school district analysis
Maria has asked us to assist in helping to analyze standardize test results. We are to analyze, report and present the data to the school board. We will then look at trends of the data so that the board can better budget for the schools in the coming year. We are to analyze the data broken down by the following breakdowns
1. By District
2. By individual school
3. If removing the Thomas High 9th graders affects this school's relative performance to the rest of the schools
4. How does replacing the ninth graders scores affect
    A. Math and reading scores by grade
    B. Scores by school spending
    C. Scores by school size
    D. Scores by school type

## Resources
- Data Sources: clean_students_complete.csv, schools_complete.csv
- Software: Jupyter Notebook

## Results
### District Summary
When looking at the school type field, there were two options: district and charter. Thomas High School (THS) is a district school, so we are looking to see if removing the 9th graders from THS affected the scores.  There were 461 students in the 9th grade at Thomas High School. In all the district schools there is a total of 26,976 students. So the THS 9th graders account for only 1.7% of all students. So we would not expect a great change in the district school stats. In fact when comparing the two sets of stats, they are identical. So to verify that the data in the challenge is correct, I looked at the individual stats for THS. That is the next section

### School Summary
When looking at Thomas High School (THS) we would expect to see changes when we remove the 9th graders. The 9th grade (461 students) accounted for 28.2% if the overall school population (1635 students). When looking at the component, we see the scores only drop 0.07 when removing the 9th graders (from 83.42 to 83.35). This is also reflected in the percentage of student passing math. It drops from 93.27% to 93.19%. Overall maintaining the good math passing percentage. The average reading score goes up when removing the 9th graders, going from 83.85 to 83.90. The percent passing reading does drop when removing 9th graders, going from 97.31% to 97.02%. Overall passing drops as expected since math and reading passing percentages both dropped. It goes from 90.95% to 90.63%.

### How does removing the Thomas High School 9th graders affect their overall racking when compared to other schools.  
When looking at the overall passing percentages, removing the 9th graders from THS does not make a difference in their overall ranking. They maintain their 2nd rank behind Cabrera High School. Ranking based on percentage of students passing math is not effected either. Thomas High School is the 7th ranked school with or without the 9th graders included. Their reading rank is greatly affected by replacing the 9th graders. They went from being the top school in percentage of students passing reading and dropped to 3rd rank. 

### How does replacing the ninth-grade scores affect
#### Math and reading scores by grade
Obviously, dropping the Thomas High School 9th graders would not have any impact on the 10th - 12th grade scores. When looking at all ninth graders, they had an average math score of 78.94. When the Thomas high School 9th graders are removed the score drops to 78.74. The reading scores follows a similiar trend dropping from 81.91 with all schools to 81.84 when removing Thomas High School. 

#### Scores by school spending
Thomas High School fell in the $630-644 bucket with regards to spending per student, so we will focus on the spending range. The THS 9th graders account for 461 out of 11,322 students in the spending range or 4.1%. When looking at the reading and math scores, they are nearly identical.  The math scores dropped .02 and the reading scores increased .02 when not counting the THS 9th graders. The percentage of students passing math, reading and overall all dropped slightly when removing the THS 9th graders. Math went from 73.48 to 73.46, reading went from 84.39 to 84.32 and overall went from 62.86 to 62.78. 

#### Scores by school size
Thomas High School falls in the medium school category with 1,635 total students. Math and reading scores remained nearly identical after removing the THS 9th graders. The math scores dropped .01 and the reading scores went up .01. The percent of students passing math, reading and overall were fairly consistent as well. The percent passing math went from 93.36% to 93.58%, reading went from 96.79% to 96.73% and overall it went from 90.62% to 90.56%.

#### Scores by school type
When looking at the school type field, there were two options: district and charter. Thomas High School (THS) is a district school, so we are looking to see if removing the 9th graders from THS affected the scores.  There were 461 students in the 9th grade at Thomas High School. In all the district schools there is a total of 26,976 students. So the THS 9th graders account for only 1.7% of all students. So we would not expect a great change in the district school stats. In fact when comparing the two sets of stats, they are identical. So to verify that the data in the challenge is correct, I looked at the individual stats for THS. That is the next section

### Overall Summary
This project was to look at the impact (if any) of removing the Thomas High School 9th graders from the scoring of standardized test scores. When looking at the math and reading scores across numerous different breakdowns, there appears to be no significant change in the scores when removing the THS 9th graders. When looking at the percentages of students passing math, reading and overall there was no significant differences in scores when removing the THS 9th graders. 
