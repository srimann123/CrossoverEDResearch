### System Design

Defining frequent ED users: 

The definition of frequent emergency department users varies throughout the literature, ranging from 3 ED visits to 7 visits annually. The most common threshold, however, is 4 visits annually. Although somewhat arbitrary, this classification is relevant for understanding the nuances behind extreme emergency department utilization in different patient populations. 

Ultimately, we decided to categorize frequent users as patients who utilized ED services 4 or more times in a 14-month period, closely adhering to the traditional definition while accounting for population-specific variance in frequent ED use by Crossover Health patients. This approach allows for a larger number of patients to be included in the frequent ED user group, resulting in a richer dataset.

System Inputs and Outputs:

Outputs: A binary indicator where 1 represents that the input translates to a frequent ED user and 0 translates to an infrequent user.




1. Who is a frequent user and who is not a frequent user?
over the span of the (data), >= 4 visits/yr

2. Who to include in our dataset, and from what points in time?

How Crossover defined the frequent user:
Data was collected (1/26/23): Who are our frequent users in the last 14 months? 14 months,,   x-14     x
In any 14 month period of a patient's timeline, have they been to the ED 4 or more times? 2018, 2022

Went back some standard amount of time, 

1. Data is all historic ED visits for individuals who have had 4 or more ed visits in the last 14 months. (Check this)
2. (Check from -17 to -14)

9/16/23:
We checked from 1/3/23 to 14 months back to see if all pts had 4 or more ed visits during this time period. That was not the case, so
our hypotheis was incorrect. Next time, we will try from the first ever visit to 14 months after. 
