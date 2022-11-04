# Analysis of Bike Sharing Feasibility for Des Moines

## Project Overview

The purpose of this project is to analyze CitiBike data gathered from NYC to determine the demographics and typical uses of CitiBikes. This will help determine if a CitiBike program will do well and be economically feasible for Des Moines, Idaho. Tablesu Public was used to build the graphics into a story, which is linked below:

[link to dashboard](https://public.tableau.com/app/profile/casey.lee2755/viz/Bike_Modules/CitiBikeFinalAnalysis?publish=yes)

## Resources

* Tableau Public 
* Jupyter Notebook
* Microsoft Excel

## Analysis

The data set analyzed in this project was taken from the month of August of use of Citi Bikes across NYC. It included age demographics, gender, trip duration, starting and ending location, customer vs subscriber, and various other metrics. The first analysis conducted was a general analysis of some of the basics of the data, as shown below:
 ![general_data.png](/Images/general_data.png)
 *Screen capture from story showing the peak bike riding hours for August, the total number of riders, customers versus subscribers, and gender breakdown of riders.*
 
The peak riding time is from 7:00pm - 8:00pm and another smaller peak at 8:00am. This is to be expected considering these are the typical work commute times. The majority of riders are subscribers, meaning they have subscriptions to Citi Bikes, versus customers which are users without subscriptions. This is interesting because it shows that repeat customers are the majority of bike riders so an appealing subscription program seems to be a key to having a successful Citi Bike program. Also the majority of riders are males, this could be important for advertising demographics.
 
 Next analyzed were the top starting and ending locations as well as trip duration by age, as shown below:
  ![starting_ending_locations.png](/Images/starting_ending_locations.png)
  *Screen capture from story panel two*
  
The majority of rides begin and end in Manhattan compared to the other boroughs of NYC. This is likely due to the high density of work places and residents and the relatively compact layout of the city compared to Brooklyn, which could turn users off if the bike ride is too long like in Brooklyn. The trip duration graph shows a general trend of younger riders taking the bikes out for longer periods of time, which makes sense regarding users general health and fitness levels.

Next analyzed were the trip durations and bike utilization, as shown below:
![checkout_times.png](/Images/checkout_times.png)
*Trip duration of the entire sample and then broken down by genders. Bike utilization for each bike; each circle represents a bike, the larger the circle the more used that bike is.*

Most of the bike rides are short, which makes sense as in Manhattan the city layout is compact. This also implies that users prefer the short bike trips as that is the majority of the rides and therefore having more Citi Bike stations available in an area gives users more options for riding. This trend us important to note for a future company in Des Moines; users prefer short bike rides, which is great for profit versus use of the bikes. Each time a bike is taken out the user is charged to unlock the bike, then additionally charged every thirty minutes. The bike unlock fee is much higher than the additional thirty minute charges, so users preferring short trips is good news for profitability. The bike utilization grap interestingly shows how some bikes are used much more frequently than other bikes. This could be due to location and/or appearance of the bikes. The bikes that are used more often will generally need more reapirs so this is important to keep track of and maybe move the bikes around if some at some stations are being used much more frequently than others at different parts of the city.

Next analyzed were the weekday trips by hour and gender, as shown below:
![weekday_trips_by_gender.png](/Images/weekday_trips_by_gender.png)
*Screen capture from story panel four*

These heat maps show the peak hours per day. The peak hours Monday-Friday are different than the peak hours Saturday-Sunday. The Monday-Friday hours are the typical commute times, 7am-9am and 6pm-8pm. For Saturday-Sunday, the peak times are less intense and generally for the whole midday, from 10am-6pm. This is to be expected considering the work days versus the weekend schedules of users and can be noted for bike repairs in the future could be done in the morning hours of Saturday and Sunday. Again, the weekday by gender usage reflects that males are the primary Citi Bike users.

The final visualization in this analysis is shown below:
![trips_by_hour_gender.png](/Images/trips_by_hour_gender.png)
*Heat map comparing weekdays by each hour split into each genders usage. Note: the unknown gender sample population is left unchecked here because the sample size is small and reflects the same usage hours as the male and female data.*

This final heat map shows a combination of the previous panel. Interesting to note that Wednesday seems to be the day that the bikes are used the least. Again this final visualization shows that males use the bikes the most, the peak hours are the typical commute hours and midday on the weekends.

## Summary

In conclusion, the Citi Bike program in NYC is doing well because there are a lot of commuters who subcribe to the program and regularly use the bikes to travel around the city. Manhattan is compact enough to encourage this and there are many Citi Bike stations and bikes established. To be able to understand how this can relate to Des Moines, there needs to be an analysis of the city of Des Moines, the commuter population, the tourism stream, the gender distribution, and the layout of the city. NYC is unique in regards to other American cities in that is so compact; in a larger, more spread out city a Citi Bike program might not be as appealing to residents. NYC is also notoriously difficult to drive in and find parking; this should not be underestimated in its impact on the Citi Bike program for commuters. Also an important consideration is the presence of bike lanes. Without a developed bike lane system it could be too dangerous 
