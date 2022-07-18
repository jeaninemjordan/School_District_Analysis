# School_District_Analysis

## A district-wide analyisis of academic performance in correlation with allotted spending, school size and school type on both individual and comprehensive proportions.

### Project Overview

This analysis is intended on reporting the academic performance versus the funding and budget metrics of the students at fifteen district and charter high schools.  During the analysis, it was discovered that the ninth-grade math and reading scores from Thomas High School were skewed due to potential academic dishonesty and needed to be removed from the overall assessment. To do this, the ninth-grade scores from Thomas High School were nullified with NaN (Not a Number) values during a second analysis and a comparison was conducted to understand the overall difference between omitting the grades from the analysis. 

### Results

## District Analysis Comparason

A comparason of the overall district analysis was conducted using the data from the original analysis including the math and reading scores from Thomas High School, as well as the data with these metrics removed. It is observed that the updated analysis was lowered by less than 0.5% in the updated analysis when the THS ninth grade math and reading grades are removed. The Thomas High School ninth grade class is comprised of only 461 students, making up only 1.2% of the entire student population included within the total analysis (39,170 total). Due to the small size of the THS ninth grade in comparason to the total student count, it is clear that the removal of the ninth grade math and reading scores from this school would not have a major effect on the overall analysis. Below are screenshots of the dataframes in both assessments.

#### Original Analysis Including Metrics from THS

INSERT PICTURE

#### Updated Analysis With THS Metrics Removed

INSERT PICTURE

## Top and Bottom School Comparasons

The lists of top and bottom ranked schools in the original and updated assessments were compared in this analysis. Thomas High School is listed in second place within the top five ranked schools in both results. The updated analysis shows that the metrics within Thomas High School are only affected by less than 1% on each metric measured and the rankings remain unchanged. Below are screenshots of the dataframes in both assessments.

#### Original Analysis - Top 5 Schools Within District Ranked

INSERT PICTURE

#### Updated Analysis - Top 5 Schools Within District Ranked

INSERT PICTURE

The list of bottom ranked schools within the district remains identical during both analyses. This is due to Thomas High School never being apart of these rankings to begin with, thus there is no changed data being compared or observed. Below are screenshots of the dataframes in both assessments.

#### Original Analysis - Bottom 5 Schools Within District Ranked

INSERT PICTURE

#### Updated Analysis - Bottom 5 Schools Within District Ranked

INSERT PICTURE

## Impact of Math and Reading Scores by Grade

Comparasons of the math and reading scores by grades were conducted using the original and updated analyses. The only noticable difference are the NaN (Not a Number) values in place of the ninth grade math and reading scores on the updated analysis. Below are screenshots of the dataframes in both assessments.

#### Original Analysis - Math Scores by Grade

INSERT PICTURE

#### Updated Analysis - Reading Scores by Grade

INSERT PICTURE

## Impact of Scores by School Spending

Comparasons of the spending ranges per student dataframes were conducted using both analyses. The $630-644 bucket is the only metric within these comparasons affected. When the ninth grade math and reading scores from Thomas High School are removed, we see a difference in the bucket title from $631-645 to $630-644. In each metric of the updated analysis, the scores are affected by less than 0.1%. The differences are so small that they are only able to be observed using the unrounded numbers without formatting. Below are screenshots of the dataframes in both assessments.  Interestingly, the lower the spending ranges per student are, the higher the scores are reported to be. 

#### Original Analysis - Spending Per Student

INSERT PICTURE

#### Updated Analysis - Spending Per Student

INSERT PICTURE

## Scores by School Size Comparason

Comparasons of the scores per school size were conducted using the original and updated analyses. Similar to the prior comparasons made, there is a slight difference in the updated analysis. The medium (1000-2000) size schools are the only group affected, with each metric dropping by less than 1%. Thomas High School is comprised of 1,635 students, which is only 4.1% of the total school population measured. Below are screenshots of the dataframes in both assessments. An overall correlation between higher average scores and smaller schools is visible here; however, passing percentages are highest in medium size schools. 

#### Original Analysis - Scores by School Size

INSERT PICTURE

#### Updated Analysis - Scores by School Size

INSERT PICTURE

## Impact of Scores by School Type

Comparasons of the scores by school type were conducted using the original and updated analyses. As Thomas High School is a charter school, its metrics are affected within the updated analysis by less than 0.1%. There are no changes to the district school metrics due to there being no changes made to any of the schools' metrics within this category. Below are screenshots of the dataframes in both assessments. Noticably higher scores in all categories for charter schools versus district schools are observed during this analysis. 

#### Original Analysis - Scores by School Type

INSERT PICTURE

#### Updated Analysis - Scores by School Type

INSERT PICTURE
