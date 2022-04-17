# School_District_Analysis

## Overview of the school district analysis
The purpose of this analysis was to determine if there was any falsified testing data within a school district.  The analysis focussed on math and reading testing scores to determine if there were any schools "cheating" on their testing numbers.  Specifically, the school board wanted to see how the overall analysis differed when one school, Thomas High School, was removed from the data to be analyzed.

## Results
### How is the district summary affected?
  -The orignial district summary analysis produced a slightly higher passing percentage in math, reading, and overall than the adjusted analysis.  By removing the 9th grade scores from Thomas High School in the adjusted analysis, the passing percentaged dropped but not by a statistically meaningful amount.  This is primarily due to the small percentage of the overall student population that was removed (only 461 out of 39170 students).
  
   -Original Analysis:
![This is an image](https://github.com/JDBrowder523/School_District_Analysis/blob/main/Resources/district_summary1.png)

   -Adjusted Analysis:
![This is an image](https://github.com/JDBrowder523/School_District_Analysis/blob/main/Resources/district_summary2.png)


### How is the school summary affected?
  -The original school summary analysis showed Thomas High School with an overall passing percentage of almost 91%.  When the 9th grade scores were removed form the data, Thomas High School dropped to an overall passing percentage of 65%.
  
  -Original Analysis:
  ![This is an image](https://github.com/JDBrowder523/School_District_Analysis/blob/main/Resources/school_summary1.png)
  
  -Adjusted Analysis:
  ![This is an image](https://github.com/JDBrowder523/School_District_Analysis/blob/main/Resources/school_summary2.png)

### How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?

  -As seen in the images above, Thomas High school was second in the district in overall passing percentage in the original analysis but dropped down to eighth in the district after the 9th grade scores were removed from the data.
  
### How does replacing the ninth-grade scores affect the following:

#### Math and reading scores by grade

  -By replacing the 9th grade math and reading scores with NaN values, the scores for 10th, 11th, and 12th grade do not change from the original data.
  
  -Math Scores by Grade Level:
  ![This is an image](https://github.com/JDBrowder523/School_District_Analysis/blob/main/Resources/Adjusted_math2.png)
  
   
   -Reading Scores by Grade Level:
  ![This is an image](https://github.com/JDBrowder523/School_District_Analysis/blob/main/Resources/adjusted_reading2.png)
  
#### Scores by school spending

  -Replacing the 9th grade math and reading scores with NaN values resulted in lower scores for Thomas High School, which is in the per capita student range of $586-$630.  This lowered the overall passing percentage for schools in this spending range from 63% to 56%.
  
   -Original Analysis:
  ![This is an image](https://github.com/JDBrowder523/School_District_Analysis/blob/main/Resources/scores_by_spending1.png)
  
   -Adjusted Analysis:
  ![This is an image](https://github.com/JDBrowder523/School_District_Analysis/blob/main/Resources/scores_by_spending2.png)
  
#### Scores by school size

  -Replacing the 9th grade math and reading scores resulted in a negligible change in school scores based on size.  When rounded to the nearest whole number, the numbers for the two analysis are the same.
  
   -Original Analysis:
  ![This is an image](https://github.com/JDBrowder523/School_District_Analysis/blob/main/Resources/scores_by_size1.png)
  
   -Adjusted Analysis:
  ![This is an image](https://github.com/JDBrowder523/School_District_Analysis/blob/main/Resources/scores_by_size2.png)
  
#### Scores by school type

  -Replacing the 9th grade math and reading scores resulted in a negligible change in school scores based on school type.  When rounded to the nearest whole number, the numbers for the two analysis are the same.
  
   -Original Analysis:
  ![This is an image](https://github.com/JDBrowder523/School_District_Analysis/blob/main/Resources/scores_by_type1.png)
  
   -Adjusted Analysis:
  ![This is an image](https://github.com/JDBrowder523/School_District_Analysis/blob/main/Resources/scores_by_type2.png)
  
  ## Summary
    Based on the removal of 9th grade math and reading score date from Thomas High School:
    1. Thomas High School's overall average passing percentage dropped from almost 91% to 65%.
    2. Thomas High School dropped from 2nd highest in the district to 8th in the district.
    3. The overall score for schools in the $586 to $630 per capita student range deopped by 7%.
    4. The math and reading scores based on grade level now shows "nan" for 9th graders at Thomas High School.
