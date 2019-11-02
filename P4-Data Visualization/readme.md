# (Ford GoBike System data Exploration)
## by (Malak Alshedokhi)


## Dataset

There are 565,028 bike trips in the dataset with 16 fields (bike_id, bike_share_for_all_trip, duration_sec, end_station_id, end_station_latitude, end_station_longitude, end_station_name, end_time, member_birth_year, member_gender, start_station_id, start_station_latitude, start_station_longitude, start_station_name, start_time and user_type). There are fields that were calculated using the givin fields, like; member_age, start_month, start_month_time, start_time_weekday, start_time_day, start_time_hour.
The data set containg information about 3 months of 2019, April, May and June. 
They are sorted. Most variables are numeric in nature, but the variables start_time and and end_time have been converted to DateTime data type.


## Summary of Findings

In the exploration, I found that there was a strong relationship between the the day of the trip and the duration. When I have started the analysis, I was curious about the relationships between the different variables provided in the dataset. I have started exploring the duration of bike trips, and I have found that the mean duration is 12.5 minutes, the shortest trip was 1 minute long, while the longest trip took 24 hours. Moving on, I have started to explore the age of the members, the ages were differing from 18 to over 100 years old, so I have decided to clean that a bit and omit those who were above 60 years old. I have found that most users are around the age of 30 years old. Moreover, the dataset contained information about gender, type of customer, daily usage and whether this trip was shared or not. Plotting those data showed that most of the users are male. Also, the subscriber user type is higher than the customer ones. Moreover, most of the trips were not shared.
  Furthermore, exploring the relationships between the different variables was interesting. Plotting the numeric variables showed a small positive correlation between member age and duration of the trip. In addition, plotting member age and duration of the trip against the categorical variables of the dataset showed some interesting insights. The median of male age is a little higher than the median of the female age. Also, on Saturdays and Sundays, the age of the bike renters is higher than the other days. While plotting the categorical variables against each other also provided interesting insights; Fridays get more customer user type than the other days, while Wednesdays and Thursdays are more popular among the subscribers. The weekends (Saturdays and Sundays) have the least number of bike renters. Lastly, plotting the hourly usage of the bikes among the week illustrated the following; We may notice now that among subscribers, between 7-9AM and 5-6pm are the most popular hours. From that we may derive that most of the subscribers are employees.
While costumers, have peek in the evenings (5-7 pm). Those maybe just casual renters and want to cruise the city after working hours.



## Key Insights for Presentation
For the presentation, I focus on just the influence of the main numeric variables; duration in seconds and age of member.

Also, I introduced each of the categorical variables one by one. 
