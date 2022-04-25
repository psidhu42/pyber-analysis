# Ride-sharing Data Analysis

## Overview of Project

Analyze ride-sharing data and determine how different factors affect the overall outcomes.

### Purpose

Analyze the ride-sharing data from "PyBer", based on city type determine the number of rides, number of drivers, and the average fare per ride and average fare per driver. Once that data is collected create a multiple-line graph that shows the total weekly fares for each city type. Report how the data is different by city type and how it can be used.

## Results of Analysis

The following results show how the data compares between city types.

### PyBer Summary DataFrame

![PyBer Summary DataFrame](https://github.com/psidhu42/pyber-analysis/blob/main/analysis/Summary_df.png)

As seen in the DataFrame above, although Urban cities have larger totals for Rides, Drivers, and Total Fares, they have the lowest Average Fares per Ride/Driver. Rural cities have the fewest Total Rides and Drivers, but have about 3.35 times the Average Fare per Driver of Urban cities. Average Fare per Ride for each city type has a smaller diffrence than that of Average Fare per Driver for each city type.

This Bubble Chart is a good visual representaion of the Average Fares and Total Number of Rides by City Type.

![PyBer Bubble Chart](https://github.com/psidhu42/pyber-analysis/blob/main/analysis/Fig1.jpg)

### PyBer Weekly Summary

The data above was organized and sorted by dates and fares to better see how each city type performed on a weekly basis.

Here is an exmple of the new DataFrame created to help with the analysis.

![Fares by Week DataFrame](https://github.com/psidhu42/pyber-analysis/blob/main/analysis/fare_by_week_df.PNG)


## Summary

Overall there isn't a huge change to the School District Summary after replacing the THS 9th grader scores with "nan". However four changes, though small, did show up. The "Average Math Score" of the district fell by 0.1. The "% Passing Math" in the district went down by 0.2%. The "% Passing Reading" dropped by 0.3%. Lastly, for the whole district, the "% Overall Passing" dropped by 0.1%. It should be noted that the "Total Student" count did not change in the "District Summary", because only the scores of the 9th grader students at THS were removed not the count of students themselves.