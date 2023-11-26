# XGBoost on a Housing Dataset

# Context

In this project, I use XGBoost, a powerful machine learning library, to predict real estate prices. The goal is to build a predictive model, evaluating the performance and tuning hyperparameters for optimal results.

# Content

## Data Pre-processing

### Encoding Categorical Columns

Categorical columns are encoded to facilitate model training by converting them into a numerical format.

### Handling Missing Values

The project addresses missing values in the dataset through appropriate strategies to ensure data integrity.

# Building the Model

## DMatrix

The DMatrix object is used to efficiently handle the dataset, optimizing it for XGBoost.

## Splitting the Data

The dataset is divided into training and testing sets to assess the model's performance accurately.

## Model Setting / Parameters

This section covers the configuration of model settings and parameters to achieve the desired outcome.

# Testing Model's Performance

## Computing MAE

Mean Absolute Error (MAE) is computed to quantify the model's prediction accuracy.

## Hyperparameters Tuning using HYPEROPT

The project explores hyperparameter tuning using the HYPEROPT library to enhance the model's performance.

## K-fold Cross Validation

K-fold Cross Validation is employed to assess the model's robustness and generalization across different subsets of the data.

## Feature Importance

An analysis of feature importance is conducted to understand the variables that significantly impact the model's predictions.
