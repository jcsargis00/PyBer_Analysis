# PyBer_Analysis
### Background
This report has been prepared for V. Isualize to summarize data trends found in an in-depth
analysis of the multi-city PyBer ride sharing company data troves.  The analysis used city and 
ride data provided by PyBer.

Cities were categorized as urban, suburban or rural.
Fares were tracked by driver, city, average fare and total fare.

Data differences in the different types of cities will be summarized for PyBer decision
makers to make changes to address the findings.

A summary follows the findings with recommendations to address disparites found amongst the differing city types.
### Analysis
#### Overview
Pandas functions were used to create a customized PyBer data frame.  From the data frame,
the total number of rides, total number of drivers and the total fares for each city type 
were found.  With this information, average fare per ride and average fare per driver 
for each city were calculated.
#### Results

The total rides for each city type were 125 (rural), 625 (suburban) and 1625 (urban).
#
![total rider](https://github.com/jcsargis00/PyBer_Analysis/blob/main/Resources/totalrides.PNG)
#
The total number of drivers for each city type were 78 (rural), 490 (suburban) 
and 2405 (urban).
#
![total drivers](https://github.com/jcsargis00/PyBer_Analysis/blob/main/Resources/totaldrivers.PNG)
#
The total fares collected by city type were $4,327.93 (rural), $19,356.33 (suburban) 
and $39,854.38 (urban).
#
![total fare](https://github.com/jcsargis00/PyBer_Analysis/blob/main/Resources/totalfares.PNG)
#
The average fare per ride by city type was $34.62 (rural), $30.97 (suburban) and 
$24.53 (urban). 
#
![avg fare ride](https://github.com/jcsargis00/PyBer_Analysis/blob/main/Resources/avgfarperide.PNG)
#
The average fare per driver for each city type was $55.49 (rural), $39.50 (suburuban), 
and $16.57 (urban).
#
![avg fare driver](https://github.com/jcsargis00/PyBer_Analysis/blob/main/Resources/avgfareperdriver.PNG)
#

#### Differences in ride-shaing data amoungst the different city types
Urban rides comprised 68% of total rides, while suburban rides were 26%, and rural rides
were only 5%.  However, average fares in rural areas were much higher and the average fare
per ride was also higher in rural areas.  This could be due to shorter length of rides
in urban areas, an area to look into if the data is available.  Total fares by area
were much higher in urban areas, due to the volume of rides and drivers, compared to 
the other city types.  
#
![pie chart rides/city](https://github.com/jcsargis00/PyBer_Analysis/blob/main/Resources/numberridespie.PNG)
#### Ride-sharing data

#### Summary - Addressing disparities amongst the city types
#
![summary](https://github.com/jcsargis00/PyBer_Analysis/blob/main/Resources/summary.PNG)
#
Data collected by city type is shown below in the figure titled "Total Fare by City Type."
* PyBer ridesharing service is used much more in urban city types.
* Average fares per ride were higher in rural city types.
* Fares peaked from the last week of February in all city types.  
* Fares peaked through the first week in March in urban areas.
* Total fares were consistently lower in rural areas and suburban areas. 
* The number of drivers was also lowest in rural areas.  
* The higher cost per ride in rural areas could be a factor in less usage
#
![Summary figure](https://github.com/jcsargis00/PyBer_Analysis/blob/main/analysis/PyBer_fare_summary.png)
    
There may be opportunities to expand PyBer ridesharing with changes in the number of drivers
per city type and changing pricing structure for fares based on distance
* Based on the findings, consider pricing per fare changes by city type
* Gather additional data to see length of rides, does it effect pricing
* Survey drivers - are rural drivers underpaid, would there be more with higher salaries
    * Is the # of drivers or the pricing effecting the business bottom line in each city type?
    * If yes, possible solutions:
    - Urban cities - hire less drivers to increase demand and increase average fare price
    - Urban cities - minimum charge fore short trips?  surcharge for waiting in traffic?
    - Rural and suburban cities - hire more drivers to drive average fare prices down and increase usage
    - Which cities are underserved?  Do these areas have a smaller percentage of drivers?