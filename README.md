# NY CitiBike with Tableau  

## Overview of The Analysis
By utilizing data from a New York City bike sharing program, a data analyst may be able to help investors make data-driven decisions regarding whether or not her startup bikesharing program in Des Moines, Iowa could be successful and deserving of investment.  

## Results

A fully interractive dashboard may be found 
[here.](https://public.tableau.com/shared/QKTF6SRWH?:display_count=n&:origin=viz_share_link "here.")  

### Single Use Customer vs. Program Subscribers  
![Visualization](images/1.png)
We see well over 75% of all users are subscribers.  This would indicate a consistent revenue stream from local users rather than one-off tourist or "try it out" usage.  

### Trip Length by Year of Birth  
![Visualization](images/2.png)  
Users may have input erroneous data for year of birth (it is unlikely that someone born in 1891 rode a bike through New York City for 45 mintues).  More telling is the trip length amongst late Millenial and Gen Z users.  An analysis of average birth year of Des Moines residents could predict the relative success of the program based on age and length of trip.  


### Length of Trip  
![Visualization](images/3.png) 
Most rides last less than twenty minutes.  Considering this is New York City data, we should consider the average time it may takes to bike between locations in Des Moines through an analysis of Google Maps bike time data between residential areas and commercial areas around Des Moines.  

### Length of Trip by Gender  
![Visualization](images/4.png)  
More male than female users are shown to utilize the bikesharing program.  Marketing should consider targeting the female population of Des Moines to increase revenue and utilization.  

### End of Ride Time of Day  
![Visualization](images/5.png)  
Weekday rush hour and common work start and end times are unsurprisingly when the largest numbers of rides end during the weekdays.  On weekends, rides end more in the middle of the day as people utilize the bikes for leisure and other enjoyment.  

### End of Ride Time of Day by Gender  
![Visualization](images/6.png)  
Gender appears to have little impact on when a ride may end.  Lighter hues and values for the female heatmap simply indicate the relatively lower number of total female users.  

### Usage by Day, Customer Type, and Gender  
![Visualization](images/7.png)  
Thursdays tend to be the busiest days, and again, men seem to use the program more.  Single-use customers, as expected seem to utilize more on the weekends, indicating tourist usage.  Marketing should focus on consistent revenue-stream subscriber models geared towards women to both increase user base and capitalize on the heavier usage subscirber model.  

Note:  Repair costs associated with more usage by subscribers should be considered when pricing subscription pricing.  
## Summary
Ultimately the results illustrate that men tend to use the bikesharing program more than women.  Commute times are expectedly clustered around rush hours during weekdays, and leisure hours during weekends.  Subscription customers significantly outweigh single-use customers, illustrating that the program is typically used for travel by residents of the area more than, perhaps, tourists.  Most rides usually last less than twenty minutes.  Ultimately, more demographic information would be necessary about metropolitan residents of Des Moines, Iowa and how they compare to the demographic infomration from New York City, New York shown in this analysis.

I would suggest demographic data visualizations for Des Moines, Iowa, specifically average ages.  As we see from the trip length by year of birth, younger generations tend to use the program more than older generations.  Furthermore, I would utilize google maps data to create visualizations regarding average bike commute times in and around multiple residential and commercial locations in downtown Des Moines; if the typical calculcated commute is over twenty minutes, that may pose a problem for this proposed business.

## Acknowledgement  

Utilized code to create a calculated field converting datetime format to trip time in seconds.  

http://tableauworkaround.blogspot.com/2016/06/hhmmss-to-seconds-in-tableau.html
