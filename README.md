# (Ford GoBike System Data Exploration)
## by (Passy Mukami Miano)


## Dataset
> The dataset contains information about 183,412 individual rides made in the Ford GoBike bike-sharing system covering the greater San Fransisco Bay area. The dataset has several features which include: duration in seconds, start_time, end_time, user_type, member_birth_year, member_gender, start_station_name, end_station_name and other bike trip information. 

> Some preliminary data wrangling such as changing variable data types had to be performed before analysis. To be precise user_type and member_gender were changed to categorical variables while start_time and end_time were changed to datetime variables.

>I also extracted the hour and the day of the week a bike ride was made from the start_time column. This resulted into new variables namely start_time_weekday and start_time_hour.

>I also created a new variable age by subtracting each member_birth_year from the year the bike rides data was collected which is 2019. Morepver I also created the variable route by concantenating start_station_name and end_station_name.

## Summary of Findings
In the beginnig of my analysis I was mainly interested in finding insights and trends that could be helpful understanding bike usage among among users. This information could potentially be used to optimize the bike sharing system. The findings are as follows.

> Majority of users are subscribers.
> Many bike rides are less than 30 minutes.
> There are more male bike riders than female bike riders.
> Most users are between the age 25 and 35 and the number of users steadily decrease from ages 40 onwards.
> There are more bike rides from Monday to Friday than during the weekends that is Saturday and Sunday.
> In a day, the highest bike rides are observed during commute hours that is at 8am and 5pm.
> Most popular biking route is Berry St at 4th St to Sanfransisco Ferry Building.
> Customers pend more time during their bike rides than subscribers.
> Users of all ages tend to have bike rides whish are less than 200 minutes.
> Subscribers take more bike riders than customers throughout the day and also on all weekdays.
> Female users take longer bike rides along the week compared to male users.
> Customers take longer bike rides than subscribers throughout the week. However, in both cases the duration of bike rides increased during the weekends.
    


## Key Insights for Presentation

>For my presentation, I want to focus on the trends of bike usage along the day and during the week among different users and also the distribution of duration of rides.