# Warframe Market Data Analysis

Warframe Market is an online platform where players can trade in-game items such as mods, prime parts, and other resources in the popular video game Warframe.
The Warframe Market Data Analysis project is designed to retrieve and analyze in-game item pricing information from the Warframe Market API. 

# Project Overview

The main goals of this project include:

## Data Retrieval 

Fetching item information from the Warframe Market API to understand the current state of the in-game market.

## Data Analysis

Utilizing linear regression, random forest and gradient boosting to predict the lowest price for the next day based on historical order data. This involves extracting, processing, and analyzing order information to provide insights into price trends.

Using linear regression as a baseline for comparison, I used random forest for its better predictive performance and robustness.
Subsequently, I used gradient boosting to correct the errors made by both predictive models, resulting in a more accurate ensemble known as a Gradient Boosted Random Forest.

## Evalutation Metric

To determine which predictive model is the most accurate, I used Mean Absolute Error (MAE) as a metric to assess the accuracy of my predictive models. 

MAE represents the mean of the absolute difference between the predicted values and the actual values. Thus a lower MAE indicates that the model's predictions are closer to the actual values.

## Output

Saving the analyzed data to an Excel file for further exploration and reference.

