# CitiBike-Challenge

## Data Source
Downlded citi bike data from August 2022 to July 2023. <br>
This project covers 12 month data.<br>
CitiBike Data: https://s3.amazonaws.com/tripdata/index.html)

## Data Cleaning
Used Jupyter Notebook to clean the data in all 12 csv files.
<img src="/image/data_cleaning_1.png" />

Checking data info then save it as csv file.<br>
<img src="/image/data_cleaning_2.png" height="400" width="400"/>

## Limitation
<img src="/image/cleaned_csv.png" height="250" width="600" />
Because of the file size of the csv and tableau workbook are too large, I am not able to upload them into the repository from local.

## Tableau Story
[Story](https://public.tableau.com/app/profile/wei.zhang2701/viz/CitiBikeChallenge-Storytelling/CitiBikeStory?publish=yes)

## Project Analysis
### Map with start data - filter with month and member type
<img src="/image/tableau_story.png" height="400" width="600" />

First of all, I present a basic density map using start stations data, filter with month and member type. From the first glance, people would see the place with heavy density is around the Harborside at the port. It shows a trend that a lot of people use bike as a connection for their daily commute. <br>

### Average Travel Time
<img src="/image/travel_time.png" height="400" width="600" />

Citi Bike offers two kind of users: members and causal users. The above graph could show that the number of members are larger than causal users. Moreover, there are different type of bikes under each user type. <br>
From the above graph, people would see members are only have classic bikes and electric bikes. But causal users have an additional type of bike, which is docked bike. Classic bikes are the most popular choice for both members and causal users. <br>
With average travel time between classic bikes and electric bikes are very close. I tend to use the average travel time to define which type of bike might need more inspections or repairments. It is surprising to see that the docked bike is the winner, since it has the longest average travel time.<br>
On the other hand, if we use the number of rider counts for each bike type; the data show different results. Classic bike might be the one need frequent insepctions, because it is the most used one. <br>

### Peak Season Analysis with Rideable Type
<img src="/image/rideable_type.png" height="400" width="600" />

This graph shows the consistency of our data, that classic bike is the favorable one. Linking with pervious graph, even though less people choose docked bike, but it is the one with longest average travel time. <br>

### Peak Analysis - dashboard
<img src="/image/peak_data.png" height="400" width="600" />

I use the start time to analyze the peak time for a day. The data shown in the graph is different from what I originally imagined. Because people would choose the bike as the connection for their daily commute, I was thinking that 7am to 8am would be the peak time of the day. But the graph shows a different story. The actual peak time is from 5pm to 6pm, when people are off work.<br>
Furthermore, this graph also presents the peak season. Compared with different seasons, people tend to use bikes more often during summer and fall. The data is slowly decreasing, when winter is coming. In contrast, the rider number climbs when the weaather becomes warmer. <br>


### Top 10 Stations - dashboard
<img src="/image/top_10.png" height="400" width="600" />

The top 10 starting stations and top 10 ending stations overlap. People seem to commute between those stations, and it also shows the consistent trend with the density map. <br>

### Bottom 10 Stations - dashboard
<img src="/image/bottom_10.png" height="400" width="600" />



