# Ride-Sharing Data Analysis
## Exploratory Analysis of Fare and Ridership Metrics Across City Types : Rural, Suburban & Urban
The scope of this project is to perform an exploratory analysis comparing ride-sharing metrics (including total fares generated, number of riders, number of drivers, etc) against types of cities (categorized by urban, rural and suburban) for a specific time frame. The purpose of the analysis is to discover patterns and relationships between our metrics and our city types to inform high level decision making for ride share companies. Our data points are gathered across US cities from January 2019 to April 2019.

## Results
To give our results context it is important to note the incidence of each city type in our dataset - there are 18 rural, 36 suburban and 66 urban cities in total. Using this as our baseline we can see how each of the following metrics for city types tracks against the statistical representation of the city type in the dataset.
### Number of Rides by City Type
![rides_per_city](https://user-images.githubusercontent.com/107326987/179896250-edd69564-c554-4a70-ac95-666e666ae1ec.png)
![Fig6](https://user-images.githubusercontent.com/107326987/179901751-d562860e-31de-401d-ad67-12d35c5c9a06.png)

Ridership across city type is correlated to the city type representation in the dataset, however it is not a proportional relationship. Rural cities make up %15 of total cities but their ridership accounts for only just over 5% of total rides. Urban cities make up 55% of total cities represented in our data, but ridership accounts for 68% of total rides.

### Number of Drivers by City Type
![drivers_per_city](https://user-images.githubusercontent.com/107326987/179896274-a8811841-aadb-45e1-a695-51b95249356d.png)
![Fig7](https://user-images.githubusercontent.com/107326987/179901773-059b4c57-e4ca-47a7-bf6c-eab8c10f75f1.png)

80% of all drivers are in urban cities. There is a much higher concentration of drivers in urban cities than compared to drivers in suburban or rural cities. There are more drivers in urban cities than there were completed rides in the time frame of our dataset. We can conclude that some drivers did not successfully participate in a single ride.

### Total Fare and Average Fare by City Type
- ### Total Fare per City Type
![total_fare_per_city](https://user-images.githubusercontent.com/107326987/179896345-954b8b42-8d82-44de-b27f-a4777741b2de.png)
![Fig5](https://user-images.githubusercontent.com/107326987/179901719-4d7508c4-d73f-4784-92e9-22852e3180d8.png)

- ### Average Fare per Rider
![avg_fare_per_ride](https://user-images.githubusercontent.com/107326987/179896301-1be0b8a1-6cc9-4877-af39-ec5c1420f494.png)

The disparity in avg fare is much less than the spread of data across our other metrics. We can see that while the total fares collected in urban cities is much higher, when spread across the disproportionately high occurance of drivers, the average fare in urban cities is less than the average fare in rural cities. Rural cities are advantageous for drivers and disadvantageous for riders.

### Comprehensive Comparative Analysis
![challenge_fare_summary](https://user-images.githubusercontent.com/107326987/179896383-33cd6f0c-f4d2-4967-89e7-89f125c0e21e.png)

The line chart above shows that there is not a strong general upward or downward trend in ridership across the time span of January to April 2019. Neither are the peaks and valleys in ridership extreme, revealing a small standard deviation from the mean for each city type. Urban cities consistently generate the most revenue in ride fares across every data point. There is however, the most potential to increase ridership and generate more untapped revenue in rural cities.
- Summary Dataframe

![summary](https://user-images.githubusercontent.com/107326987/179896362-5ed9d1cb-d501-42b3-90cd-b2c20ed17389.png)

## Summary Outcomes & Takeaways
### Recommendation 1 : Further Analysis Incorporating Larger Dataset Across Longer Timeframe
The analysis would be more informative if we had datapoints for the entire year. It would be revealing to compare this analysis of the first trimester, against the 2nd and 3rd trimesters of 2019 to see if ridership data is chronologically consistent or if there are natural ebbs and flows in ridership participation and demand based on season. The analysis results would be more powerful as well if there was a comparison of population of people across city types. This statistic is critical in exploring the size of the potential customer pool and the current participation of the population in each city type.
### Recommendation 2 : Increase Ridership in Rural Cities
Rural cities make up 15% of our total city representation but rural ridership accounts for 5% of total rides. There is potential to increase ridership in rural cities if the average fare could be corrected to more closely match the market rate of urban cities. It would be important to note the average length of trip, perhaps the average trips in rural cities are longer and therefore more expensive. In this case the dollar per mile value is static - prices would need to be held artifically lower than suburban and urban per/distance fares in order to incentivize ride-sharing travel as a more realistic and popular option.
### Recommendation 3 : Incentivize Drivers in Rural Cities
Ride-share companies can provide a market correction for the over supply of drivers in urban cities. Drivers could be incentivized to drive in rural areas, as the average fare is higher and there is less competition. Access to more drivers could also drive the average fare per ride down, which might increase demand and in turn further support implementation of recommendation 2.  

## Resources
please visit resources folder for all originals of images referenced. The full python script of analysis can be found PyBer_Challenge.ipynb file. The raw datasets can be found in the analysis folder.
