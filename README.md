Math482 - Assignment 3: Kaggle Competition - Predicting Road Accident Risk

This project was completed as part of Boğaziçi University’s Math482 course.
The goal is to solve a regression problem in the real Kaggle competition Predicting Road Accident Risk and to experience the end-to-end process of a machine learning project.

Objective:

The purpose of this assignment is to guide students through a complete machine learning pipeline, including:
Understanding and analyzing tabular data (EDA)
Data preprocessing and feature engineering
Training and comparing multiple models
Implementing validation strategies and interpreting results

Project Workflow

1) Exploratory Data Analysis (EDA)
Identified numerical and categorical variables.
Examined the distribution of the target variable accident_risk using histograms and boxplots.
Explored relationships between features such as weather, time_of_day, and the target variable.
 
2)Data Preprocessing
Missing values were handled with appropriate imputation strategies.
Categorical features were encoded using pd.get_dummies() and OneHotEncoder.
Unnecessary columns were dropped and numerical features were normalized.
 
3)Feature Engineering
At least two new, meaningful features were created.
Their impact on model performance was evaluated.

4)Modeling
Three different regression models were trained and compared.

5)Validation Strategy
Used train_test_split to hold out 20% of the data for validation.
All models were trained and evaluated on the same split for fair comparison.
Performance was measured using Root Mean Squared Error (RMSE), consistent with Kaggle’s competition metric.

6) Model Comparison and Final Model
Simpler models like Linear Regression underperformed due to data complexity.
Ensemble models, especially LightGBM, achieved significantly lower RMSE.
feature_importances_ plots were used to analyze the most influential features.
