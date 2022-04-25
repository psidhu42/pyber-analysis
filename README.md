# Ride-sharing Data Analysis

## Overview of Project

Analyze ride-sharing data and determine how different factors affect the overall outcomes.

### Purpose

Analyze the ride-sharing data from "PyBer", based on city type determine the number of rides, number of drivers, and the average fare per ride and average fare per driver. Once that data is collected create a multiple-line graph that shows the total weekly fares for each city type. Report how the data is different by city type and how it can be used.

## Results of Analysis

The following results show how the data compares between city types.

### PyBer Summary DataFrame

![PyBer Summary DataFrame](https://github.com/psidhu42/school-district-analysis/blob/main/resources/district_summary.PNG)



### School Summary

The school summary only changed for Thomas High School as it was the only school that had the 9th grader scores removed.

* Thomas High School Summary Changes
    - Total Students: No Change
    - Total Budget: No Change
    - Per Student Budget: No Change
    - Average Math Score: Dropped from 83.41 to 83.35
    - Average Reading Score: Increased from 83.84 to 83.89
    - % Passing Math: Dropped by 0.1%
    - % Passing Reading: Dropped by 0.3%
    - % Overall Passing: Dropped by 0.3%

* With All Scores:

![School Summary](https://github.com/psidhu42/school-district-analysis/blob/main/resources/school_summary.PNG)

* Without 9th Grader Scores from THS:

![School Summary Without THS 9th Grader Scores](https://github.com/psidhu42/school-district-analysis/blob/main/resources/school_summary_altered.PNG)

### Scores by Grade

Looking at the DataFrame for Scores by Grade, you can see removing the 9th grader scores from THS only changed those cells to "nan" on both math and reading scores.

* Math Scores by Grade

![Math Scores by Grade](https://github.com/psidhu42/school-district-analysis/blob/main/resources/math_scores_by_grade.PNG)![Math Scores Without THS 9th Graders](https://github.com/psidhu42/school-district-analysis/blob/main/resources/math_scores_by_grade_altered.PNG)

* Reading Scores by Grade

![Reading Scores by Grade](https://github.com/psidhu42/school-district-analysis/blob/main/resources/reading_scores_by_grade.PNG)![Reading Scores Without THS 9th Graders](https://github.com/psidhu42/school-district-analysis/blob/main/resources/reading_scores_by_grade_altered.PNG)

### Scores by School Spending, Size, and Type

The scores by school spending, size, and type did not change at all, as shown in the following images of the DataFrames.

#### Spending

* With All Scores:

![Scores by Spending](https://github.com/psidhu42/school-district-analysis/blob/main/resources/scores_by_spending.PNG)

* Without 9th Grader Scores from THS:

![Scores by Spending Without THS 9th Graders](https://github.com/psidhu42/school-district-analysis/blob/main/resources/scores_by_spending_altered.PNG)

#### Size

* With All Scores:

![Scores by Size](https://github.com/psidhu42/school-district-analysis/blob/main/resources/scores_by_size.PNG)

* Without 9th Grader Scores from THS:

![Scores by Size Without THS 9th Graders](https://github.com/psidhu42/school-district-analysis/blob/main/resources/scores_by_size_altered.PNG)

#### Type

* With All Scores:

![Scores by Type](https://github.com/psidhu42/school-district-analysis/blob/main/resources/scores_by_type.PNG)

* Without 9th Grader Scores from THS:

![Scores by Type Without THS 9th Graders](https://github.com/psidhu42/school-district-analysis/blob/main/resources/scores_by_type_altered.PNG)

## Summary

Overall there isn't a huge change to the School District Summary after replacing the THS 9th grader scores with "nan". However four changes, though small, did show up. The "Average Math Score" of the district fell by 0.1. The "% Passing Math" in the district went down by 0.2%. The "% Passing Reading" dropped by 0.3%. Lastly, for the whole district, the "% Overall Passing" dropped by 0.1%. It should be noted that the "Total Student" count did not change in the "District Summary", because only the scores of the 9th grader students at THS were removed not the count of students themselves.