These Datasets contain historical sales data for 45 Walmart stores located in different regions. Each store contains a number of departments, the task is predicting the department-wide sales for each store. In addition, Walmart runs several promotional markdown events throughout the year. These markdowns precede prominent holidays, the four largest of which are the Super Bowl, Labor Day, Thanksgiving, and Christmas. The weeks including these holidays are weighted five times higher in the evaluation than non-holiday weeks. Part of the challenge presented by this competition in Kaggle is modeling the effects of markdowns on these holiday weeks in the absence of complete/ideal historical data.


Questions explored in this data set:
•	Which Dept has the highest weekly sales?
•	Which store type has the highest weekly sales?
•	Are there Trends or seasonality in the time series?

EDA Findings:
- There's Definitely a surge in sales at the last 2 months of each year because of Thanksgiving and Christmas holidays

- The average sales per week are about 16K except for the November and december sales it surges to around 28K

- The Most common store type is type A, although there's an ambiguity around the type of variable but after searching the internet I suppose the most common is the super store as suggested by the plots of store size

-  Also Store A has the highest weekly sales on average
- This Data set is not stationary after plotting the autocorrelation plots
