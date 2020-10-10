# School_District_Analysis
   Analysis of School district data using Python

## Overview
After compiling the data for Py City Schools, it was discovered that the 9th grade scores in math and reading had been altered at Thomas High School.  While it is unknown the extent of the academic dishonesty, the Py City School Board has decided to proceed with the analysis without the 9th grade scores from Thomas High School.  After replacing all 9th grade math and reading scores at Thomas High School with NaN, the following results were tallied.

- District Summary
- School Summary
- Math Scores by Grade
- Reading Scores by Grade
- Scores by School Spending
- Scores by School Size
- Scores by School Type

## Results
As a result of the changes to the Thomas High School 9th grade math and reading scores, the seven school district metrics were effected as follows:
- District Summary (Ref:  Districk Summary Charts)
   - Average math scores for the district dropped by 1/10th of a point from 79.0 to 78.9.
   - There was no significant change for average reading scores in the district.
   - Percentage of students with passing math scores dropped by 2/10th of a point from 75% to 74.8%.
   - Percentage of students with passing reading scores dropped by 3/10th of a point from 86% to 85.7%.
   - Overall Percentage of students who passed both math and reading dropped by 1/10th of a point from 65% to 64.9%.
- School Summary (Ref: School Summary Charts)
   - Average math scores for the Thomas High School dropped by 6/100th of a point from 83.41 to 83.35.
   - Average reading scores for Thomas High School improved by 8/100th of a point from 83.84 to 83.89.
   - Percentage of students with passing math scores dropped 26% from 93.27% to 66.91%.
   - Percentage of students with passing reading scores dropped 27% from from 97.3% to 69.66%.
   - Overall Percentage of students who passed both math and reading dropped 25% from 90.94% to 65.07%.
- Math Scores by Grade (Ref: Math Scores Charts)
   - All 9th grade scores have been nullified for Thomas High School.  Not comparison possible at this time.  All other school's scores were uneffected by this change.
- Reading Scores by Grade (Ref:  Reading Scores Charts)
   - All 9th grade scores have been nullified for Thomas High School.  Not comparison possible at this time.  All other school's scores were uneffected by this change.
- Scores by School Spending (Ref:  School Spending Charts)
   - Only scores effected by the changes were for schools spending between $630 to $644 per student.
   - Percentage of students with passing math scores dropped .06% from 73% to 67%.
   - Percentage of students with passing reading scores dropped .07% from from 84% to 77%.
   - Overall Percentage of students who passed both math and reading dropped .05% from 63% to 58%.
- Scores by School Size (Ref: School Size Charts)
   - Only scores effected by the changes were for schools with 1000 to 2000 students.
   - Percentage of students with passing math scores dropped .06% from 94% to 88%.
   - Percentage of students with passing reading scores dropped .06% from from 97% to 91%.
   - Overall Percentage of students who passed both math and reading dropped .06% from 91% to 85%.
- Scores by School Type (Ref: School Type Charts)
   - Only scores effected by the changes were charter schools.
   - Percentage of students with passing math scores dropped .04% from 94% to 90%.
   - Percentage of students with passing reading scores dropped .04% from from 97% to 93%.
   - Overall Percentage of students who passed both math and reading dropped .03% from 90% to 87%.
- Top 5 Performing Schools (Ref: Top 5 Performing Schools)
    - After removing the 9th grade math and reading scores, Thomas High School dropped from the second best performing school to out of the top 5.  Wright High School moved into 
    top 5.

