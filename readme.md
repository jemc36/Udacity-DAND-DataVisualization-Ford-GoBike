# Data Visualization - Ford GoBike (Bike Shares)


## Dataset
The dataset, 2017-fordgobike-tripdata.csv, is downloaded from [Ford GoBike](https://s3.amazonaws.com/fordgobike-data/index.html) and licensed by [Ford GoBike](https://assets.fordgobike.com/data-license-agreement.html). This dataset includes 519,700 trips with 15 features such as locations, time, and user attributes. There are start and end stations. I noticed that most trips happen on the same stations, so I subset the dataset by choosing top 8 trips start stations with the most trips. Also, the program launched since June, 28th, 2017, so I remove June's data because of lack of insufficient data. Thus, the following analysis is performed by this subsetted dataset.


## Summary of Findings
1. Univariate exploration: the number of trips gradually decreases when the weather becomes colder. During the day, there are more trips in the morning and afternoon than the night. Also, there are more trips during the weekdays and less trips during the weekends. It makes sense that there are more subscribers than customers [pricing](https://www.fordgobike.com/pricing).
For the gender groups, the number of trips in male riders is 3 times more than the number of trips in females. It needs to be investigated more. Most of riders are 30 to 40 years old and the duration of trips is around 650 seconds.

2. Bivariate exploration: there is a slightly negative correlation between age and duration of trips. After separation the top 8 stations, half of stations have the most trips in the morning and another half of stations has the most trips in the afternoon. Weekdays have the most trips than weekends. In each month, besides July (the program just launched), from August to October, the number of trips gradually increases and it decreases in the winder (November and December). Biking is definitely correlated with the weather. It needs more weather forecast data to support the assumption.
3. Multivariate exploration: separating user types, customers and subscribers, gives more insights. Customers like to bike during the weekend and in the summer. Also, the number of trips increases in the tourist attractions like ferry building and Embarcadero. On the other hand, the trips in subscribers increase during the weekdays and after launching, the number of trips gradually increases and then decreases when the weather becomes colder. Moreover, customers ride longer than subscribers. Both of them have the longest trips at night and in December. I am guessing because of holiday seasons but not sure about why night trips are longer so still need more data to prove my point.

## Key Insights for Presentation  
The stations with the most trips are located in San Francisco and connect to public transportations including Caltrain, Bart and Ferry. User types play a key factor on the number of trips in each location and time group. For customers, there are more trips in the weekends and in August. They also have longer trips. On the other hand, for subscribers, there are more trips during the weekends and the number of trips is influenced by the climate change. Thus, collecting more information individually from these two user types is important for the future analysis.

## Review
* [Udacity Review 1](https://github.com/jemc36/Udacity-DAND-DataVisualization-Ford-GoBike/blob/master/Udacity%20Reviews%201.pdf)  
* [Udacity Review 2](https://github.com/jemc36/Udacity-DAND-DataVisualization-Ford-GoBike/blob/master/Udacity%20Reviews%202.pdf)   
