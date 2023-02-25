# Usage Analytics on Ford GoBike Sharing System
## by Uchenna Urom


## Dataset

The data is a csv excel spreadsheet containing 174, 952 recorded bike rides to and from different stations. There are 9 variables describing the features of the each ride. Some of the variables are the user-type, date and time of each ride, start and end station names, bike id and user gender.

The dataset was also divided into two tables to conform with tidiness standards. The trip_df table containing information on the each trip taken by a user. Also, the user_df table carries information about the user on each trip. 8, 460 rows were dropped from the original datset due to missing values.

Obtain the data [here](https://video.udacity-data.com/topher/2020/October/5f91cf38_201902-fordgobike-tripdata/201902-fordgobike-tripdata.csv).

Columns in the dataset includes: 
- Trip Duration (seconds)
- Start Time and Date
- End Time and Date
- Start Station ID
- Start Station Name
- Start Station Latitude
- Start Station Longitude
- End Station ID
- End Station Name
- End Station Latitude
- End Station Longitude
- Bike ID
- User Type (Subscriber or Customer)

## Summary of Findings

- The exploration revealed that the most frequent start and end stations were `Market St at 10th St` and  `San Francisco Caltrain Station 2  (Townsend St at 4th St)` respectively.

- It became clear that younger users rode longer distances that older users and age had no impact on daily use.

- A decline in the demand was also noted during the weekends compared to the usual rates during weekdays.

- Peak hours of usage during weeks days were between 0800 and 1000 in the morning and 1600 to 1700 in the evenings.

- This was different on weekends for both Customers and Subscribers during weekends. Here, peak hours were between 1000 and 1500 in the weekend.

- Although Males were more by headcount among genders, the proportion of subscribers within the genders was uniform among all genders.


## Key Insights for Presentation

The presenation slide deck uncovered the frequency distribution of trip duration (in seconds) among all users. It showed the mode duration to be around the 300 seconds mark. 

Further, investigation to the influence of user types on bike use showed that Subscriber user types had an overwhelming use by head count than Customer type.

Similarly, analysis of usage by genders revealed that Male gender group were more than any other gender. This also reflected across the user types.

Daily and hourly usage showed some interesting findings as well. First, weekdays had more demand than on the weekends. Then, the peak demand hours on weekdays were in the mornings and evening while weekends were during midday.