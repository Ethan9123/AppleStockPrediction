# AppleStockPrediction
------
The data source is the Apple Stock data from yahoo finance.

Firstly, used the matplotlib to draw the lineplot for stock close price from 2018-9-10 to 2019-9-10.

Extracted three date metrics- day of the week, day of the month, and month from the date column

Utilized past stock price data to generate extra three metrics
  - how many days of stock price increasing
  - how many days of stock price decreasing
  - the gap between average stock price and the stock price of the day before

Split the data into training set and testing set

Used Linear Regression, quadratic regression, and KNN to make prediction for the last 50 days
