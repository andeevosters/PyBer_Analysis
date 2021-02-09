# PyBer_Analysis

## Overview
PyBer, a ride-sharing company, had hired us to do some basic analysis on their ridesharing data. Since wrapping up that project, PyBer has asked us to provide further analysis to better understand the makeup of their business (drivers, riders, and fares) by city type––urban, suburban and rural––based on city data and ride data provided by the company. 

We were asked to create a summary DataFrame of the ride-sharing data by city type; and, using Pandas and Matplotlib, to create a multiple-line graph that shows the total weekly fares for each city type for a designated timeframe. 

In this analysis, we'll summarize how the data differs by city type and how those differences can be used to make business decisions.

## Analysis
### Totals and Averages by City Type
Through merging the city data (city, driver count and city type) with the ride data (ride logs that include rider ID, city, date/time and total fare), we determined totals and averages of rides, drivers and fares based on city type. You can see the results in the table below.

#### Visual 1: Ride & City Data Summary
![PyBer_data_summary.png](https://github.com/andeevosters/PyBer_Analysis/blob/main/Analysis/PyBer_data_summary.png)

#### Results

##### 1. The total rides
Not surprisingly, urban cities had the largest total number of rides (1,625) more than double the suburban cities (625) and thirteen-fold of the rural cities (125). 

##### 2. Total drivers
Urban cities also have the largest total number of drivers (2,405), followed by nearly 1/5 of drivers in suburban areas (490), and only 78 rural drivers.

##### 3. Total fares
Rural cities accounted for $4,328 in fares, while suburban cities reported $19,356 (4.5 times more), and urban cities reported 8 $39,854 (9+ times more).

##### 4. Average fare per ride
Rural cities had the highest average fare per ride ($34.62), while urban cities had the lowest ($24.53). The average fare per suburban ride was $30.97.

##### 5. Average fare per driver
Like the average fare per ride, rural cities also had the highest average fare per driver ($55.49). Urban cities had the lowest average fare per driver ($16.57), less than one-third that of the rural driver. Surburban drivers had an average of $39.50, more than double the urban driver.

#### Takeaway
Higher population means more rides, and more rides require more drivers. It's no surprise that there are more urban rides and drivers, since there are more people in those cities, destinations tend to be closer together, less urban residents have cars than rural residents, and so on. The data above supports the supply and demand theory that one might expect to see for city types; however, more can be done to investigate potential disparities if needed or desired.


### Fares By Timeframe By City Type
Secondly, PyBer asked us to look at ride logs over a four-moth period (January through April 2019) to continue our analysis of data by city type. We looked at the total weekly fares, looking for trends by city type and/or by timeline. Below are the results. 

#### Visual 2: Total Weekly Fare By City Type (Jan-April '19)
![PyBer_fare_summary.png](https://github.com/andeevosters/PyBer_Analysis/blob/main/Analysis/PyBer_fare_summary.png)

#### Results
Rural fares did not see much fluctuation over the 4-month span, meanwhile suburban fares started and ended with an increase, and urban fares were a bit more frenetic across the timeframe. The obvious similarity was an increase in late February, among all the city types. 

#### Takeaway
Urban cities had significantly higher total weekly fares than suburban and rural cities, as we first learned in the data summary. The late-February peak is worth investigating.

## Summary of Recommendations
With the intention of the analysis being to identify any potential disparities between city types, the following actions are recommended:

### 1. With a bit more primary research, we can better understand supply & demand, fare discrepancies, and popular ride times.
* Distance of ride by city type: how far a driver drives per ride
* Length of ride by city type: coincides with distance to determine cost to driver
* Rider wait time by city type: supply vs. demand
* Total fares by driver ID: how much an average driver makes in a given timeframe
* Total fares by day of the week: Are rides requested mostly on weekends? Never on Tuesdays? This insight could help with better planning and marketing.

### 2. With secondary research to complement our primary research, we can better understand supply and demand as a way to affect pricing, marketing and recruiting.
* City population for cities in the datasets: supply and demand, market share
* Share of car owners in the cities in the datasets: supply and demand of both riders and drivers
  * For example, it is likely that rural communities have more car owners per capita. So, if the desire is to market to rural residents, sell reasons NOT to drive your own car. (Skip parking fees at airports, don't drink and drive, etc.)

### 3. Conduct a late-February deep-dive to understand the increase in rides across the board.
* (PyBer data): Did particular cities affect the overall increase in fares? 
* (Secondary data): Based on the city results, research if there was an event or need that was geo-specific? And/or can that success be duplicated?
  
## Resources
Matplotlib: 3.3.2; Python: 3.7.9
