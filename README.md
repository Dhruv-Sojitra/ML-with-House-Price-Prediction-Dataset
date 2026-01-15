# ML-with-House-Price-Prediction-Dataset
🏠 House Price Prediction using Machine Learning
📌 Project Overview

This project focuses on predicting house prices using machine learning techniques.
The goal is to analyze housing features, preprocess the data, and build a regression model that can accurately predict house prices.

The project uses XGBoost Regressor, a powerful gradient boosting algorithm, and evaluates model performance using R² Score and Mean Absolute Error (MAE).

📂 Dataset

Dataset Name: Housing Dataset

File: Housing.csv

Target Variable: price

Key Features

Area

Bedrooms

Bathrooms

Stories

Parking

Furnishing status

Amenities such as air conditioning, basement, guest room, etc.

🛠️ Technologies & Libraries Used

Python

Pandas

NumPy

Matplotlib

Seaborn

Scikit-learn

XGBoost

🔍 Project Workflow
1️⃣ Data Loading

Loaded the dataset using Pandas

Inspected shape, structure, and summary statistics

2️⃣ Data Exploration & Analysis

Checked for missing values

Generated descriptive statistics

Visualized correlations using a heatmap to understand feature relationships

3️⃣ Data Preprocessing

Encoded categorical variables

Removed unnecessary columns

Prepared feature matrix (X) and target vector (y)

Split data into training and testing sets

🤖 Model Building

Used XGBoost Regressor

Trained the model on training data

Evaluated performance on both training and test datasets

📊 Model Evaluation
Metrics Used

R² Score

Mean Absolute Error (MAE)

Observations

Training performance was very high, indicating strong learning

Test performance was lower, indicating overfitting

Regularization and hyperparameter tuning were applied to reduce overfitting

📈 Results
Dataset	R² Score	MAE
Training Data	~0.99	Low
Test Data	~0.59	~1,053,105

The gap between training and testing scores indicates overfitting, which is common with powerful models like XGBoost.

🚀 Improvements & Future Work

Hyperparameter tuning using GridSearchCV

Feature engineering

Log transformation of target variable

Cross-validation

Outlier handling

Trying alternative models (Random Forest, Gradient Boosting)

📌 Conclusion

This project demonstrates a complete machine learning pipeline for house price prediction.
While the model performs well on training data, further tuning is required to improve generalization on unseen data.
