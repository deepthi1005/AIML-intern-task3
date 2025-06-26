# AIML-intern-task3
This repository contains a simple yet complete project demonstrating how to build and evaluate a Linear Regression model using the Housing dataset. The model is trained to predict house prices based on various features like area, number of bedrooms, presence of amenities, and more.

The dataset used is Housing.csv, which contains information about different housing attributes and their corresponding prices.

# Project Workflow
Import and Explore Data
Load and view the first few rows of the dataset.
1. Preprocess Dataset
2. One-hot encoding for categorical variables
3. Drop first dummy column to avoid multicollinearity
4.Train-Test Split:80% of data for training, 20% for testing.
5.Train Linear Regression Model:Using sklearn.linear_model.LinearRegression.
5. Model Evaluation: Mean Absolute Error (MAE),Mean Squared Error (MSE),R² Score
6. Visualization: Scatter plot of actual house prices vs. area,Regression line fit using area as the sole feature (for interpretation),Interpret Coefficients,Display the effect of each feature on price prediction.
# Results
The model provides a reasonable fit for the dataset:
1. R² score around 0.65
2. Visualization shows a clear linear relationship between area and price.
