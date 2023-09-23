### System Design

Defining frequent ED users: 

The definition of frequent emergency department users varies throughout the literature, ranging from 3 ED visits to 7 visits annually. The most common threshold, however, is 4 visits annually. Although somewhat arbitrary, this classification is relevant for understanding the nuances behind extreme emergency department utilization in different patient populations. 

Ultimately, we decided to categorize frequent users as patients who utilized ED services 4 or more times in a 14-month period, closely adhering to the traditional definition while accounting for population-specific variance in frequent ED use by Crossover Health patients. This approach allows for a larger number of patients to be included in the frequent ED user group, resulting in a richer dataset.

System Inputs and Outputs:

Outputs: A binary indicator where 1 represents that the input translates to a frequent ED user and 0 translates to an infrequent user.

1. Who is a frequent user and who is not a frequent user, according to the current data sheets?

In any 14 month period of a patient's timeline, have they been to the ED 4 or more times? (THIS)
In the first 14 month period from the first ever ED occurrence? (Not this, not a standard time)
In the last 14 month period, ending on the last ever ED occurrence of present date? (Not this, not a standard time)

2. How do we want to classify freqeuent users and non-frequent users? We may reorganize our data, accordingly.
