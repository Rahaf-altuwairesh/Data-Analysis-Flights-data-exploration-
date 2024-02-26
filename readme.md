# (Flights data exploration)
## by (Rahaf Altuwairesh)


## Dataset

> This dataset report flights in the United States, For the first quarter of 2008. Including variables like carriers, arrival and departure delays, and more other features.for more information[https://community.amstat.org/jointscsg-section/dataexpo/dataexpo2009]


## Summary of Findings
* The flight cancellation rate in the first quarter of 2008 was 3%.
* The airline with the highest frequency is WN (Southwest Airlines), and the airline with the lowest frequency AQ (Aloha Airlines).
* Delayed departure has outliers however most of the values were around and at zero. and By seeing the plot and skewness(6.30) and kurtosis(99.80) indicators, that delays lie mostly on the left side - most delays are short - of the graph, with a long tail to the right - longer delays cause higher right skewness.We also note interesting negative values, which indicate that the trips started ahead of schedule.
* The biggest reason for flight cancellations was the carrier and the weather, followed by the National Air System.
* The airline AA(American Airlines)occupies the highest number of flight cancellations, and the airline AQ(Aloha Airlines)occupies the lowest number of flight cancellations,and this is logical because the number of flights in it is few.The interesting thing is that the airline WN(Southwest Airlines) is located in the average cancellation values, and it occupies the most number of flights.
* The airlines with more than 30 minutes average delay are HA(Hawaiian Airlines),YV(Mesa Airlines),EV(Atlantic Southeast Airlines).
* The airlines with less than 11 minutes average delay are FL(AirTran Airways), B6(JetBlue Airways), WN(Southwest Airlines).
* The interesting thing is that the airline WN(Southwest Airlines) have a less than 11 minutes average delay, and it occupies the most number of flights.
* Friday has the most delays and Wednesday has the least number of delays-best day to fly-.
* February has the most delays In the first quarter of the year, and April has the least number of delays-best month In the first quarter to fly-
* Through the bar chart, we noticed a positive relationship between the delay of arrival time and the delay of departure, whether it was for the days of the week or months in the first quarter.
* From the clustered bar chart , we see that Wednesdays usually have the lowest average departure delays, and Fridays the highest average departures delays in the first quarter of the year.

**convert (month and day of week column)to categorical to make it easier to read through visualization.**
**Change the data type (Cancelled) column to 'bool'**
## Key Insights for Presentation

* interesting negative values in departure delay, which indicate that the trips started ahead of schedule.
* We notice that Friday is the most day that people having flights on in the first quarter of the year.
* there is a significant correlation between arrival delay and departure delay. There is also an average correlation between carrier delay, arrival delay and departure delay. however,It looks like there aren't so many correlations between the quantitative features. But we observed so much detailed information when utilizing it with other features.

## Sources
* https://aspm.faa.gov/aspmhelp/index/ASQP___Carrier_Codes_And_Names.html
* https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/HG7NV7
* https://medium.com/@atanudan/kurtosis-skew-function-in-pandas-aa63d72e20de
* https://seaborn.pydata.org/generated/seaborn.barplot.html
* https://www.transtats.bts.gov/DatabaseInfo.asp?QO_VQ=EFD&QO_fu146_anzr=b0-gvzr&QO_anzr=Nv4yv0r%FDb0-gvzr%FDcr4s14zn0pr%FDQn6n&Yv0x=D&DB_URL=
* https://community.amstat.org/jointscsg-section/dataexpo/dataexpo2009