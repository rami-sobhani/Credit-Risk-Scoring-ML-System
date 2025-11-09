# Credit-Risk-Scoring-ML-System
This project details the development of a production-ready Credit Risk Scoring System implemented through a highly structured Scikit-learn Pipeline, leveraging the power of XGBoost for classification. The core of the solution is focused on robust feature engineering, model optimization, and post-modeling interpretability.

Up until now I used got my data for in csv file format with columns of different features such as trade lines opened, derogatory accounts, balance of total trade lines, etc. with target variable of weather customer defaulted or not (1 or 0).

Created pipelines to clean, scale, preprocess the data. Split the data to training, validation, and testing sets.

Used two ML models (Logistic Regression and XGBoost) comparing both using AUC as the metric. Chose the better performing model (it was XGBoost but not by much)

Next steps: trying to figure out how to get better results using a different ML model or different parameters for XGBoost and trying to use SHAP to understand which features affect the target variable decisions.
