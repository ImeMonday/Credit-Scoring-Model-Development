Credit Scoring Model Development

Predicting Credit Card Default Using Machine Learning

Project Overview

This project builds a complete credit scoring model that predicts whether a customer will default on their credit card payment next month. The workflow includes data cleaning, exploratory analysis, feature engineering, model training, evaluation and interpretation.
Dataset

Default of Credit Card Clients
UCI Machine Learning Repository
Frame contains demographic data, credit limits, historical bill amounts, and payment behavior.

Objective

Build a validated credit scoring model using both statistical and machine learning techniques.
Compare model performance.
Explain which variables drive credit risk.
 1. Data Preparation

Loaded dataset and removed the ID column.
Converted category features to numeric codes.
Scaled numerical features for Logistic Regression.
Checked class imbalance and applied class weighting.
2. Exploratory Data Analysis

Identified a default rate of about twenty two percent.
Observed that recent payment status is the strongest risk driver.
Higher bill amounts indicate higher financial stress.
Younger borrowers show higher risk patterns.

3. Feature Engineering

Created numerical mappings for repayment status.
Ensured all features were numeric and ready for modeling.
Split the dataset into training and testing sets.

4. Models Trained

Logistic Regression for baseline and interpretability.
XGBoost for higher predictive performance.
XGBoost used tuned depth, number of trees, learning rate, subsampling and column sampling.
 5. Model Evaluation

Metrics calculated
Accuracy
Precision
Recall
F1 Score
ROC AUC

XGBoost achieved the strongest performance overall and significantly improved ROC AUC compared to Logistic Regression.

6. Feature Importance Insights

Top predictors from XGBoost
Most recent payment status
Previous payment behavior across six months
Outstanding bill amounts
Credit limit
Age group

Most delinquency related features showed the greatest predictive power.
These factors match real world credit risk patterns.
 Deliverables

Clean processed dataset.
Full Google Colab workflow.
Trained Logistic Regression model.
Trained XGBoost model.
Evaluation table comparing both models.
Feature importance chart.
Business interpretation of risk drivers.
Final credit scoring report.
 Conclusion
The project delivers a complete industry style credit scoring pipeline.
Models are trained, validated and interpreted.
XGBoost is recommended for deployment due to superior discrimination power.
The workflow is reproducible and ready for portfolio presentation.

