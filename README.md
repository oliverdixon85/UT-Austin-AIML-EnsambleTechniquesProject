# Problem statement
We have data from a Portuguese bank on details of customers related to selling a term deposit The objective of the project is to help the marketing team identify potential customers who are relatively more likely to subscribe to the term deposit and this increase the hit ratio

Data dictionary
Bank client data

1 - age
2 - job : type of job
3 - marital : marital status
4 - education
5 - default: has credit in default?
6 - housing: has housing loan?
7 - loan: has personal loan?
8 - balance in account
Related to previous contact

8 - contact: contact communication type
9 - month: last contact month of year
10 - day: last contact day of the month
11 - duration: last contact duration, in seconds*
Other attributes

12 - campaign: number of contacts performed during this campaign and for this client
13 - pdays: number of days that passed by after the client was last contacted from a previous campaign
14 - previous: number of contacts performed before this campaign and for this client
15 - poutcome: outcome of the previous marketing campaign

Achieved 
Bagging Acc	0.889929 Recall 0.241851
Gradient Boost Acc	0.894279 Recall	0.212516

Poor recall results
