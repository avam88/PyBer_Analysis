# Ride-Sharing Data Analysis by City Type
## Exploratory Analysis of Fare and Ridership Metrics Across City Types : Rural, Suburban & Urban
Exploratory analysis comparing metrics including total fares gathered, number of riders, number of drivers etc against types of city (categorized by urban, rural and suburban) by mining our large dataset. The purpose of the analysis is to discover patterns and relatinoships between our metrics and our city types to inform high level decision making for ride share companies. Our data points are gathered across US cities from January 2019 to April 2019.

## Results
To give our results context it is important to note the incidence of each city type in our dataset - there are 18 rural, 36 suburban and 66 urban cities in total. Using this as our baseline we can see how each of these metrics for each city type track against the statistical representation of the city type.
### Number of Rides by City Type
![rides_per_city](https://user-images.githubusercontent.com/107326987/179896250-edd69564-c554-4a70-ac95-666e666ae1ec.png)
![Fig6](https://user-images.githubusercontent.com/107326987/179901751-d562860e-31de-401d-ad67-12d35c5c9a06.png)

Ridership across city type is correlated to the city type representation in the data set, however it is not a proportional relationship. Rural cities make up %15 of total cities but their ridership accounts for only just over 5% of total rides. Urban cities make up 55% of total cities represented in our data, but ridership accounts for 68% of total rides.

### Number of Drivers by City Type
![drivers_per_city](https://user-images.githubusercontent.com/107326987/179896274-a8811841-aadb-45e1-a695-51b95249356d.png)
![Fig7](https://user-images.githubusercontent.com/107326987/179901773-059b4c57-e4ca-47a7-bf6c-eab8c10f75f1.png)

80% of all drivers are in urban cities. There is a much higher concentration of drivers than in suburban or rural cities. There are more drivers in urban cities than there were completed rides in the timeframe of our dataset. We can conclude that some drivers did not successfully participate in a single ride.
### Total Fare and Average Fare by City Type
- ### Total Fare per City Type
![total_fare_per_city](https://user-images.githubusercontent.com/107326987/179896345-954b8b42-8d82-44de-b27f-a4777741b2de.png)
![Fig5](https://user-images.githubusercontent.com/107326987/179901719-4d7508c4-d73f-4784-92e9-22852e3180d8.png)

- ### Average Fare per Rider
![avg_fare_per_ride](https://user-images.githubusercontent.com/107326987/179896301-1be0b8a1-6cc9-4877-af39-ec5c1420f494.png)

The disparity in avg fare is much less than the spread of data across our othe metrics. We can see that while the total fares collected in urban cities is much higher, when spread across the high disproportionately high occurance of drivers, the average fare is less than the average fare in rural cities. Rural cities are advantageous for drivers and disadvantageous for riders.

### Comprehensive Comparative Analysis
![challenge_fare_summary](https://user-images.githubusercontent.com/107326987/179896383-33cd6f0c-f4d2-4967-89e7-89f125c0e21e.png)

The line chart above shows that ridership peaks and valleys are not dramatic over time span of January to April. Urban cities consistently generate the most revenue in ride fares across every data point. There is however, the most potential to increase ridership and generate more untapped revenue in rural cities.
![summary](https://user-images.githubusercontent.com/107326987/179896362-5ed9d1cb-d501-42b3-90cd-b2c20ed17389.png)

## Summary
### Recommendation 1 : Further Analysis Incorporating Larger Dataset Across Longer Timeframe with More Data Points
The analysis would be more informative if we had datapoints for the entire year. It would be revealing to compare this analysis of the first trimester, against the 2nd and 3rd trimesters of 2019 to see if ridership data is chronologically consistent or if there are natural ebbs and flows in ridership participation and demand based on season. The analysis results would be more powerful as well if there was a comparison of population of people across city types. This statistic is critical in exploring the size of the potential customer pool and the current participatino of the population in each city type.
### Recommendation 2 : Increase Ridership in Rural Cities
Rural cities make up 15% of our total city representatio but rural ridership accounts for 5% of total rides. There is potential to increase ridership in rural cities if the avergae fare could be corrected to match market rate of urban cities. It would be important to note the average length of trip, perhaps the average trips are more expensive because they are traveling further, in which case the dollar per mile value is static. In this case, prices would need to be held artifically lower than suburban and urban per/distance fares in order to incentivize ride-sharing travel as a more realistic and popular option.
### Recommendation 3 : Incentivize Drivers in Rural Cities
Market correction for over supply of drivers in urban cities. Drivers could be incentivized to drive in rural areas, as the average fare is higher and less compentition. Access to moer drivers would also drive price down a little, which might increase demand. "Data for rural cities shows that the average fare per ride and average fare per driver is much higher than Suburban and urban cities.This can indicate that rural area based riders are taking trips over a longer distance. This can result in a majority of drivers being occupied with current trips and loss in potential revenue when there are peaks in business." Recommendation 2 and 3 go hand in hand. 
### Recommendation 4 : Correct for Market Supply of Drivers in Urban Cities
Artificially high amount of drivers in urban cities, more drivers than there are rides. keeping the average fare artifically low.

## Resources
please visit resources folder for all originals of images referenced. The full python script of analysis can be found  . . .
