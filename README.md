# PyBer_Analysis

## Overview
The purpose of this analysis was to analyze ride data for PyBer, a taxi-like service.
Specifically, this project analyzed ride-data relating to fare's, and number of drivers for each type of city (i.e. urban, rural).
Additionally, the client Omar requested a line graph showing total weekly fares for each city type.
The results of this analysis can be used by PyBer to make important decisions regarding fare prices and hiring practices.

## Results
After cleaning and preliminary analysis pie charts were created to visualize and understand the impact of each city type on the company's costs and revenue.

![Fig5](https://user-images.githubusercontent.com/96553988/185920669-9221e411-7021-4c9f-ba34-6f13d78f14f8.png)
![Fig6](https://user-images.githubusercontent.com/96553988/185920682-7a14bcc8-6ddb-40e3-8624-ae08c03c96aa.png)
![Fig7](https://user-images.githubusercontent.com/96553988/185920687-fdbe5424-724b-4612-a12c-1c69e6f4904d.png)

The analysis created a dataframe of the important data regarding Omar's request, seen below.
![PyBer_summary_dataframe](https://user-images.githubusercontent.com/96553988/152713422-17d90214-8380-4e95-9477-e7b3c3ec9f7c.png)

From this dataframe we can see the total rides, total drivers, total fares, average fare per ride, and average fare per driver, for each city type.
Rural cities have the least number of rides and the least number of drivers, whereas Urban cities have the most.
Conversely, rural cities have the highest average fare per driver, as well as per ride.

![PyBer_fare_summary](https://user-images.githubusercontent.com/96553988/152713708-7239b07e-f85f-4b46-afc4-61ed4782fc60.png)

Above is a line graph representing the total fares for each city type for each week in the first 4 months on 2019.
This graph displays that Urban cities create the largest total fares, with suburban cities displaying the second most, and rural cities totalling the least fares.

## Summary
Based on the results of this analysis the recommendations I would make are to invest in getting more drivers in rural cities. Despite a low total fare, the average fare in rural cities is much higher than other city types and creates an oppurtunity for more profit. Conversely, urban cities seem to have too many drivers, I suggest we halt the hiring of additional drivers in urban cities. As can be seen in the data frame the number of drivers is greater than the number of rides and the average fare per driver is much lower than other city types. Suburban cities show a good yield in total fare without reaching a very low average fare per driver like urban cities do.
