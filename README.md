# CitiBike Ride Exploration and Visualization 2022
## by Ifeoma Ugbomah


## Dataset

[Citi Bike](https://en.wikipedia.org/wiki/Citi_Bike) is New York City’s bike share system, and the largest in the nation. Citi Bike launched in May 2013 and has become an essential part of transportation network. They make commute fun, efficient and affordable – not to mention healthy and good for the environment. Download 2022 in CSV format covering New York City area [here](https://www.citibikenyc.com/system-data)

**N.B**: The data used for this exploration is data from **`January`** to **`August`**.

##### Data wrangling process:
- fix started_at and ended_at not in correct format to datetime datatype.
- Missing values end_station_id and end_station_name, and end_lat and end_lng.
- Drop unnecessary columns(ride_id, start_station_id, end_station_id).
- Create a trip duration column from started_at and ended_at.
- Create trip start date, trip start hour of the day, day of the week and month
- cast 'start_dayofweek' to category dtype.
- cast 'start_month' to category dtype for easy plotting.


## Summary of Findings

The number of trips peaked around 17-19pm with saturday slightly higher than other days with a value of 86873. For the 2022, between January to August, the ride service usage increases with month. Most riders are members and ride type are classic bike, most rides were quick and short, lasted between 4 to 7 minutes. There was no unusual points and no transformation was also needed due to straightforwardness of the data.

There are a lot of member than casual users and the riding habit varies alot between both user type. Members uses the bike sharing system for work commute thus having low average trip between on work days (Mon-Fri) whereas casual tends to ride for fun especially over the weekend.

There are lot more member usage than casual overall. The short and efficient period of usage  for member between Monday through Friday indicate the use primarily for work commute. The more higher and flexible pattern of casual use shows that they are taking advantage of the bike sharing system quite differntly heavily over the weekends for city tour or leisure purposs probably.


>**N.B**: The data used for this exploration is data from **`January`** to **`August`**.

## Key Insights for Presentation

Different usage pattern/habit between the two type of riders are seen from the exploration. Members use the bike sharing system heavily on work days i.e. Monday through Friday whereas casual users rides a lot on weekends, especially in the afternoon. Many trips concentrated around 17pm-19pm on work days for members, while customers tend to use it more over the weekend with small difference between member and casual usage. The efficient/short period of usage for members corresponds to their usage from Monday to Friday, indicating the use is primarily for work commute. The more relaxing and flexible pattern of causual users shows that they're taking advantage of the bike sharing system quite differently from members, heavily over the weekends for city tour or leisure purpose probably.