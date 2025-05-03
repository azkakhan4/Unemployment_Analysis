# Unemployment in India Analysis

## Problem Statement
The goal of this project is to analyze and predict unemployment trends in India. The project aims to understand the factors contributing to unemployment in India and to build a model that can predict future unemployment rates. The dataset includes features such as age, education level, industry, and more.

## About the Dataset
The dataset used for this project contains historical data on unemployment rates in India, including various factors that influence unemployment, such as educational qualifications, industry sectors, and region-wise statistics.

### Dataset Information:
- **Source**: Kaggle (Unemployment Dataset)
- **Rows**: 2000+
- **Columns**: 10+

### Features:
The dataset consists of the following columns:
- **Age**: The age group of the individual (numeric).
- **Education Level**: The highest level of education (categorical: 'High School', 'Undergraduate', 'Postgraduate').
- **Industry**: The industry in which the individual is employed (categorical).
- **Region**: The region of India (categorical: 'North', 'South', 'East', 'West').
- **Experience**: Years of experience (numeric).
- **Unemployment Rate**: The rate of unemployment in that region (target variable).

## Why This Dataset?
This dataset is suitable for building a model to predict unemployment trends because it includes demographic, educational, and regional features, all of which are important in analyzing and predicting unemployment.

### Benefits of this dataset:
- The dataset includes various socio-economic factors that influence unemployment rates.
- It allows for testing predictive models for a real-world socio-economic issue.

## Model
The model used for this project is a **Linear Regression** model which is commonly used for predicting continuous variables such as unemployment rates.

### Steps Taken:

1. **Data Preprocessing**:
    - Handled missing values, if any.
    - Encoded categorical features like education level, industry, and region.

2. **Model Training**:
    - Trained the model using the preprocessed dataset.

3. **Model Evaluation**:
    - Evaluated the model’s performance using **Mean Absolute Error (MAE)** and **R-squared**.

4. **Model Saving**:
    - The trained model was saved as a pickle file (`model.pkl`) for future predictions.

## About
A machine learning project to analyze and predict unemployment trends in India using **Linear Regression** or **Random Forest**. The project helps in understanding the socio-economic factors influencing unemployment.

## Topics
- python
- machine-learning
- regression
- socio-economic analysis

## Resources
- Kaggle (Unemployment Dataset)
- Scikit-learn (Linear Regression, Random Forest)
