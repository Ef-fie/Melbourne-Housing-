# Melbourne Housing Price Prediction (First Regression Analysis)

## Project Overview
This project represents my first regression analysis using the Melbourne Housing dataset from Kaggle. The goal was to understand how models work and the basic workflow behind them. I started with building a Decision Tree.

The project focuses on learning how data preparation, model training, and validation affect prediction accuracy rather than producing a highly optimized model.

# Objectives
- Explore the Melbourne housing dataset
- Perform basic data cleaning
- Build a regression model to predict house prices
- Evaluate model performance using Mean Absolute Error (MAE)
- Understand the impact of data splitting on model evaluation

# Dataset
The dataset was obtained from Kaggle and contains information on house sales in Melbourne, including property characteristics and prices.

For simplicity, rows with missing values were removed instead of applying advanced data cleaning.

# Methodology
- Removed rows containing missing values
- Selected house price as the target variable
- Chose relevant features as predictors eg rooms
- Built a Decision Tree Regression model
- Initially trained the model on the full dataset
- Later split the data into training and validation sets to improve model evaluation
- Compared MAE results before and after data splitting

# Model Summary
- Model used: Decision Tree Regressor
- Evaluation metric: Mean Absolute Error (MAE)
- The model showed improved MAE after splitting the data, highlighting the importance of proper model validation

# Key Learnings
- Training and evaluating a model on the same dataset can lead to misleading performance results
- Splitting data into training and validation sets provides a more realistic estimate of model accuracy
- Even simple data preparation steps significantly affect model performance

# Limitations
- Data cleaning was minimal
- No feature engineering was performed
- Model was not tuned
- More advanced validation techniques were not applied

# Future Improvements
- Apply proper data cleaning and handling of missing values
- Perform feature engineering and selection
- Tune model 
- Experiment with other regression models
- Use cross-validation for more robust evaluation

## Files in This Repository
- `melbourne_housing_regression.ipynb` – Jupyter Notebook containing data preparation, modeling, and evaluation
