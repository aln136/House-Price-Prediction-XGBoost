# House Price Prediction Competition
Link: https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques

## Overview

This repository contains a Kaggle notebook for the "House Prices - Advanced Regression Techniques" competition. The notebook focuses on preprocessing data, training an XGBoost regression model, and evaluating its performance using cross-validation.

## Objectives

- **Preprocess Data:** Handle missing values using various imputing strategies and scale data.
- **Feature Selection:** Drop columns that provided little value to model.
- **Model Training:** Train an XGBoost model with the most optimal hyperparameters
- **Evaluation:** Assess model performance using Root Mean Squared Log Error (RMSLE).

## Process

1. **Data Preparation:**
   - Visualized data using a heatmap and boxplots.
   - Dropped columns with a low correlation to "SalePrice".
   - Removed columns with more than 50% missing data.
   - Imputed missing values using mode for categorical and median for numerical data.

3. **Feature Engineering:**
   - Applied ordinal encoding to ordinal features and one-hot encoding to nominal features
   - Scaled numerical features.

4. **Modeling:**
   - Trained XGBoost model with hyperparameter tuning.
   - Evaluated model using cross-validation.

5. **Submission:**
   - Generated predictions for the test dataset and placed in the top 25% in the competition.
