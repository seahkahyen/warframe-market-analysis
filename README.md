# Warframe Market Data Analysis

Warframe Market is an online platform where players can trade in-game items such as mods, prime parts, and other resources in the popular video game Warframe.


My Warframe Market Data Analysis project is designed to retrieve item data from its API and use machine learning algorithms to analyze and predict future item prices.

# Project Overview

The main goals of this project include:

## Data Retrieval 

Fetching item information from the Warframe Market API to understand the current state of the in-game market.

## Data Analysis

Utilizing predictive models such as linear regression, random forest, gradient boost, ada boost and XGB to predict the lowest price for the next day based on historical order data. 

This involves extracting, processing, and analyzing order information to provide insights into price trends.

## Evalutation Metric

To determine which predictive model is the most accurate, I used Mean Absolute Error (MAE) as a metric to assess the accuracy of my predictive models. 

MAE represents the mean of the absolute difference between the predicted values and the actual values. Thus a lower MAE suggests that the model's predictions are closer to the actual values.

## Output

Saving the analyzed data to an Excel file for further exploration and reference.

