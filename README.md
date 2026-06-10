# machine-learning-buy-box-winner
A Machine Learning Approach to Predict the Buy Box Winner
Overview
This project was developed as part of my Master's degree in Big Data Analytics and Management at Bahçeşehir University.
The objective of this study was to predict Buy Box winners in e-commerce marketplaces using machine learning techniques and identify the factors that most influence Buy Box selection. The project evaluates multiple regression algorithms and ensemble learning methods to improve prediction accuracy.

Dataset

The dataset consists of 50,000 records and 21 features collected from major e-commerce platforms.
Key features include:
Product price
Seller ratings
Shipping options
Site reference
Merchant-related attributes
Note: The original dataset is not publicly available due to confidentiality and data privacy considerations.

Methodology

The project followed the following workflow:
Data collection
Data cleaning and preprocessing
Label encoding of categorical variables
Exploratory Data Analysis (EDA)
Feature selection
Model training and evaluation
Ensemble learning
The dataset was divided into training (80%) and testing (20%) sets for model evaluation.
Machine Learning Models

The following models were implemented and compared:

Linear Regression
Random Forest Regressor
Extra Trees Regressor
XGBoost Regressor
CatBoost Regressor
HistGradientBoosting Regressor
LightGBM Regressor
Gradient Boosting Regressor
Stacking Regressor
Evaluation Metrics
Model performance was evaluated using:
Mean Absolute Error (MAE)
Mean Squared Error (MSE)
Root Mean Squared Error (RMSE)
Training Time

Key Findings

Product pricing was one of the most influential factors affecting Buy Box outcomes.
Free shipping showed a positive impact on Buy Box ranking.
Ensemble learning improved prediction performance.
Stacking Regressor achieved the strongest overall prediction results.
Extra Trees Regressor demonstrated excellent accuracy with efficient training time.
Technologies Used
Python
Pandas
NumPy
Scikit-learn
XGBoost
CatBoost
LightGBM
Matplotlib

Author

Bayan Hasan Al-Anani

Master's Degree in Big Data Analytics and Management

Bahçeşehir University

