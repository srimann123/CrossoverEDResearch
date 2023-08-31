### System Design

Defining frequent ED users: 

The definition of frequent emergency department users varies throughout the literature, ranging from 3 ED visits to 7 visits annually. The most common threshold, however, is 4 visits annually. Although somewhat arbitrary, this classification is relevant for understanding the nuances behind extreme emergency department utilization in different patient populations. 

Ultimately, we decided to categorize frequent users as patients who utilized ED services 4 or more times in a 14-month period, closely adhering to the traditional definition while accounting for population-specific variance in frequent ED use by Crossover Health patients. This approach allows for a larger number of patients to be included in the frequent ED user group, resulting in a richer dataset.

System Inputs and Outputs:

Outputs: A binary indicator where 1 represents that the input translates to a frequent ED user and 0 translates to an infrequent user.

