# BikeSharing
Analyzing NYC bikeshare data from CitiBike - Exploring Data Visualization with Tableau

## Purpose and Overview
The purpose of this analysis is to prepare a presentation using visualizations that showcase to investors the different aspects of this business and communicates its potential. The analysis is conducted on data from a successful bikeshare company in New York City - CitiBike. With this data, we look specifically at the usage of the bikes, where they are most popularly used, what times of day, and for how long they are typically used - among other parameters. Identifying these trends is aimed to help the business owners, as well as the investors, predict how to make the idea successful in another city.

## Results
To view the data visualizations in their entirety, please visit [my Tableau Public profile](https://public.tableau.com/app/profile/chichi.ugochukwu/viz/BikeShare_Challenge_16648924371160/NYCCitiBikeShareStory?publish=yes)

### User Data 
![](https://github.com/chichi-ugo/BikeSharing/blob/main/images/user_data.PNG?raw=true)

We observe there or more male users that female. We also see that there is a higher percentage of users that are subscribers 

### Peak Hours of Use in August
![](https://github.com/chichi-ugo/BikeSharing/blob/main/images/peak_hours.PNG?raw=true)

Not only does this visual show when riders are biking most often, it also helps indicate the best possible times to preform maintenance on the bikes

### Bike Usage
![](https://github.com/chichi-ugo/BikeSharing/blob/main/images/bike_usage.PNG?raw=true)

By creating a visual for each bike's usage, we can get an indication of when the bike will need to undergo maintenance.

### Popular Starting Points
![](https://github.com/chichi-ugo/BikeSharing/blob/main/images/pop_start.PNG?raw=true)

This visual shows where the highest volumes of starting points are in the city. Not depicted is a map of the ending points - we found that the end points map was almost completely indistinguishable from the starting points, so we have not included it in the presentation.

### Trip Duration
|           |           |
|-----------|-----------|
|![](https://github.com/chichi-ugo/BikeSharing/blob/main/images/trip_duration.PNG?raw=true) | ![](https://github.com/chichi-ugo/BikeSharing/blob/main/images/trip_duration_gen.PNG?raw=true) |

Here we observe that the average duration for bike rides was about 5-6 minutes across all genders. We also see again that males use the bike share service more than females.

### Weekday Breakdown of Trip Duration
|           |           |
|-----------|-----------|
|![](https://github.com/chichi-ugo/BikeSharing/blob/main/images/trip_wkday.PNG?raw=true) | ![](https://github.com/chichi-ugo/BikeSharing/blob/main/images/trip_wkday_gen.PNG?raw=true) |

With these visuals, we are able to further see the trend for usage. We note that there is increased usage during commuting hours (8AM and 5-6PM) and high usage on the weekends. We also observe that males and females show a similar pattern of usage.

### Weekday Breakdown by User Type
![](https://github.com/chichi-ugo/BikeSharing/blob/main/images/usertype_gen.PNG?raw=true)

Here we see the usage between the two different types of users - customers (1-time users who pay each trip) and subscribers (repeat users who pay annually). We observe higher usage from subscribers, and particularly males. 

## Summary
All in all, bikeshare services have remarkable potential to do well, especially in high traffic cities where there is a good population of residents, as well as a high tourism rate. We observed that the service has a high male usership and can plan specific marketing goals to target the female demographic from this insight. We also noted high usership during the morning and evening - commuting hours - during the weekdays, and a more even spread of rides during the day on the weekends. This insight can help us devise marketing targets that incentivize users to increase usage (i.e., discounts or deals during popular riding hours). Finally, we were able to get a general idea of bike usage that can help to plan for maintenance and upkeep of the bikes.

For further analysis, we should consider:
- Having a more descriptive measure for bike maintenance.
  - i.e., an average of how many times each bike undergoes maintenance, common maintenance done (fill tires, replace chains, etc.), and average cost of maintenance per bike.
- Further breakdown of the "Trip Duration" parameter.
  - Looking at trip duration for each day of the week to see if riders take longer trips on certain days.
  - Looking at trip duration in relation to area (Start and End latitude and longitude) to see if there is a heavier focus on tourist-centric areas or if it is more widely and evenly dispersed throughout the city.
    - Further could breakdown this point to compare the different days of the week - seeing if weekends have a higher usage around tourist areas.
