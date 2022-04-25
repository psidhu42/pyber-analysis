# Ride-sharing Data Analysis

## Overview of Project

Analyze ride-sharing data and determine how different factors affect the overall outcomes.

### Purpose

Analyze the ride-sharing data from "PyBer", based on city type determine the number of rides, number of drivers, and the average fare per ride and average fare per driver. Once that data is collected create a multiple-line graph that shows the total weekly fares for each city type. Report how the data is different by city type and how it can be used.

## Results of Analysis

The following results show how the data compares between city types.

### PyBer Summary DataFrame

![PyBer Summary DataFrame](https://github.com/psidhu42/pyber-analysis/blob/main/analysis/Summary_df.png)

As seen in the DataFrame above, although Urban cities have larger totals for Rides, Drivers, and Total Fares, they have the lowest Average Fares per Ride/Driver. Rural cities have the fewest Total Rides and Drivers but have about 3.35 times the Average Fare per Driver of Urban cities. Average Fare per Ride for each city type has a smaller difference than that of Average Fare per Driver for each city type.

This Bubble Chart is a good visual representation of the Average Fares and Total Number of Rides by City Type.

![PyBer Bubble Chart](https://github.com/psidhu42/pyber-analysis/blob/main/analysis/Fig1.jpg)

### PyBer Weekly Summary

The data above was organized and sorted by dates and fares to better see how each city type performed on a weekly basis.

Here is an example of the new DataFrame created to help with the analysis.

![Fares by Week DataFrame](https://github.com/psidhu42/pyber-analysis/blob/main/analysis/fare_by_week_df.PNG)

Once sorted into weekly bins the data was plotted as a multiple-line graph, shown below. In this line graph we can see that Urban City Weekly Fares stayed mostly between the $2,000 and $2,500 amount. Both Urban and Suburban cities started off lower at the beginning of the year and jumped up in the first week. Rural City Weekly Fares, shown in blue, are the lowest, and mostly are below the $500 line. All 3 city types however jumped up towards the end of February, and went back down the first week of March.

![Weekly Fares Multi-line Graph](https://github.com/psidhu42/pyber-analysis/blob/main/analysis/PyBer_fare_summary.png)


## Summary

In summary there are a few business recommendations, the first would be to decrease the difference in Average Fare per Ride between each city type, a more consistent average fare per ride would incentivize riders everywhere to use the service more often. The second is to increase the number of divers in the rural cities, this may help reduce the average cost of rides, which in turn would increase the number of people requesting rides, increasing profits. The third recommendation is similar in a sense to the 2nd, reduce the number of drivers in Urban cities, less drivers would mean a higher Average Fare per Driver.