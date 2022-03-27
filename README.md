# Bikesharing with Citi-Bike

## Description
The objective of this project is to take NYC Citi-Bike data to gain insight how this concept can be applied in other cities (in our case we are looking to implement something similar in Des Moines, Iowa). Some of the key points we hope to address in this analysis are: 
- Who uses bike sharing programs (gender, age, etc.)?
- What areas of the city use them the most?
- What times of day are the busiest?
- What oversights can be avoided (potential for bike repairs)?

## Results

The full report can be found by clicking the following link: [NYC Citi-Bike Analysis](https://public.tableau.com/app/profile/brandon.degraw/viz/NYC_Citi-Bike_Challenge/NYCCiti-BikeAnalysis?publish=yes)

Using the NYC Citi-Bike data at our disposal we created a number of visualizations using Tableau (public). The first of which is a breakdown by customer type (subscriber or customer) and by gender. You can see below that the number of Subscribers vastly outnumber the amount of Customers. You will also notice that the demographic using this service the most tend to be Male. Another thing that would be useful to know is if there is a discrepancy concerning age. From the graph below of Average trip duration by birth year, we can see a steady increase in general with the younger demographic. I would assume that if we plotted a count of users by age that the majority of them would be younger.

![customers](https://github.com/brand0j/Citi-Bike/blob/main/Resources/customers.PNG)
![avg_trip_duration](https://github.com/brand0j/Citi-Bike/blob/main/Resources/avg_trip_duration.PNG)

Another thing we were concerned with was the locations that saw the most activity. Below are visualizations detailing the most frequently used bike stations based on starting location and ending location (as expected these both correspond to the same relative area with minor differences).

![ride_start_locations](https://github.com/brand0j/Citi-Bike/blob/main/Resources/ride_start_locations.PNG)
![ride_end_locations](https://github.com/brand0j/Citi-Bike/blob/main/Resources/ride_end_locations.PNG)

Maintaining our bikes is a number one priority since the more bikes that are available to the public, the more they will be used. In the following plot we show the most active times when Citi-Bike is being used so we can identify a window where maintenance can be performed on bikes that have accrued the highest tripduration total (they are more susceptible to wearing down and breaking). This window was identified below, along with a unique plot of bike utilization for the bike_id as well as the end destinations that have the highest tripduration sum (the logic here is that these stations are the most popular and where the majority of the bikes end up at the conclusion of the day so we can prioritize specific stations to perform preventative maintenance on a group of bikes since they will be the ones that are used most frequently). When you hover on the bike utilizaiton chart it will display the respective station id or bike id. 

![peak_hours](https://github.com/brand0j/Citi-Bike/blob/main/Resources/peak_hours.PNG)
![bike_utilization](https://github.com/brand0j/Citi-Bike/blob/main/Resources/bike_utilization.PNG)

The following is a display of checkout times for all users along with checkout times by Gender. The analysis was detailed within Tableau and has been included here (as to not be redundant I will forego explaining the charts a second time)

![checkout_times](https://github.com/brand0j/Citi-Bike/blob/main/Resources/checkout_times.PNG)

Another visual we were interested in was to see which hours of the day were the most popular and on which days of the week. We decided to apply this in general, then again regarding gender, and a final time when considering our usertype (customer or subscriber). Most of this analysis is included within the story generated through Tableau. 

![trips_weekday_per_hour](https://github.com/brand0j/Citi-Bike/blob/main/Resources/trips_weekday_per_hour.PNG)
![user_trips_by_weekday](https://github.com/brand0j/Citi-Bike/blob/main/Resources/user_trips_by_weekday.PNG)

## Summary

To conclude our proposal, bikesharing services are popular in busy cities where maneuvering through it with alternate forms of transportations are beneficial not only for the individual, but to the environment as well. Our user base is primarily made up of male subscribers, but conducting a survey to address issues that might be preventing a larger female audience from subscribing would be step in the right direction. Most of the peak times occur around the typical work-day hours and commuting times. If this were to be further explored it would be interesting to see starting and ending locations during each hour of the day to observe the progression of traffic between different neighborhoods and which stations are more popular at certain times of day and which days during the week. Another interesting idea would be to explore if there was any difference between male and female users with respect to age.
