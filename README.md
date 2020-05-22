# Predict-SellingPrice-of-Used-Car

# Dataset:
Craigslist UsedCars Data
Data Set was found here: https://www.kaggle.com/austinreese/craigslist-carstrucks-data 

Download "vehicles.csv" file from this link.

# Description
In this project, Cleaning the data first, Preprocessing data,Exploratory Data Analysis of missing data, Visualizing the data and predicting the selling price of a used car based on reported trends.

# Goal
Observing the different patterns of how selling price of cars is dependent on various features and predicting the price of used cars using Supervised Machine Learning Models with Scikit Learn Library and Pyspark ML Library.
In this Project we are using different Supervised Regression Models to predict the price.

# Observations
In the original data when we performed EDA we found there are few columns which are not contributing towards price prediction so we dropped them. There is also significant amount of Missing values in few columns, we approached the problem in two ways
* Dropped all the missing values from the data.
* Filled the missing data in categorical columns with ‘Unknown’ category and numerical columns with mean values.

# Libraries Used: Scikit Learn, Pyspark ML , plotly
Plotly Installation pip command: pip install plotly==4.7.1
