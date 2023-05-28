# Bike Sharing Predictions

## Goal
Train a model to predict bike sharing demand. 

## Data
Competition: https://www.kaggle.com/competitions/bike-sharing-demand/overview

## Result
Best submission on Kaggle: RMSLE = 0.41928 (around #400)

- RandomForestRegressor
- log transformation to reduce outlier influence
- target = casual + registered
- Hyperparameter Optimization