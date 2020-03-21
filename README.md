# Project Data Science Blog Post

This project explores data from the Seattle dataset from Airbnb, retrieved from: https://www.kaggle.com/airbnb/seattle/data
The goal is to highlight and answer three relevant questions that might be relevant for business purposes.

1) What is the trend of Airbnb listings and visitors?
2) Do price per night and availability of listings show seasonality effects?
3) What's driving listing prices and how can we predict the price for our appartment?

## Data
The following Airbnb activity is included in this Seattle dataset:

* listings.csv, including full descriptions and average review score
* reviews.csv, including unique id for each reviewer and detailed comments
* calendar.csv, including listing id and the price and availability for that day

## Libraries used
* pandas  
* numpy
* datetime
* matplotlibtatsmodels
* sklearn

## Results
In summary, the project shows that between 2009 and 2016 the number of listings and visitors significantly increased.
The number of new listings and visitors shows strong seasonality as more people are visiting Seattle in Summer than in Winter.
This also has an effect on the average price per night which generally highest around August.
Lastly, I trained a linear regression model to see what drives prices (other than the season) and to be able to predict prices for new listing.
The results showed that type, size and location of the listing are the most relevant factors to determine the price. 
