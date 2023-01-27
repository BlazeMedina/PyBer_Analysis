# PyBer_Analysis

## Overview of PyBer_Analysis
PyBer CEO requested analysis of the ride-sharing data.

1. DataFrame summary of the ride-sharing data by city type.
2. Graph that shows the total weekly fares for each city type.
3. Summary of how data differs by city type and how those differences can be used by decision-makers at PyBer.

## Resources
- Data Source: city_data.csv, ride_data.csv
- Software: Python 3.6.1, Jupyter Notebook 

## PyBer_Analysis Results
![PyBer_Summary.png](https://github.com/BlazeMedina/PyBer_Analysis/blob/main/analysis/PyBer_Summary.png)


The summary of the ride-sharing data by city type show that:
- Rural City Type:
	- The average fare per ride is high at $34.62
	- The average fare per driver is high at $55.49
	- Although both the average fare per ride and driver are higher than the other city types, there were substantially less total rides (125) as compared to the other city types thus resulting in the lowest total fares of $4,327.93
	
- Suburban City Type:
	- The average fare per ride is $30.97
	- The average fare per driver is $39.50
	- With a total rides of 490 for the same time period it resulted in a total fares of $19,356.33

- Urban City Type:
	- The average fare per ride is low at $16.57
	- The average fare per driver is the lowest at $24.53
	- Although both the average fare per ride and driver are lower than the other city types, there were substantially more total rides (1,625) as compared to the other city types thus resulting in the highest total fares of $39,854.38

![PyBer_fare_summary.png](https://github.com/BlazeMedina/PyBer_Analysis/blob/main/analysis/PyBer_fare_summary.png)

The graph of the total weekly fares by city type show that:
- All three city types performed above their perspective averages the week of Feb. 24, 2019.
- During this timeframe the urban cities total fare outperformed the other two city types each week.
- City peeks:
	- Rural - week of 04/07/2019 with $501.24 total fares 
	- Suburban - week of 02/24/2019 with $1,415.75 total fares 
	- Urban - week of 03/10/2019 with $2,470.93 total fares 

    
## PyBer_Analysis Summary
In the rural cities there are less drivers than rides, if PyBer were to increase the number of drivers, thus increasing the availability should result in more rides.  With the average fare being higher, the percentage increase to total fares should be substantial. Conversely, the urban cities have substantially more drivers than rides.  That is creating a substantially lower average fare per driver.  PyBer should not increase the number of drivers in the urban cities until the demand for rides increase substantially.  Finally, the suburban cities seem to perform very well when compared to urban cities.  The suburban cities do not bring a higher total fare however, they produce a ratio of nearly 5:1 when comparing the total drivers to the total fares of suburban cities to urban cities.


