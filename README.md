# King County House Price Prediction Analysis

*Disclaimer: This repository contains the Final Assignment notebook for the "Analyzing Data with Python" course, part of the IBM Data Science Professional Certificate*

## 🎯 Project Goal
This project aims to analyze and predict the market price of residential real estate in King County (including Seattle) using various house features such as square footage, number of bedrooms, number of floors, and so on.

## 📊 Dataset Overview
The dataset includes house sale prices for homes sold in King County between May 2014 and May 2015. It was sourced from public data (https://www.kaggle.com/datasets/harlfoxem/housesalesprediction) and slightly modified for this analysis.

## 🛠️ Modules & Methodology
The analysis followed a standard data science pipeline:
- Module 1: Importing Data
- Module 2: Data Wrangling (Cleaning, transformation, and preparation)
- Module 3: Exploratory Data Analysis (EDA) (Visualizing relationships between features and the target variable, 'price')
- Module 4: Model Development (Building various Linear Regression and Pipeline models)
- Module 5: Model Evaluation and Refinement (Testing model performance using Ridge Regression)

## ⭐ Result: Best Model Recommendation

Based on the Model Development and Evaluation phases, the **Polynomial Regression Pipeline** demonstrated the highest performance in explaining the variance in house prices. The Polynomial Regression Pipeline Model (involving StandardScaler(), PolynomialFeatures(degree=2), and LinearRegression()) is the best model to use for prediction, achieving an $R^2$ score of 0.7512. This means the model explains approximately 75.12% of the variability in King County house prices, making it a robust starting point for the Real Estate Investment Trust's analysis.
