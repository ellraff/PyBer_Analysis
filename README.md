# PyBer Analysis

## Overview of PyBer Analysis
A ficticious python based ride-sharing company called PyBer requires an analysis of their ride-sharing data.  The goal of this project was to create a dataframe summarizing ride-sharing data by city type: urban, suburban and rural.  Then, to help visualize the data, a multiline graph was generated that shows total weekly fares for each city type.  Based on the results, conclusions can be made about how ride-sharing trends in the different city types.

## Results of PyBer Analysis
The first stage was to gather summary data for the different city types to get an idea of simple trends.  Using <a href = "/Resources/city_data.csv"> this city data</a> and <a href = "/Resources/city_data.csv"> this ride data</a>, the total rides, total fares, average fare per ride and average fare per driver were calculated for rural, suburban and urban cities using PyBer. The resulting dataframe is:
<p align ="center">
  <img src = "/analysis/PyBer_summary_by_city.png" alt = "Summary of PyBer Rides by City Type" width = "70%">  
</p>
Based on this data, there are some fairly obvious trends for each city type.  Although the total rides, total drivers and total fares are highest by far in urban cities, the average fare per ride and per driver are both the lowest for urban cities.  Suburban cities have much lower ride and driver counts, but their average fares per ride and per river are significantly higher than urban cities.  This makes sense because the amount of total drivers is almost 800 more then the total rides.  The average fair per ride is somewhat low because typically in urban cities, riders may not need to go that far compared to a rural city, but the average fare per driver is so low because there's simply too many of them compared to the available business.


Although the rural city fares per ride and per driver are rather high, the number of rides is very low.  As I mentioned before, typically riders in rural areas may need to go further than someone would need to in a urban or suburban city.  The amount of rides over time is important to recognize and peaks in activity in any of these areas.

<p align ="center">
  <img src = "/analysis/PyBer_fare_summary.png" alt = "Summary of PyBer Rides by City Type over time" width = "70%">  
</p>
The data was sorted into weeks to get a clear view of any peaks.  Although there are some peaks, the overall trend of the data for each city type seems consistent throughout. Although the rural city data seems higher compared to the others in the summary dataframe, this plot above shows, even though it's somewhat consistent, the total amount of rides is extremely low.  

There definitely seems to be a distinct peak in the 3rd week of march for all city types and then a peak for rural in early april while ther others consistently dip.  This may be a slight rise in ruraly cities due higher interest in rural areas in spring but there's no conclusive evidence of that.  

## Summary of PyBer Analysis
First of all, even though rides are low in rural areas, ride fare is high, so people are willing to pay more and the fare per driver is also high.  If PyBer came up with some kind of discount for new riders in rural cities and encouraged more drivers to start getting on, then the average ride fare may go down a little but the quantity of rides may go up.  Suburban cities seem to be the middle ground but more busy than in rural areas and at peak times like weekend or holidays, prices could be increased based on demand in order ot take advantage of the surge.  Urban cities have a very high driver to rider ratio, but rides happen more often than in the other cities.  By basing prices off of demand, this could increase profits while also ensuring consistent growth by keep prices lower when demand isn't as high.  Since urban cities have more room for growth typically, promotions for new riders should be initiated with coupons or deals.
