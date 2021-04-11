#PyBer_Analysis

# PyBer Analysis Overview
Utilizing raw **PyBer** company data to analyze and create visualizations for rides between 01/19 and 05/19 in various markets

## Results:

Here is the summary of our results, which breaks down the number of total rides, total drivers, total fares, average fare per ride, and average fare per driver in each market. 

<img width="505" alt="Ride Summary" src="https://user-images.githubusercontent.com/78561980/114319611-c8a78500-9ad7-11eb-898b-5607db473644.png">

Digging a bit deeper, we looked at how the PyBer ride data was distributed by city type to identify how we are meeting the market need. As seen in the box-and-whisker plot, Rural markets make up 3.5x to 4x fewer rides per city than in Urban and Suburban markets, respectively.

![Number Rides by City Type Box-and_whisker](https://user-images.githubusercontent.com/78561980/114319744-6b600380-9ad8-11eb-8721-ea2f1e5613d9.png)

In addition, the average ride fare in Rural markets ($34.62) is about 30% higher than that of Urban markets ($24.53) and over 10% higher than Suburban markets ($30.97). 

![Number Rides by Fare Box-and_Whisker](https://user-images.githubusercontent.com/78561980/114319749-6f8c2100-9ad8-11eb-85b3-6a41d474a07a.png)

Regarding the quantity of drivers we have in each market, Rural markets (78 total drivers) have 96% fewer drivers than Urban markets (2405 drivers), and 84% fewer drivers than Suburban markets (480 drivers).

![Number Drivers by City Type Box-andwhisker](https://user-images.githubusercontent.com/78561980/114319751-70bd4e00-9ad8-11eb-8724-f7433c8fb125.png)




## Summary:

The analysis provided shows the three city types (Urban, Suburban, and Rural) differ greatly in volume of rides and drivers, as well as average fares per ride and driver, and total fares by city type.


![Total Rides by city type pie chart](https://user-images.githubusercontent.com/78561980/114319757-76b32f00-9ad8-11eb-924e-f2e8d9eff0a6.png)

![Total Fares by city type Pie Chart](https://user-images.githubusercontent.com/78561980/114319755-7450d500-9ad8-11eb-86ef-ffb3f5c9c5ca.png)

![Percent of Drivers by city type pie chart](https://user-images.githubusercontent.com/78561980/114319760-79ae1f80-9ad8-11eb-91bb-a6179bf83758.png)

This scatter plot shows a cohesive visual of the distribution of rides, fares, and driver count by market.

![Ride Sharing Summary Bubble Plot](https://user-images.githubusercontent.com/78561980/114319739-669b4f80-9ad8-11eb-9671-087cdde267bc.png)

## Recommendations:

Although the rural market makes up a fraction of our overall business, the limited number of drivers combined with higher fares customers are willing to pay, provides an opportunity to increase revenue by adding additional drivers and decreasing fares to increase demand. 
My second recommendation is to implement incremental fare increases in Urban markets to maximize revenue, because of the high demand.

![Pyber_fare_summary](https://user-images.githubusercontent.com/78561980/114319764-7d41a680-9ad8-11eb-93e8-35a8c85f07c8.png)

Lastly, I recommend performing addition analysis (specifically regression analysis) to determine the correlation between rides and fares in each market, as well as variations in demand by week, month and quarter to determine the number of drivers needed, adjustments in fare to capitalize on peak time periods, and promotions to stimulate demand in non-peak time periods. 

The following chart is an example of the variation of total fares week-to-week to highlight peaks and non-peaks
 on a small scale, which supports my third recommendation.
 
<img width="223" alt="Weekly Data" src="https://user-images.githubusercontent.com/78561980/114319605-c34a3a80-9ad7-11eb-9c20-c3164e6b3868.png">


