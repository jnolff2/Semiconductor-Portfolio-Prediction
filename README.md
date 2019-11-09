# Stock-Price-Prediction
Project Synopsis 

To understand the stock behavior and determine if there is correlation, we determined the z scores. To calculate, we used the yfinance library to access stock data to show volume, opening and closing price, and the high and lows. We chose to highlight Facebook, Microsoft, Amazon, Google, and Apple stock prices for our project. 

The transforming of the data was integral, we grouped by the percent change for the next day, next week, 2 weeks, and 1 months returns. The output (outcome) from the percent change came after normalizing the data to ensure we get fair comparisons between features of differing scale. (these are the factors) We visualize this correlation from the features that was binned from said factors. 

When running the linear regression shows a Rsquared of >0.25 and approximately equal coefficients for each of the features, suggesting that they're all contributing strongly to the model. When going through the analysis we learned that we have to split the data for both prediction and testing. We split our data from Jan 1, 2014 to Jan 1, 2018 and tested from the beginning of 2019 (Jan 1) to Nov. 8, 2019.

The 5-Day-Prediction folder contains an image of our model's direction price prediction based on the closing price of the date in the image.  The number is predicting the directional movement of the stock price from the closing price of that day to the closing price 5 days in the future.  A positive number indicates the user should go long that stock and a negative number indicates the user should short the stock.

The Recent-Performance-Breakdown folder contains an image that shows some custom performance metrics we used to measure our portfolio.  It includes the accuracy of our predictions, the average weekly percentage returns if the predictions were acted on, a breakdown of long vs. short prediction performance, etc.
