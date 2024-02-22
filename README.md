                                                       Housing Prices Prediction Project
This project aims to predict the sales prices of residential homes in Ames, Iowa, using the Ames Housing dataset provided by Dean De Cock for data science education. The goal is to develop a predictive model that accurately estimates the final price of each house based on various explanatory variables.

Data Source:
Dataset: Ames Housing dataset
Source: Kaggle

Goal:
The goal of this project is to predict the sales price for each house. For each Id in the test set, the task is to predict the value of the SalePrice variable.

Metric:
Submissions are evaluated on Root-Mean-Squared-Error (RMSE) between the logarithm of the predicted value and the logarithm of the observed sales price. Taking logs means that errors in predicting expensive houses and cheap houses will affect the result equally.

Model Used:
Logistic Regression

Steps:
Data Preprocessing: Cleaned the dataset by handling missing values, encoding categorical variables, and scaling numerical features.

Feature Engineering: Created new features and transformed existing ones to capture meaningful information.

Model Training: Implemented Logistic Regression model using scikit-learn library.

Model Evaluation: Evaluated the model performance using Root-Mean-Squared-Error (RMSE) metric.

Dependencies:
Python 3.x
NumPy
pandas
scikit-learn
matplotlib
seaborn
