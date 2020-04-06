# US Mobility during the COVID outbreak

*Authors:*

**Emanuele Massaro (1)**

*1. EPFL*


*Notice: this is preliminary analysis, has not yet been peer-reviewed and is updated daily as new data becomes available. This work is licensed under a Creative Commons Attribution 4.0 International License.*     


## Data

Mobility data is provided by Unacast, a location intelligence, and measurement platform. This first-party data is collected from anonymized users who have opted-in to provide access to their location data anonymously, through a GDPR-compliant framework.

Location is collected anonymously from opted in users through smartphone applications. At the device level, iOS and Android operating systems combine various location data sources (e.g. GPS, wifi, beacons, network) and provide geographical coordinates with a given level of accuracy. Location accuracy is determined by the device and is variable, but can be as accurate as 10 meters.

Temporal sampling of anonymized users’ location is also variable and dependent on app/OS characteristics and on user behavioral patterns, but it has a high-frequency overall. We selected a panel of users who were active during the period 19 March - 03 April 2020. This leads to a sample of about 17Million users with a total of about 175 billion data points over the period of study. The basic unit of information we process is an event of the form (anonymous hashed user id, time, latitude, longitude), plus additional non-personal metadata and location accuracy.

## County Level

In this section we show the reduction of mobility at county level in the US.

![GitHub Logo](countyMap.png)

We can notice a clear distinction between the coast and the center of the US. We report the temporal profile of the recution of the mobility between March 19th and April 1st in terms of radius of gyration and average traveled distance.

![GitHub Logo](temporalCountyDist.png)

![GitHub Logo](temporalCountyRg.png)

An interesting question is to see the difference between the business days and the weekends. In the next we report the map of the reduction of the mobility for the business days between March, 20th to March, 31st in comparison withe the first day of the analusis, i.e. Maarch 19th.



## New York City

In the first process we analyzed the reduction of mobility in NYC. We analyze more than 9 billion data points and 1'375'515 distinct users. In the Figure we report the reduction of the traveling distance in each neighborhood.    

![GitHub Logo](NYdiffMap11.png)

In the next figure we report the average distance per user per day in the entire City.  

![GitHub Logo](temporalDist.png)

In the same way we report the radius of gyration. 


![GitHub Logo](temporalRadius.png)

We also study the correlation between the distance drop and the socio-economic status of the different district. We plot the correlation between houseld income and travel redduction at the community district level.

![GitHub Logo](correlationIncome11.png)

The plot indicates a positive correlation between travel reduction and houseld income.


