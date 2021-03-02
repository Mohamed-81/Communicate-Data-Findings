
# Ford GoBike Communicating Data Findings Project
## by Haotongli
## feb 16 2021

##bicycle sharing system in California's San Francisco Bay Area. It is operated by Motivate in a partnership with the Metropolitan Transportation Commission and the Bay Area Air Quality Management District. Bay Wheels is the first regional and large-scale bicycle sharing system deployed in California and on the West Coast of the United States. It was established as Bay Area Bike Share in August 2013. As of January 2018, the Bay Wheels system had over 2,600 bicycles in 262 stations across San Francisco, East Bay and San Jose.
## Dataset
### Structure of dataset

there are 174,952 records in the dataset with 12 features ( duration_sec , start_time , end_time , start_station_id , start_station_name , end_station_id , end_station_name , bike_id , user_type , member_birth_year , member_gender, age)
01. **`duration_sec`**: Trip Duration (seconds)
02. **`start_time`**>: Start Time and Date
03. **`end_time`**: End Time and Date
04. **`start_station_id`**: Start Station ID
05. **`start_station_name`**: Start Station Name
06. **`start_station_latitude`**: Start Station Latitude
07. **`start_station_longitude`**: Start Station Longitude
08. **`end_station_id`**: End Station ID
09. **`end_station_name`**: End Station Name
10. **`end_station_latitude`**: End Station Latitude
11. **`end_station_longitude`**: End Station Longitude
12. **`bike_id`**: Bike ID
13. **`user_type`**: User Type (Subscriber or Customer – “Subscriber” = Member or “Customer” = Casual)
14. **`member_birth_year`**: Member Year of Birth
15. **`member_gender`**: Member Gender
16. **`bike_share_for_all_trip`**: Boolean to track members who are enrolled in the "Bike Share for All" program for low-income residents
17. **`start_metro_area`** <u>[added feature]</u>: Starting station's metro area
18. **`end_metro_area`** <u>[added feature]</u>: Ending station's metro area
19. **`member_age`** <u>[added feature]</u>: Age of user
20. **`age_group`** <u>[added feature]</u>: Age group of user
21. **`month`** <u>[added feature]</u>: Month of ride
22. **`weekday`** <u>[added feature]</u>: Day of week of ride
23. **`hours`** <u>[added feature]</u>: Time of day of ride

### Accessing Summary

01. what is the avarage age of users? the most user age from 30 :35 years

02.what is the most user type ? We can see the the above plot is subscriber is the most user type

03.what is the most gender ? We can see the the above plot is male is the most Gender

04.what the relationshipe between Age and trip duration ? (Trip Duration) is very dependendable on the (age) of the member avarage age about 25 : 35 take the trip in shorter time than the older

05.what the relationshipe between Age and trip duration with gender ? (Trip Duration) is very dependendable on the (gender) of the member tha male take the trip in shorter time than the female