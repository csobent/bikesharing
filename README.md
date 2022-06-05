# Bikesharing in NYC
## Purpose of Analysis
The first part of preparing of this analysis was using Pandas to convert the tripduration from an integer to datetime. After this conversion, we used Tableau to create different visualizations to convince investors that a bike-sharing program is Des Moines is a feasible and profitable proposal. Using the converted tripduration, we were assigned to create a set of visualizations:
- Show the length of time that bikes are checked out for all riders and genders
- Show the number of bike trips for all riders and genders for each hour of each day of the week
- Show the number of bike trips for each type of user and gender for each day of the week

### Conversion Comparison
Before:
![Before_Conversion.png](Images/Before_Conversion.png)
After:
![After_Conversion.png](Images/After_Conversion.png)

## Results
- This picture depicts length of time bikes were checked out for all riders and genders:
![Checkout_Times_Users.png](Images/Checkout_Times_Users.png)

- This picture depicts a breakdown of length of time bikes were checked out filtered by gender. Males, represented by the orange line, use bikes 3-4 times more than females (yellow) and 9-10 times more than the other/unknown categorization (red):
![Checkout_Times_Gender.png](Images/Checkout_Times_Gender.png)

- This picture depicts a heatmap of bike utilization by weekday and by hour, filtered by gender. For the female and male categories, there is a trend in bikes being used more during the hours of 6AM to 10AM and then again between 5PM and 8PM. In the unknown category, there does not seem to be enough data to see a trend:
![Trips_by_Gender.png](Images/Trips_by_Gender.png)

- This picture depicts another heatmap of a breakdown of customer vs subscriber, filtered by gender. In the subscriber usertype, males use bikes more overall, but in the female and male categories, bike use is heavier between the days of Thursday and Saturday. Mostly subscribers use the bikes versus possible one-time use customers:
![Customer_Subscriber.png](Images/Customer_Subscriber.png)

