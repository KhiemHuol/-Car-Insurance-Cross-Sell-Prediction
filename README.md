Car Insurance Cross-Sell Prediction
Overview

This project was completed as part of BZAN 6357 – Final Group Project and focuses on predicting whether an existing medical insurance customer will purchase a cross-sold car insurance policy after being contacted by a sales representative.

The objective is to build a machine learning solution that can accurately identify high-probability customers, enabling more efficient and targeted marketing efforts.

Project Highlights
Comprehensive data quality assessment and validation
Exploratory Data Analysis (EDA) to identify key drivers of purchase behavior
Feature engineering using domain knowledge and data insights
Cross-validated target encoding for high-cardinality variables
Evaluation of multiple machine learning algorithms
Hyperparameter tuning using Grid Search and Cross Validation
Class imbalance handling through SMOTE, class weighting, and scale adjustment techniques
Threshold optimization using Precision-Recall analysis
Ensemble learning through soft voting and stacking
Weight optimization using Nelder-Mead optimization
Final prediction generation for an unseen score dataset

Models Evaluated

The project compares a wide range of machine learning approaches, including:

Logistic Regression
Random Forest
Gradient Boosting
HistGradientBoosting
Extra Trees
K-Nearest Neighbors
MLP Neural Network
PCA + MLP
XGBoost
LightGBM
CatBoost
Multiple Voting and Stacking Ensembles
