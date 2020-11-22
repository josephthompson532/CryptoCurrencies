# CryptoCurrencies

## Purpose
The purpose of this project was to create a report that includes what cryptocurrencies are on the trading market and how they could be grouped to create a classification system.

### Overview
To begin, I filtered the data so it only included those cryptocurrencies that are currently being traded. Then I created two dataframes that would hold the coin names and index for later use.

Then I created dummy variables from the categorical data and scaled the data. Given the high number of dimensions I used PCA to convert the features to three principal components.

I used an elbow curve to find the best value for K. The graph made a sharp horizontal turn at 4 and was thus chosen. After predicting the labels and merging them with the original dataframe, I then set out to visualizing the clusters.

I used plotly to render a 3-dimenensional scatter plot off the 3 principal components with class represented by shape and color.

Lastly I created a plot using hvplot to visualize the total coins mined against the total coin supply.
