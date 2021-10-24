# PyBer Ride-Sharing Analysis
## Project Overview

While working at PyBer a ride-sharing company, we created some simple analysis that the CEO V. Isualize had used for strategic decision making. V. Isualize was so impressed with our initial analysis and visualizations that we were tasked with another assignment. For this assignment, the CEO would like to see a matrix of key information by city type as well as a graph that shows the total weekly fares for each city type. To display this data in an easy-to-read format we will be using a line graph. 
## Resources
-	Data Sources: city_data.csv, ride_data.csv
-	Software: Python 3.7.6, Anaconda Version 4.10.3, Jupyter Notebook

## Results

### PyBer Data Summary 
After we merged the data provided to us we built a simple matrix that can be used to easily see the key metrics by city type that routinely get used in strategic decision making. There are totals by city type for rides and drivers as well as averages for fare per ride and fare per driver. 
Urban cities had higher totals and averages in all categories while rural cities were the lowest overall. 

PyBer City Type Summary Matrix: 

![PyBer_Summary_DF](https://user-images.githubusercontent.com/90698381/138612312-8571adc4-e1cb-4b6e-aa57-f81935841bdc.png)


Key observations in this matrix are as follows: 
-	Urban cities had more total drivers than total rides.
-	Rural and suburban cites had more total rides than total drivers. 
-	Urban cites made up for more than 62% ($39,854.38) of the total fares while rural cites made up for less than 7% ($4,327.93).
-	Average rural fares per driver are almost $40 higher than that of urban cites. 

### PyBer Weekly Ride Fare Summary 
To show the by week trend of the total fares collected by PyBer from January 2019 to the end of April 2019 we created a line graph per V. Isualize’s request. Similar to the previous analysis the graph below is grouped by city type and it clearly shows that urban cities collect the highest total fares (top line), suburban rides generally take in a moderate amount of fares (middle line) and rural fares bring in the lowest per weekly fares (bottom line). 

Total Fare by City Type Graph: 

![PyBer_fare_summary](https://user-images.githubusercontent.com/90698381/138612322-247032ec-b6ad-4c52-9286-e00269ed222c.png)

We can also see that weekly urban and suburban fares collected tend to be lowest at the start of the year in January and the rural fares peak in April. 
## Summary 
Based on our review of the PyBer city type summary matrix and total fare by city type graph it is our observation that there are a few disparities that can be explained by city type. While the total rides are substantially higher in urban cites there are more total drivers available than total rides. It was also discovered that there were more total rides than total drivers in both rural and suburban city types. It would be our recommendation that drivers in the urban environment be disbursed to rural and suburban environments to better accommodate citizens in those two types of cities. It is also clear that urban cities have a substantially lower average fare per driver than that of rural or suburban cities. This may be a simple example of the law of supply and demand. The high number of total drivers has created an increased supply of drivers which is greater than the number of total rides. We feel that through disbursing urban drivers to rural and suburban environments PyBer would lower the supply of drivers in urban cites therefor it would be our recommendation to then increase fares in urban cities generating greater revenues. Our analysis also shows that average rural fares are also much higher than that of urban cites and only marginally higher than that of suburban environments. Through disbursing the surplus of urban drivers, and better balancing drivers through all city types PyBer should lower the average fare in rural cities. This lower fare should be more than offset by the increased fare in Urban cities thus resulting in a balanced an equitable fare rate for citizens and equal average fares for drivers in all city types while still generating more overall revenue. To give an exact recommendation of fare by city type more analysis would need to be performed. Rural and suburban drivers may be travelling longer distances which could warrant the higher rates but we cannot decipher that with the data provided. 
