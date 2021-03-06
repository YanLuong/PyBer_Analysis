# PyBer Analysis

### Overview and purpose of the analysis.

The purpose of this analysis is to analyze ride sharing data on behalf of a ride sharing app company called PyBer. The focus is on how the data such as fares varies between the three different city types (urban, suburban and rural) of interest. We will be using Pandas and Matplotlib to summarise and visualise the results. 

----

### Results

After aggregating the data of the different city types, we can see that there are some key differences between them. In this analysis, covering a specific date range, the bulk of the rides is in urban cities accounting for 68% of the total rides. Suburban rides accounting for 26% and rural rides for only 5% of the total rides. As there are considerably more rides in the urban cities, it also makes sense that urban cities also have more drivers to meet the demand. There are a total 2973 drivers in this analysis, 2405 of those drivers are in urban cities (81%), 490 (16%) in suburban areas and 78 (2.6%) in rural areas. Urban city type also accounted 63% ($39,854) of the total fares earned while suburban accounted for 30% and rural for 7%. 

We can see that the urban city type account for most of the data in total rides, total drivers and total fares and the rural city type accounting for the least as it is likely due to it being less densely populated. However, it is interesting to note that the rural city type rides cost the most with the average fare per ride at $34.62 and average fare per driver at $55.49. This could be due to the fact that there are less drivers so that rate is higher or the distance covered is longer. Where as in the urban city type, we can see the that the average fare per driver is $16.57 and in suburban area at $39.50. This again makes sense, the higher density of the city type, the higher total rides, drivers and fares. The more densely populated a city type is, the more competitive the prices become as we can observe the lowest average fare per ride and average fare per driver is in urban city type. This could also be due to a difference in the distance of the journey. The opposite is true for rural city type with there being less drivers and higher fares. 

Another aspect that we have not accounted for in this analysis is car ownership may be a factor in the differences between the city types.

![Summary of dataframe](https://github.com/YanLuong/PyBer_Analysis/blob/main/Resources/Summary%20DataFrame.png)




![Total weekly fares by type](https://github.com/YanLuong/PyBer_Analysis/blob/main/analysis/PyBer_fare_summary.png)

----
### Summary

This analysis has highlighted the disparaties between urban, suburban and rural areas. The distance of the ride, the purpose of it and the accessibility of using ride sharing must vary between the city types. This is also reflected in the average fare per ride and the average fare per driver. 

The rural areas account for the least number of total rides and also happen to have the higher average fare per ride and average fare per driver so one of the recommendations would be to lower the pricing in the rural city type areas as there is still room to move lower or consider a more flat rate type fare for longer journeys. This would also apply to suburban areas as the average fare per driver is quite a fair bit more than the average fare per ride unlike in urban city type where it is reversed. This difference suggests that the fare range is significantly larger than in suburban and rural areas. The first recommendation may help encourage demand for ride sharing in these areas. The second recommendation, would be to carry out further analysis and research in rural areas and investigate whether or what barriers exist to explain the lower uptake in rural areas as the current data is quite limited. The third recommendation is to run some advertising campaigns to increase awareness in the lower density areas such as rural city types.


