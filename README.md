# Airbnb Price Prediction

## Overview
This project aims to predict the price of Airbnb listings in New York City using various features from the Airbnb dataset. The project leverages machine learning models to help hosts set competitive prices for their listings and to better understand the factors influencing rental costs.

## Project Structure

- **Data Source**: The project uses the Airbnb NYC dataset, which contains information about various listings, including features like accommodates, room type, number of bedrooms, and reviews.

- **Objective**: Develop a machine learning model to predict the price of Airbnb listings based on key features.

- **Models Implemented**:
  - **Linear Regression**: A simple linear approach to predict prices.
  - **Random Forest Regressor**: An ensemble model that improves prediction accuracy through decision trees.

## Key Features

- **Data Preparation**: 
  - Handled missing data and outliers.
  - Applied one-hot encoding for categorical variables.
  - Selected relevant features such as accommodates, room type, bathrooms, bedrooms, and beds.

- **Modeling**: 
  - Trained and tested two models: Linear Regression and Random Forest.
  - Evaluated model performance using RMSE and R² metrics.
  
- **Evaluation Results**:
  - **Random Forest**: RMSE of 0.7920 and R² score of 0.4058.
  - **Linear Regression**: RMSE of 0.8295 and R² score of 0.3482.


Conclusion: 
In this analysis, I developed and evaluated Linear Regression (LR) and Random Forest (RF) models to predict Airbnb listing prices. The Random Forest model performed better, with an RMSE of 0.7920 and an R² of 0.4058, compared to the Linear Regression model's RMSE of 0.8295 and R² of 0.3482. While the Random Forest model showed improved accuracy, the relatively low R² scores suggest that there is room for further enhancement through additional feature engineering and model refinement.
