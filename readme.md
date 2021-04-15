# Data Visualization - Ford GoBike (Bike Shares)


## Dataset
The dataset, 2017-fordgobike-tripdata.csv, is downloaded from Ford GoBike and licensed by Ford GoBike. This dataset includes 519,700 trips with 15 features such as locations, time, and user attributes. There are start and end stations. I noticed that most trips happen on the same stations, so I subset the dataset by choosing the top 8 trip start stations with the most trips. Also, the program launched on June 28th, 2017, so I remove June's data because of the lack of insufficient data. Thus, the following analysis is performed by this subsetted dataset.


## Summary of Findings
1. Univariate exploration: the number of trips gradually decreases when the weather becomes colder. During the day, there are more trips in the morning and afternoon than the night. Also, there are more trips during the weekdays and fewer trips during the weekends. It makes sense that there are more subscribers than customers [pricing](https://www.fordgobike.com/pricing).
For the gender groups, the number of trips in male riders is three times more than the number of female trips. It needs to be investigated more. Most riders are 30 to 40 years old, and the duration of trips is around 650 seconds.

2. Bivariate exploration: there is a slightly negative correlation between age and duration of trips. After separation, the top 8 stations, half of the stations have the most trips in the morning, and another half of stations have the most trips in the afternoon. Weekdays have the most trips than weekends. In each month, besides July (the program just launched), the number of trips gradually increases from August to October, and it decreases in the winter (November and December). Biking is definitely correlated with the weather. It needs more weather forecast data to support the assumption.
3. Multivariate exploration: separating user types, customers, and subscribers, gives more insights. Customers like to bike during the weekend and in the summer. Also, the number of trips increases in the tourist attractions like ferry building and Embarcadero. On the other hand, the subscribers' trips increase during the weekdays, and after launching, the number of trips gradually increases and decreases when the weather becomes colder. Moreover, customers ride longer than subscribers. Both of them have the most extended trips at night and in December. I  guess because of the holiday seasons, but not sure why night trips are longer. I still need more data to prove my point.

## Key Insights for Presentation  
Most trips are located in San Francisco and connect to public transportations, including Caltrain, Bart, and Ferry. User types play a crucial factor in the number of trips in each location and time group. For customers, there are more trips on the weekends and in August. They also have more extended trips. On the other hand, there are more trips during the weekends for subscribers, and climate change influences the number of trips. Thus, collecting more information individually from these two user types is essential for future analysis.

## Review
* [Udacity Review 1](https://github.com/jemc36/Udacity-DAND-DataVisualization-Ford-GoBike/blob/master/Udacity%20Reviews%201.pdf)  
* [Udacity Review 2](https://github.com/jemc36/Udacity-DAND-DataVisualization-Ford-GoBike/blob/master/Udacity%20Reviews%202.pdf)   
