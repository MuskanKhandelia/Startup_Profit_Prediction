# Startup Profit Prediction

This repository contains code for building a multiple linear regression model to predict startup profit based on various parameters such as R&D Spend, Administration Spend, Marketing Spend, and the State from which the data is collected.

## Overview

The goal of this project is to create an effective model for predicting startup profit by analyzing and understanding the relationships between different features. The dataset includes information on R&D Spend, Administration Spend, Marketing Spend, and the State of the startups.

## Key Features

- **R&D Spend:** Research and development spending in the past few years.
- **Administration:** Spending on administration in the past few years.
- **Marketing Spend:** Spending on marketing in the past few years.
- **State:** States from which data is collected.

## Model Performance

After performing data cleaning, analysis, and visualization, it was observed that all three columns (R&D Spend, Marketing Spend, Administration) have a direct relationship with the profit, which is the target variable. The correlation analysis showed that R&D Spend is highly correlated, Marketing Spend is moderately correlated, and Administration is least correlated.

To handle the categorical variable (State), one-hot encoding was applied to convert it into numerical form.

The model achieved an R2 score of 0.97 for training data and 0.91 for testing data, indicating strong predictive performance.
