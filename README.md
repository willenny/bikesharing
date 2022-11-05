# bikesharing

## Overview
With the dream of starting a bike share business in Des Moines, Iowa, citibike data from New York City was collected and analyzed to see if the business is feasible. Variables like Gender, Trip Duration, Start Time, and Stop Time were used to designed multiple charts and graphs that will drive the decision to begin the business. Using Tableau, dashboards were used to build a Story to present to an angel investor that is interested in the potential business. Kate will use the models in the Tableau Story during her proposal to the investor. 

### Resources
Data Source: 201908-citibike-tripdata.csv
Software: Tableau, Jupyter Notebooks, Python, Pandas

## Results
[View the Visualizations for the Trip Analysis](https://public.tableau.com/app/profile/will.enny/viz/VisualizationsforTripAnalysis/VisualizationsforTripAnalysis)
- The first Story Points gives the overall all number of rides during the month of August in NYC, a woppping 2,344,224 rides. With nearly 8.5 million people liviing in NYC, that comes out to about 1/4 of New Yorkers used citibike in August. Next we have a Gender Breakdown of the rides. About 65% of riders were male, about 25% were female, and the remaining 10% is unknown. Our first Story Point also describes the popular start times of riders, with a peak at 5am. It seems many riders are using citibike early in the morning, possibly as their means to commute to work. 
- The second Story Point shows a heatmap that describes the numbers of trips taken on each weekdays, broken down by the hours in the day. This shows the stop time of the rides, which the darkest colors appear at about 8am and 6pm. It seems that riders are using citibike in the morning to arrive to work and then once again in the evenings to return home from work. It is getting to be clear that the majority of citibike riders are using the bikes for the work commutes. This could be helpful information when choosing where the bikes are located in Des Moines. 
- The third Story Point breaks down the previous heatmap into genders. We can see the males are using the citibikes more commonly than females but it is important to note that the stop times for each gender are approximately the same. 
- The fourth and final Story Point shows a heatmap that breaks down the number of trips per day for each gender and user type. Subscribers are using the bikes more often than customers, which would be assumed. That being said, there is a subtle detail that we can make out of this. It appears that the customers are using the bikes more often on the weekends and the subscribers are using bikes more regularly during the week days. This could potentially drive a marketing strategy for each subscribers and customers based on the days of the week. 

## Summary
After diving into the concrete data about citibike, we are hopeful that Kate's proposal will be convincing to the angel investor. Our visualizations have shown insight to gender of riders, peak riding hours, and customer vs. subscriber trends. Although our graphs may be convincing, I believe there is still more information that can be tapped and analyzed. Two additional visualizations that I believe could be powerful are:
1. Using a filter for the User Type when looking at popular start locations. This could give insights on if subscribers are typically starting in a certain neighboor and if customers are beginning their trips based on a certain location as well. This could help our understanding of what bike locations would be best for Des Moines.
2. Looking at how old a bike is and how many trips it has had can help us keep all bikes in working order. By tracking each bikes trip duration, we can anticipate repairs or retirement.
