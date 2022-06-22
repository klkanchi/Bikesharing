# Bikesharing

**An analysis of NYC CitiBike bikesharing data from August, 2019, with Tableau**
## Overview

This Tableau story can be seen, in its entirety, at this link.

The framework for this project was to analyze bikeshare data from CitiBike in New York City for presentation to investors looking to begin a bikeshare program in Des Moines, Iowa. While Des Moines is a long way away from the hustle and bustle of NYC, this analysis might help answer a few key questions:

    Who uses bikeshare programs?
    What area of a city sees the most bikeshare usage?
    What time of day are bikes used the most and the least?
    How much are the bikes used and by whom?

## Results

While the demographics of Des Moines may be different from the make up of the citizenry of NYC, a cursory look at the makeup of CitiBike riders may shine light on who bikeshare might appeal to, regardless of locale.

![Costumer_ride_count.png](https://github.com/klkanchi/Bikesharing/blob/main/images/Costumer_ride_count.png)

In the above image we can see that more than 3/4 of the users are Subscribers, who make regular use of the bikes and are a predictable source of income for the program. Bikeshare program users are also predominantly male, at approximately 5/8 to only about 1/4 female. The remaining 1/8 gender is unknown or undeclared.


![Number_of_rides.png](https://github.com/klkanchi/Bikesharing/blob/main/images/Number_of_rides.png)

The above map displays the bike stations from which recorded bike trips started. The size of the circles and darkness of the green indicate the relative number of trips started at those locations. It is apparent that the bulk of the bike trips are originating in the bustling commercial heart of Lower Manhattan, known for towering office buildings, densely packed residential skyscrapers, and entertainment venues. Bike usage is lower in the less densely packed surrounding neighborhoods.

![Number_of_rides_per_hour_day.png](https://github.com/klkanchi/Bikesharing/blob/main/images/Number_of_rides_per_hour_day.png)

This chart displays the number of bike rides initiated during each hour of the day, totaled across the entire month of August. We can see peak usage during morning rush hour and end-of-workday commute times. What is also of note is the low-usage hours between 2 AM and 5 AM. These hours would be the best times to conduct bike repairs and redistribution of bikes from full stations to less-full stations.



![Trip_duration_by_user.png](https://github.com/klkanchi/Bikesharing/blob/main/images/Trip_duration_by_user.png)

This graphing of number of trips by duration show that the vast majority of trips taken on CitiBike bikes are under an hour in length. More specifically, most trips are under a half-hour in length, with a swift dropoff in number of rides over an hour in length.

![Trip_duration_by_gender.png](https://github.com/klkanchi/Bikesharing/blob/main/images/Trip_duration_by_gender.png)

This breakdown of number of rides by duration, separated by gender, makes it even more apparent how many more rides are taken by male-identifying customers.

Lastly, the heatmap reinforces how much of the userbase is dominated by male-identifying, subscribing users. Why this is the case is unclear and warrants additional study.

## Summary

In conclusion, bikeshare services are remarkably popular in busy metropolitan areas, where occupied real estate is densely packed and parking spaces may be scarce. The user base is made up mostly of male subscribers, providing regular income to the program. More outreach should be done to attract female riders, but male users seem a reliable market. And main usage seems focused around morning and evening commute times.

If I were to pursue additional lines of inquiry for analysis and visualization, given the data provided, I would explore:

1. trip starting and ending locations during morning and evening rush hour time-windows, to display the flow of traffic between neighborhoods at peak hours;

2. average trip duration, by birth year, by gender, to explore if there was any difference in male or female or un-gendered riders as they age.

Tableau Story with additional images:
https://public.tableau.com/app/profile/krishna.kanchi8657/viz/NYCCitiBikeAnalysischallenge_16557631524160/NYCCitiBikeAnalysis?publish=yes


