# PyBer_Analysis
## Overview 
In this analysis, Matplotlib and Pandas was used to create a dataframe summarizing ride sharing data across the three city types (rural, urban, suburban) and to create a  multi-line graph of weekly fare totals across the first four months of 2019.

## Results
The Ride Share Summary DataFrame can be found below. 
![Ride Share Data Frame](https://github.com/dkristek/PyBer_Analysis/blob/main/analysis/pyber_summary.png)

The urban cities have a much larger amount of total drivers and total riders than the suburban and rural towns. However, the urban cities have more rides than drivers which is not the case for the other two city types. The average fare per rider and average fare per driver is the highest for rural cities and the lowest in urban cities. This trend makes sense as there is a smaller supply for drivers in the less populous cities which means the price could be expected to be higher than in urban cities. 


The multi-line chart can be found below.
![Multi Line Plot](https://github.com/dkristek/PyBer_Analysis/blob/main/analysis/PyBer_fare_summary.png)

All the city types have peaks in late-February; approximately $480 in total fares for rural cities, $1400 for suburban cities, and $2500 for urban cities. Total rural fares has another peak during early-March reaching around $500. Urban cities have two more peaks for fare total during early-March and late-March at ~$2500 and ~$2350.

A graph showing the weekly ride count by city type for the same time period was plotted and can be found below.
![Multi Line Plot Rides](https://github.com/dkristek/PyBer_Analysis/blob/main/analysis/PyBer_rides_summary.png)

This graph becomes more interesting when comparing it to the graph of the total fares graph. While the peaks of this graph correspond with the peaks on the fares multi-line plot for the most part, there are a few instances where this is not the case. In January, urban cities had a peak in total fares followed by a sharp decline and then another peak. This behavior is not present in the total rides graph; the slope of the graph remains positive throughout all of January. From the middle of March to the beginning of April the total rides for suburban cities increases. However in the total fares graph, fares for suburban cities peaks in late March and decreases until the middle of April.

## Summary
Based on the analysis, several discrepancies can be found between the different city types. One noticable discrepancy is the rise in fare total for rural cities during the first week of April while the total fare decreases for Suburban cities in the same timeframe. A possible business strategy to take advantage of this trend would be to relocate or otherwise encourage drivers from suburban areas into more rural areas during that time period to provide a higher supply of available drivers to the areas in more need. A second piece of advice would be to take advantage of periods of high ride volume by increasing fare prices. Conversely, discounts can be offered during periods of low volume to try to encourage people to order more rides. One final piece of advice would be to re-evaluate the amount of drivers in urban cities. Urban cities have move total drivers than they had rides, which was not the case for rural and suburban cities. It is possible that the availability of drivers is a net benefit for urban areas, however, further cost-benefit analysis on this point should be performed.
