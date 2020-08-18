
# (Ford GoBike System Data Visualization)
## by (Hanan Alshehri)


## Dataset

> San Francisco Ford GoBike , managed by Motivate, provides the Bay Area’s bike share system. Bike share is a convenient, healthy, affordable, and fun form of transportation. People use bike share to commute to work or school, run errands, get to appointments, and more. The dataset contains trip data from 2013-2018, in this project I will use data of the year 2017 which includes 519700 trips and 13 variables which most of them are number value (duration_sec, start_time, end_time, start_station_id, start_station_name, start_station_latitude, start_station_longitude, end_station_id, end_station_name, end_station_latitude, end_station_longitude, bike_id and user_type). This dataset is clean (No duplication and No null values).


## Summary of Findings

- **Univariate Exploration:**
> In this section, I Observed that the majority of the users are 79% subscribers, and the most number of bike rides is in October month. Also, I needed a log transformation to make normally distribution for the duration variable.

- **Bivariate Exploration:**
> In this exploration, I investigated the relationships between trip duration and seasons and shows that the weather has an effect on the trip duration, and the top of them is summer. As well, The heatmap plot shows there is a lot of negative correlation between the numeric variables.

- **Multivariate Exploration:**
> In multivariate charts, I found that the customer through months or days has a little longer trips than the subscriber. In addition, our charts show that subscribers use the ride service from Monday to Friday, while customers preferred to ride on the weekends.


## Key Insights for Presentation

> For the presentation, I focused on the relationship between our main feature(s) of interest to strengthen: "This Time is for Bike!". First, I showed the distribution for Ford GoBike users, and ride duration. Then, I created a histogram for the most service months. After that, I used a plot for all the relationships between variables to see the impact and draw up a conclusion of who/when/how long people want to use the Ford GoBike System.