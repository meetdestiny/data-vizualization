## Introduction

I have analyzed whole data provided on github link for this assignment. While Seattle data contains more data than SFO,
but as we are supposed to compare both the cities, I ended up filter data of Seattle to match the period between 
06/01/2014 to 08/31/2014. This is the only period for which data is available for both cities. 


## Aggregate Analysis
In this chart, we can compare the daily counts of crime between Seattle and SFO. The pattern is almost similar with 3 marked drops in SFO. This is most probably due to data being not available. Otherwise, this chart does not show any marked difference in the trend of crime between these two cities. 
![Alt text](daily_pattern.jpg?raw=true "Optional Title")




## Hour Analysis
In this chart, we can compare the aggregate crimes committed on hour of day between 06/01/2014 to 08/31/2014. Within this period, similar trend can be observed for SFO and Seattle with SFO reporting slighlty lower crimes count between 4 AM and 4PM. It appears SFO has a better night life which is showing up in higher crime rate between 4 PM to 2 AM. 
![Alt text](hour.jpeg?raw=true "Optional Title")

## Hour per Day Analysis
In this chart, the daily cycle of crime is very evident. We see the crime counts between 06/01/2014 to 08/31/2014 based on hour of day ( 0 to 23 format )  on day of week (1-7) basis, we can clearly see the regular cycle of crime rates. The X-axis labels are a concatenation of day of week ( 1 = Sunday, ...) with hour of day separated by a dash. Thus, 1-0 as label would mean Sunday 12 AM at night and 4-5 would mean Thursday 5 AM. 

This chart is very clearly showing the daily peaks of crime rate to happen between 12PM and 2 PM. 
![Alt text](day_hour.jpeg?raw=true "Optional Title")