#### District Summary Charts
##### District Summary Pre Thomas
![district_summary_pre_thomas](https://github.com/stephenanayashilliard/School_District_Analysis/blob/main/Resources/district_summary_pre_thomas.png)
##### District Summary Post Thomas
![district_summary_Post_thomas](https://github.com/stephenanayashilliard/School_District_Analysis/blob/main/Resources/district_summary_post_thomas.png)

#### School Summary Charts
##### School Summary Pre Thomas
![school_summary_pre_thomas](https://github.com/stephenanayashilliard/School_District_Analysis/blob/main/Resources/school_summary_pre_thomas.png)
##### School Summary Post Thomas
![school_summary_post_thomas](https://github.com/stephenanayashilliard/School_District_Analysis/blob/main/Resources/school_summary_post_thomas.png)

#### Scores by Grade Charts
##### Math Scores by Grade
###### Math Scores Pre Thomas
![math_grade_pre_thomas](https://github.com/stephenanayashilliard/School_District_Analysis/blob/main/Resources/math_by_grade_pre_thomas.png)
###### Math Scores Post Thomas
![math_grade_post_thomas](https://github.com/stephenanayashilliard/School_District_Analysis/blob/main/Resources/math_by_grade_post_thomas.png)
##### Reading Scores by Grade
###### Reading Scores Pre Thomas
![reading_by_grade_pre_thomas](https://github.com/stephenanayashilliard/School_District_Analysis/blob/main/Resources/reading_by_grade_pre_thomas.png)
###### Reading Scores Post Thomas
![reading_by_grade_post_thomas](https://github.com/stephenanayashilliard/School_District_Analysis/blob/main/Resources/reading_by_grade_post_thomas.png)

#### Scores by School Spending Charts
##### Scores pre Thomas
![scores_by_school_spending_pre_thomas](https://github.com/stephenanayashilliard/School_District_Analysis/blob/main/Resources/scores_by_school_spending_pre_thomas.png)
##### Scores post Thomas
![scores_by_school_spending_post_thomas](https://github.com/stephenanayashilliard/School_District_Analysis/blob/main/Resources/scores_by_school_spending_post_thomas.png)

#### Scores by School Size Charts
##### Scores pre Thomas
![scores_by_school_size_pre_thomas](https://github.com/stephenanayashilliard/School_District_Analysis/blob/main/Resources/scores_by_school_size_pre_thomas.png)
##### Scores post Thomas
![scores_by_school_size_post_thomas](https://github.com/stephenanayashilliard/School_District_Analysis/blob/main/Resources/scores_by_school_size_post_thomas.png)

#### Scores by School Type Charts
##### Scores pre Thomas
![scores_by_school_type_pre_thomas](https://github.com/stephenanayashilliard/School_District_Analysis/blob/main/Resources/scores_by_school_type_pre_Thomas.png)
##### Scores post Thomas
![scores_by_school_type_post_thomas](https://github.com/stephenanayashilliard/School_District_Analysis/blob/main/Resources/scores_by_school_type_post_Thomas.png)

#### Top 5 Schools by Performance
##### Top 5 Schools Pre Thomas
![top_5_schools_pre_thomas](https://github.com/stephenanayashilliard/School_District_Analysis/blob/main/Resources/top_5_schools_pre_thomas.png)
##### Top 5 Schools Post Thomas
![top_5_schools_post_thomas](https://github.com/stephenanayashilliard/School_District_Analysis/blob/main/Resources/top_5_schools_post_thomas.png)

## Summary
In summary, although there were multiple areas that were effected by removing the math and reading scores for Thomas High School.  There were 5 areas that showed drastic changes. 
- Thomas High School's performance rankings dropped.
- Thomas High School's percentage mean scores dropped 25.33%.
- The mean scores for schools spending between $630 and $644 dropped .06%.
- The mean scores for schools with a student population between 1000 to 2000 students dropped .06%.
- The mean scores for charter schools dropped .03%
In order that decisions are being made about fund allocations based on the proper data and that schools scores effected by the removal of the 9th grade math and reading scores for Thomas High School and compared equally.   It could be advantages to run the 7 results with the Thomas High School data removed.  This would require the overall student population  to relect the subtraction of the Thomas High School student population.  The same reports could also be run, just comparing the scores of 10th to 12th graders who scores were uneffected by the changes to Thomas High School's data.
