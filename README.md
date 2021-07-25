# Overview
The purpose of this challenge was to create various data visualizations using Tableau. This was done by creating worksheets that displayed various types of information with our data source that we initially cleaned up with pandas through Juypter notebook. 

[link to dashboard](https://public.tableau.com/app/profile/diana.handler/viz/NYCCitibikeStoryDVH/NYCCitibikeStory?publish=yes)


## Analysis

Checkout times by User:

![Checkout times for users](https://user-images.githubusercontent.com/82029390/126912996-558cb0a7-4c86-436a-bbed-72d97c18960b.png)

This graph displays the number of bikes checked out by duration for all users. We can filter this graph by the hour

Checkout times by Gender

![Checkout times by gender](https://user-images.githubusercontent.com/82029390/126913019-c569e723-478a-47d9-ae26-2419141d33a1.png)

Here we can see the number of bikes that are checked out by duration for each gender by the hour and weekday. We can also filter by hour and gender

Trips by weekday for each hour:

![Trips by weekday for each hour](https://user-images.githubusercontent.com/82029390/126913037-aa99d6a8-3690-4be2-a939-0a5a1ed97969.png)

The heatmap generated displays the number of bike trips for each hour of the week. The denser the color, the more bike trips for that given time. 

Trips by weekday for gender:

![Trips by gender weekday per hour](https://user-images.githubusercontent.com/82029390/126913082-b3e53003-cbcd-4a39-9a05-c78bb6d9de30.png)

This heatmap displayes the number of bike trips by gender for each hour of the days of the week. We are able to filted this heatmap by gender


Trips for each user and gender by hour and weekday:

![User Trips by Gender by Weekday](https://user-images.githubusercontent.com/82029390/126913093-5d43eaab-48a8-4f41-a2b9-3a19a73d34ea.png)

This heatmap exhibits the number of bike trips for each type of user and gender for each day of the week. We are able to filter by user and gender

Checkout Times by Gender:

![Checkout times by gender](https://user-images.githubusercontent.com/82029390/126913198-5e369dff-d047-4a32-8884-22272db92b03.png)

Here we can see the most popular checkout times between male, female, and unknown


Peak Hours by Gender

![Peak Hours by Gender](https://user-images.githubusercontent.com/82029390/126913206-2a919c59-3f33-47ab-a877-4dd1032eb40e.png)

This graph displays the relative number of males, females, and unknown gender people that use citibikes during August's peak hours.


## Summary
We can see that the Midtown/Downtown areas are the most popular starting locations for CitiBike usage in NYC during the month of August. The hours of 4-6PM are also peak hours. Of all users within these parameters, 10% are of unknown gender, 25% are female, and 65% are male. We can see that the most dense areas of new york city are the most poular for citi bike usage and thus it would be wise to suggest to the investors in Des Moines that it would be prudent to set up citi bike locations in the most dense areas of the city. It would be helpful to also download data pertaining the temperatures of the city in August and see how they compare with peak hours of citi bike usage. We could generate a tableau visualization to display both sets of data. We could also generate a tableau visualization to display the ages within the most popular locations.
