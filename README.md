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
Because of the sizes of csv file and tableau workbook are too large, I am not able to upload them into the repository from local.

## Tableau Story
https://public.tableau.com/app/profile/wei.zhang2701/viz/CitiBikeChallenge-Storytelling/CitiBikeStory?publish=yes

## Project Analysis
### Map with start data - filter with month and member type
<img src="/image/tableau_story.png" height="400" width="600" />

First of all, I present a basic density map using start stations data, filter with month and member type. From the first glance, people would see the place with heavy density is around the Harborside at the port. It shows a trend that a lot of people use Citi bike as a connection for their daily commute. <br>

### Average Travel Time
<img src="/image/travel_time.png" height="400" width="600" />

Citi bike offers two kind of users: members and causal users. The above graph could show that the number of members are larger than causal users. Moreover, there are different types of bikes under each type. <br>
From the above graph, people would see members are only have classic bikes and electric bikes. But causal users have an additional type of bike, which is docked bike. Classic bikes are the most popular choice for both members and causal users. <br>
With average travel time between classic bikes and electric bikes are very close. I tend to use the average travel time to define which type of bike might need more inspections or repairments. It is surprising to see that the docked bike is the winner, since it has the longest average travel time.<br>
On the other hand, if we use the number of rider counts for each bike type; the data show different results. Classic bike might be the one need frequent insepctions, because it is the most used one. <br>

### Peak Month Analysis with Rideable Type
<img src="/image/rideable_type.png" height="400" width="600" />

This graph shows the consistency of our data, that classic bike is the favorable one. Furthermore, this graph also presents the peak season. Compared with different seasons, people tend to use bikes more often during summer and fall. The data is slowly decreasing., The rider counts climb as people are entering spring. <br>

### Peak Day Time
<img src="/image/peak _time.png" height="400" width="600" />

### Top 10 Stations
<img src="/image/top_10.png" height="400" width="600" />

### Bottom 10 Stations
<img src="/image/bottom_10.png" height="400" width="600" />



