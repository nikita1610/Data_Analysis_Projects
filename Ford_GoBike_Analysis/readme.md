# Communicate Data Finding : Ford GoBike System Data
## by Nikita Jain


## Dataset

> I chose Ford GoBike System Data as my source data for carrying out this project. 
This data set includes information about individual rides made in a bike-sharing system.
Multiple data files corresponding to each month of 2018 was downloaded and combined to form a dataset for one whole complete year. 
The various features included in the dataset are:
Trip Duration (seconds)
Start Time along with date
End Time along with date
Start Station ID
Start Station Name
Start Station Latitude
Start Station Longitude End Station ID
End Station Name
End Station Latitude
End Station Longitude
Bike ID
User Type (Subscriber or Customer)
bike_share_for_all_trip

> Various columns of dataset were removed namely :
1. bike_share_for_all_trip
2. start_station_id
3. end_station_id

>Various new columns were also added such as:
1. trip duration in minutes
2. start month of trip
3. start day of trip
4. start hour of trip
5. trip distance


## Summary of Findings

> For carrying out the Data Analysis, data from January to December of year 2018 was considered.Around 18,63721 bike rides were recorded in the year 2018.

The demand for bike rentals was high between the months April to October months due to summer season and a significant drop was seen during winter season. 
Subscribers use the service during Weekdays from Monday to Friday to carry out daily day to day activities whereas customers tend to use it more on weekends to go in 
trips or to have fun.

85% of Subscribers are using bike service compare to customers using bike service with 15%.People use this service on weekdays more than weekends. 
Subscribers' average trip duration is around 11 minutes. Customers' average trip duration is around 32 minutes. 
Customers tend to go on a longer trip distance as compared to subscribers and on the contrary trip distance for subscribers mostly ranges from over 0.06. 
Trip duration of suscribers tend to remain stable and follow a particular trend whereas no significant trend can be observed in patterns 
of trip duration of customers.

## Key Insights for Presentation

> Distribution of bike rides according to month,day and hour
-It looks like Bike sharing is used mostly used on weekdays as compared to weekends.In weekdays bike may be used to carry out daily activites such as to commute 
to office,schools or colleges and on weekends may be used for fun activites.We can see a significant decrease in number of bike rides as winter season 
approaches while bike rides were at peak in October, followed by July month. 
The number of bike trip are at peak in office hours that is at 9 am and 5pm taking peaks at both these times.

>Distribution of Trip Durations:
-The first plot drawn was right-screwed having a  long tail its right. Then logarithmic transformation to x-axis was applied
 so that plot is easily interpretable and results can be drawn to interpret.Frm the new plot drwan after applying logarithmic transformation to duration in minutes it can
 be interpreted that  ]a majority of people use bikes for short duration trips mostly for 10 minutes and trip duration ranges from mostly 1 minute to 100 minutes.