# PyBer_Analysis

## Overview
PyBer, a ride-sharing company, had hired us to do some basic analysis on their ridesharing data. Since wrapping up that project, PyBer has asked us to provide further analysis to better understand the makeup of their business (drivers, riders, and fares) by city type––urban, suburban and rural––based on city data and ride data provided by the company. 

We were asked to create a summary DataFrame of the ride-sharing data by city type; and, using Pandas and Matplotlib, to create a multiple-line graph that shows the total weekly fares for each city type for a designated timeframe. 

In this analysis, we'll summarize how the data differs by city type and how those differences can be used to make business decisions.

## Analysis
### Totals and Averages by City Type
Through merging the city data (city, driver count and city type) with the ride data (ride logs that include rider ID, city, date/time and total fare), we determined totals and averages of rides, drivers and fares based on city type. You can see the results in the table below.
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

#### Takeaways
* Higher population means more rides, and more rides require more drivers.
* This difference could be due to a multitude of things. There could be more distance traveled per ride in rural areas due to not being as densely populated. 
* Further research and analysis would need to be done in order to determine this.
* Look at the population of the cities in the datasets to detremine consistencies the share of ride-share users vs. the city's population.
* Look at distance per ride: rural routes are likely considerable longer. Also, total time in car.
* Look at share of car owners in the cities in question.
* Look at total per driver ID, if possible, to determine how much an average driver makes in a timeframe. It may narrow or widen the discrepancies between the city * types, as far as drivers are concerned.


### Fares By Timeframe By City Type (Jan-Apr)
(01/01/2019-04/29/2019). 

![PyBer_fare_summary.png](https://github.com/andeevosters/PyBer_Analysis/blob/main/Analysis/PyBer_fare_summary.png)

#### Results
Examining the chart, we can see the Urban city type is more profitable for PyBer than the Rural and Suburban cities, even though it has a considerably lower average fare per driver and average fare per ride. Every week in the above chart, urban cities consitently produced the most total fares compared to suburban and rural cities.
Rural, suburban, and urban cites all have peaks and valleys in total fares throughout the months examined. Interestingly, all three city types show a spike in total fares around the same time in mid to late February.

#### Takeaways

## Summary of Recommendations
<Based on the results, provide three business recommendations to the CEO for addressing any disparities among the city types. There is a statement summarizing three business recommendations to the CEO for addressing any disparities among the city types. (4 pt)>

One recommendation I would make is to look at the marketing strategy in each of the different city types. Are total rural fares so low because the population is not as aware of PyBer compared to that of an urban city? Or is there just no demand for ride-sharing in rural areas?
Second, I would reccomend trying to get feedback from customers in each of the three city types to see what improvements and changes can be made that would increase customer usage.
Third, in attempt to increase ride-sharing in rural areas, it may be beneficial to offer incentives such as discount codes to new and existing customers to encourage more rides. Discount codes may also be a good idea to incorporate during lulls. Further research would need to be done into when more users are ride-sharing (i.e. weekdays vs. weekends, morning vs. night, close to holidays? , etc.) to determine which times of the year tend to be slower.

•	The data may be indicating that there aren't enough drivers in the rural areas. Based on the laws of supply and demand, the rural drivers may be able to command a higher per ride fare than in the other regions. This might also be indicated by the flat trend in total revenues, there may not be enough drivers to meet the demand. Condidering increasing the number of drivers in these regions.
•	Given that the Urban drivers are getting the smallest per ride fare, again based on supply and demand, this may indicate that there is too much completition for rides in this area. A couple of suggestions to address this:
o	Shift some Urban drivers to the Suburban or Rural areas.
o	Since the Total Revenue in the Urban areas are trending upward, they may want to hold steady for a little while and see if this is due to increased demand, which my start to increase per ride fares and thus also the fare per driver amounts.
•	Given the relatively flat trend lines in the Suburban and Rural areas, consider putting together a marketing campaign to target those regions. It probaly wouldn't hurt to include the Urban regions also. This could increase the demand in all areas and start to incr the total revenues, fare per ride and fare per driver revenues.



### 1. 
### 2. 
### 3.

## Resources:
Matplotlib: 3.3.2; Python: 3.7.9
