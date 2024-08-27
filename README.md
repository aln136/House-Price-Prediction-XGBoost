# House Price Prediction Competition
Link: https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques

## Overview

This repository contains a Kaggle notebook for the "House Prices - Advanced Regression Techniques" competition. The notebook focuses on preprocessing data, training an XGBoost regression model, and evaluating its performance using cross-validation.

## Objectives

- **Preprocess Data:** Handle missing values using various imputing strategies and scale data.
- **Feature Selection:** Drop numerical columns with low correlation to the target and columns with more than 50% missing values.
- **Model Training:** Train an XGBoost model (using numerical values for simplicity).
- **Evaluation:** Assess model performance using Root Mean Squared Log Error (RMSLE).

## Process

1. **Data Preparation:** 
   - Dropped columns with low correlation to "SalePrice".
   - Removed columns with more than 50% missing data.
   - Imputed missing values using various strategies.

2. **Feature Engineering:**
   - Scaled numerical features.

3. **Modeling:**
   - Trained XGBoost model for regression.
   - Evaluated model using cross-validation.

4. **Submission:**
   - Generated predictions for the test dataset and achieve a score of 0.15873
