# Be-an-Airbnb-host-in-Seattle
If you are considering being a host in Seattle, you must know about the market. What kinds of property provided in Seattle? How to get more review scores? How to price your place?

According to the data from Airbnb in 2016 to 2017, we can find the insight from the data and know more about the trend of traveler preference in Seattle.

#### Four questions will find out in this project: 
1. Which is the most popular season to visit Seattle?
2. What is the most type of property provided in Seattle? And Which property has topped review score?
3. How’s the correlation with the accommodation, review scores, and price?
4. What reason might affect the review score from the customers?

#### The approach:
Some visualization and statistic methods will be provided to answer the questions. 
A linear regression model is also estiblished to predict the review scores from the guests. 
The main libraries used in this project is [pandas](https://pandas.pydata.org/pandas-docs/version/0.15/tutorials.html) and [sklearn](https://scikit-learn.org/stable/). 

#### File description:
There are two csv data in data file:
- [calendar.csv](https://www.kaggle.com/airbnb/seattle?select=calendar.csv): It is included listing id and the price and availability for that day
- [Listings.csv](https://www.kaggle.com/airbnb/seattle?select=listings.csv): It is inclused full descriptions and average review score for each host.

#### Results:
Based on this analysis, we can figure out a few insights:
- The busiest visiting season is summer.
- The most type of property provided in Seattle is House.
- The highest review score of the property is Yurt.
- The accommodates and bedrooms have a positive correlation with price.
- The type of property and whether the super host or not have stronger relationships with review scores.

You can view more details on my [Medium](https://medium.com/@chris.liou007/be-an-airbnb-host-in-seattle-f36ebc621388)

#### Reference:
Data source from [Kaggle](https://www.kaggle.com/airbnb/seattle/data)
