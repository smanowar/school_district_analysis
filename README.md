# School District Analysis

## Overview 
The purpose of this analysis is to use Pandas to analyze a given data set to analyze the outcomes for standardized math and reading tests for grade nine to grade twelve students in a school district to provide insights about performance trends and pattern. 

In this analaysis the scores for ninth graders at Thomas High School have been ommitted due to evidence of academic dishonesty. We will be analyzing the effect of this ommission on the results of the prior analysis.

Using the data sets, schools_complete.csv and students_complete.csv, we will analyze:

- the effect of the omission on the district summary and the school summary,
- the effect of the omission on Thomas High School's relative performance to other schools, and
- the effect of replacing the ninth-grade scores on:

  - Math and Reading Scores by Grade
  - Scores by School Spending
  - Scores by School Size

## Results 
Rerunning the analysis we will see how the omission of the ninth-grade scores from Thomas High School affects the following:

#### District Summary
As seen in the figures below (old results on top, results omitting the ninth grade scores below):

<p align="center">
<img src=https://github.com/smanowar/school_district_analysis/blob/main/visuals/district_summary_old.PNG> 
</p>
<p align="center">
<img src=https://github.com/smanowar/school_district_analysis/blob/main/visuals/district_summary_new.PNG> 
</p>

There are no drastic change in the results, differences are as follows: 

- Average Math Score dropped 0.1% to 78.9%
- Percentage Passing Math dropped 0.2% to 74.8% 
- Percentage Passing Reading dropped 0.3% to 85.7%
- and Percentage Overall Passing dropped 0.1% to 64.9%

#### School Summary 
As seen in the figures below (old results on top, results omitting the ninth grade scores below):

<p align="center">
<img src=https://github.com/smanowar/school_district_analysis/blob/main/visuals/thomas_high_school_old.PNG> 
</p>
<p align="center">
<img src=https://github.com/smanowar/school_district_analysis/blob/main/visuals/thomas_high_school_new.PNG> 
</p>

There are no drastic change in the results, noteable differences are as follows:

- Average Math Score dropped 0.07 % to 83.35 %
- Average Reading Score increased 0.04 % to 83.89 %
- Percentage Passing Math dropped 0.09 % to 93.18 %
- Percentage Passing Reading dropped 0.29 % to 97.02 %
- Percentage Overall Passing dropped 0.32 % to 90.63 %

Omitting the ninth-grade data from Thomas High School has no effect on the top 5 schools:

<p align="center">
<img src=https://github.com/smanowar/school_district_analysis/blob/main/visuals/top_schools_new.PNG> 
</p>

Thomas High School still remains the 2nd highest performing school in the district.

There is no change in the bottom 5 schools.

#### Math and Reading Scores by Grade 

There is no change and math and reading scores by grade as the only thing changed is the omission of the ninth-grade data from Thomas High School.

#### Scores by School Spending 

Thomas High School averaged a budget of $638.00 per student, placing them in the < $584 Spending Range. However, because the effect of the omission of the ninth grade scores were so minimal on the overall results for the school it did not have any affect on the results based on school spending.

#### Scores by School Size 

Thomas High School has a student count of 1635 students, placing them in the Medium school size range. However, like above because the effect of the omission of the ninth grade scores were so minimal on the overall results for the school it did not have any affect on the results based on school size.

#### Scores by School Type 

Thomas High School is a Charter School. However, as stated previously the effect of the omission of the ninth grade scores were so minimal on the overall results for the school it did not have any affect on the results based on school type.

## Summary

After omitting the grade nine data for Thomas High School, we see a slight drop in the overall performance of the school. 

The overall reading score increased, however we saw a drop in Percentage Passing Math, Percentage Passing Reading, and Percentage Overall Passing.

However, because this change is relativley minimal it has no effect on the other metrics and Thomas High School still stands as the 2nd top performing school in the district.
