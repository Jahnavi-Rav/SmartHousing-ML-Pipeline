# SmartHousing-ML-Pipeline

# Project: Housing Price Predictor

## Project Description

This project demonstrates a complete **end-to-end machine learning pipeline** to predict housing prices in California based on various features such as geographical data, income levels, and housing attributes. The dataset is sourced from the **California Housing Dataset**, which includes important factors like median income, location, and house age. The primary objective is to train a machine learning model that accurately predicts **median house values**.

### Key Features:
- **Data Preprocessing**: Missing value imputation, feature scaling, and encoding categorical features.
- **Feature Engineering**: New features created based on the existing data (e.g., rooms per household, population per household).
- **Modeling**: Models like **Linear Regression**, **Decision Tree**, and **Random Forest** were trained and evaluated using cross-validation.
- **Hyperparameter Tuning**: Performed using **GridSearchCV** for the best model configuration.
- **Evaluation**: Root Mean Squared Error (RMSE) was used to assess the performance of models on the test set.

---

## Dataset

The dataset used in this project is a subset of the **California Housing Dataset**. It contains 20,640 rows and 10 columns, with attributes such as:
- `longitude` and `latitude`: Geographical coordinates.
- `housing_median_age`: Age of the house in years.
- `total_rooms`, `total_bedrooms`: Total number of rooms and bedrooms per block.
- `median_income`: Median income of households.
- `ocean_proximity`: Categorical attribute indicating the proximity to the ocean.
- `median_house_value`: The target variable (median house value).

---
