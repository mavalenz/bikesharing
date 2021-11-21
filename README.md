# bikesharing

## Overview
### Help Kate create a tableau dashboard as a proof of concept to predict if a bike-share company idea could work in Des Moines. To do so we will perform the following:

1. Import the citi-bike data into Tableau Public.
2. Modify the data so that the data is represented accurately when it is viewed *(e.g. rename the columns, change the data types, join data sources)*.
3. Create graphs and plots through tableau worksheets.
4. Come up with a list of questions you want to answer to help you prove what it takes to develop a ride sharing program:
	- *How many trips were recorded during the month of August?*
	- *What is the proportion of short-term customers to annual subscribers?*
	- *What are the peak riding hours in the month of August?*
	- *What are the top bike stations in the city for starting a journey?*
	- *What are the top bike stations for ending a journey?*
	- *What is the gender breakdown of active riders?*
	- *What is the average trip duration by age?*
	- *Which bikes are most likely due for repair?*
	- *How variable is bike utilization?*
5. Create a dashboard with your worksheets for the in-person pitch to potential investors of this ride-sharing program.
6. Create a story.
7. Finally, help solidify the proposal by creating additional visualizations:
	- Show the length of time that bikes are checked out for all riders and genders.
	- Show the number of bike trips for all riders and genders for each hour of each day of the week.
	- Show the number of bike trips for each type of user and gender for each day of the week.

## Results
### Overall Bike Users Metrics Dashboard:
* There were 2,344,224 rides in our citibike dataset.
* There were male bike users at 1,530,272 over unknown and female riders.
* The number of rides increased as trip durations increased, for a 2 hour trip duration with 60 minute intervals number of riders were at 2,199.
* Monday, Tuesday, and Thursdays between the hours of 5-6PM appear to be where most citibike trips occur during the week.

![overall_bike_users_metrics](https://github.com/mavalenz/bikesharing/blob/main/Resources/overall_bike_users_metrics.PNG)

### Bike Users Metrics by Gender:
* There are more male than female and unknown that utilize bikes around the city.
* Male riders appear to add to the trend of Monday, Tuesday, and Thursdays between 5-6PM for most trips during the week.
* There are more subscribers than customers type of users. Of the subscribers majority appear to be Male.

![bike_users_metrics_by_gender](https://github.com/mavalenz/bikesharing/blob/main/Resources/bike_users_metrics_by_gender.PNG)
![trips_by_gender_by_weekday](https://github.com/mavalenz/bikesharing/blob/main/Resources/User_trips_by_gender_by_weekday.PNG)


## Summary
### In summary, per our analysis it seems that bike riders tend to use the citibike sharing before and after working hours. Male users take majority of the population of bike sharing around the city compared to female and unknown genders.

Further visualizations to add to this dashboard story for future analysis would be:

- The average distance traveled for each user and gender for each day of the week.
- The average trips for each user and gender by each month of the year.

