# House Price Prediction using Machine Learning

## Overview

This project focuses on predicting house prices using Machine Learning techniques on the Ames Housing Dataset. The project includes complete Exploratory Data Analysis (EDA), Feature Engineering, Feature Selection, and Model Training to identify the most important factors affecting house prices.

## Problem Statement

The goal of this project is to predict the selling price of residential houses based on various property features such as location, overall quality, living area, garage capacity, basement size, and other housing attributes.

## Dataset

Dataset: Ames Housing Dataset

The dataset contains 79 explanatory variables describing different aspects of residential homes.

Target Variable:

- SalePrice

## Project Workflow

### 1. Exploratory Data Analysis (EDA)

- Dataset understanding
- Missing value analysis
- Feature distribution analysis
- Correlation analysis
- Data visualization

### 2. Feature Engineering

- Missing value handling
- Temporal feature transformation
- Rare category handling
- Feature scaling
- Data preprocessing

### 3. Feature Selection

Lasso Regression was used for feature selection to identify the most important features and remove less relevant variables.

Results:

- Total Features: 82
- Selected Features: 21

Selected features include:

- MSSubClass
- MSZoning
- Neighborhood
- OverallQual
- YearRemodAdd
- RoofStyle
- BsmtQual
- BsmtExposure
- HeatingQC
- CentralAir
- 1stFlrSF
- GrLivArea
- BsmtFullBath
- KitchenQual
- Fireplaces
- FireplaceQu
- GarageType
- GarageFinish
- GarageCars
- PavedDrive
- SaleCondition

### 4. Model Training

- Lasso Regression
- Feature Selection Pipeline
- Data Standardization

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn
- Jupyter Notebook

## Files

- Exploratory Data Analysis.ipynb
- Feature Engineering.ipynb
- Model Fit & Feature Selection.ipynb
- train.csv
- test.csv
- X_train.csv

## Key Learnings

- Data Cleaning
- Missing Value Handling
- Feature Engineering
- Feature Selection
- Regression Models
- Machine Learning Workflow

## Future Improvements

- Build a Streamlit Web Application
- Deploy the model online
- Compare multiple regression algorithms
- Improve prediction accuracy through hyperparameter tuning

## Author

Sathvika Ajmeera

GitHub:
https://github.com/sathvika234567
