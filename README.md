# bikesharing

[Link to Tableu Dashboard](https://public.tableau.com/app/profile/tamara.espinosa/viz/CitiBike-Challenge14/BikeSharingAnalysis?publish=yes) - [[1]](#1)

## Table of Contents
- [Overview of Project](#OverviewProject)
- [Results](#Results)
  * [Website Functionality](#Website)
  * [Code](#Code)
- [Summary](#Summary)
- [Resources](#Resources)

## <a name="OverviewProject"></a>Overview of Project

The purpose of this project is to analyze the data from August 2019 Citi Bike System in NYC [[3]](#3) in order to see if a similar bike sharing project could be deployed in Des Moine, Iowa. August is the month were the most bikerides would be taken in NYC. We used Pandas and Python to make a minor modification to the Timestamp column of the data [[2]](#2). Then we used Tableu to visually tell the story of the Citi Bike data [[1]](#1).  

## <a name="Results"></a>Results

NYC has a population of approximately 8.38 million people (according to wikipedia). In the month of August there's 2,344,332 riders (28% of the population). Of those riders the vast majority of them have a long term subscription to the bike sharing program (1,900,359 riders) where as customers do not represent a large percentage of the rider base (443,865 riders). As a commuter town with large use of public transportation, it makes sense that the majority of the use is by people with a subscription. We have also found out through our data that the majority of users are male (1,530,272 male users vs 588,431 female users, unknown gender is composed by the rest of the riders).


The bike stations with the most bike pick ups and drop offs match the areas where commuters go to work in. Additioanlly, the peak hours for bike usage are betweem 8-9 am and 4-7 pm. These two facts indicate that a good amount of the bike usage is for commuting to and from work. Our heatmaps indicate that Monday through Friday at peak commuting hours mike usage is the strongest, further cementing this point. 

We have learned that the trip duration of most bike rides are less than 40 minutes for all customers. When we see the check out times by gender, we discover that females and males bith ride less than 40 minutes, and the number of users for the time spent seems to be somewhat proportional to the overall number of users by gender. One thing that we can't see in this data is that most ridesharing services have a time limit for each time the bike is checked out. This could explain why most trips are under 40 minutes.  

## <a name="Summary"></a> Summary

The data analyzed helps us paint a picture of a commuter town using the bike sharing service as an alternative to public transportation. We gathered the information from the month of August thinking of it as the month with the most bike usage. 

In order for us to determine if Des Moine would have a succesful bike sharing system, we would have to compare the weather trends of NYC and Des Moine to see their similarities. 

Additionally, we would need to know if Des Moine is a commuter town (like NYC) and if the commutes would be at a bike riding distance. Finally, it would be good to compare the population distribution and compare it to that of NYC. 

Although there's a lot of tourism in NYC we found that the majority of usage for bikes comes from commuters. We would have to gather data in Des Moine about tourism and commuters to see how well this business would do.   


## <a name="Resources"></a>Resources

<a name="1">[1]</a> [Link to Dashboard](https://public.tableau.com/app/profile/tamara.espinosa/viz/CitiBike-Challenge14/BikeSharingAnalysis?publish=yes)

<a name="2">[2]</a> [Code to Modify Tripduration](https://github.com/tamiespinosa/bikesharing/blob/db5b8c6f964e7fe27c20b484120a442adec24f2c/NYC_CitiBike_Challenge.ipynb)

<a name="3">[3]</a> [Data Source - "201908-citibike-tripdata"](https://s3.amazonaws.com/tripdata/index.html)

[5] https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax
