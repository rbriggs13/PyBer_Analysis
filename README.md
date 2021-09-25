# PyBer_Challenge_Analysis

## Overview
The purpose of this analysis is to but the fare, driver, and ride count per city type(urban, suburban, or rural) into context in order to properly inform business decisions for the near future.

## Results
A summary of the data is displayed below:
![PyBer_summary_dataframe](https://user-images.githubusercontent.com/87343629/134773117-81752de0-f1aa-465c-9f44-872d79ec7c2b.png)

as well as a line graph describing the total fare by city type over the course of 4 months:
![PyBer_fare_summary](https://user-images.githubusercontent.com/87343629/134773212-450b05c3-2aeb-4b10-ab01-30f7ae0189f7.png)
The data summary shows that the total values for fare, rides, and drivers all follow the same trend, with urban having the most, suburban having the second most, and rural having the least of all three. However the averages are where the data gets interesting. Both the average fare per ride and the average fare per driver follow the opposite trend with rural having the most and urban having the least. With the average fare per driver having large disparities between each city type with a minimum of $15 difference between the averages of each category. The line graph indicates that while there is variance in fare between weeks on average they remain steady.
### Summary
Based on these results I would recomend the following decisions:
- Decrease the amount of urban drivers because the lower fare average per ride and significantly higher driver and ride count indicates that the urban rides are typically shorter, meaning that less drivers are required.
- Increase the amount of rural drivers because the higher fare average per ride and significantly less driver and ride count indicates that rural rides are typically longer, so with more drivers more passengers could be picked up while other drivers are occupied with other rides.
- Keep the same amount of drivers in suburban areas as the data indicates that the averages are where they should be.
