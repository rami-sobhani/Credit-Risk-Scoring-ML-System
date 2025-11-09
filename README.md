# Credit-Risk-Scoring-ML-System
This project details the development of a production-ready Credit Risk Scoring System implemented through a highly structured Scikit-learn Pipeline, leveraging the power of XGBoost for classification. The core of the solution is focused on robust feature engineering, model optimization, and post-modeling interpretability.

Up until now I used a csv file with columns of different features such as trade lines opened, derogatory accounts, balance of total trade lines, etc. with target variable of weather customer defaulted or not (1 or 0).

I then create pipelines to clean, scale, preprocess the data. Split the data to training, validation, and testing sets.

Then I used two ML models (Logistic Regression and XGBoost) comparing both using AUC as the metric. I chose the better performing model (it was XGBoost but not by much)

I am trying to figure out how I could get better results using a different ML model or different parameters for XGBoost. Also trying to use SHAP to understand which features affect the target variable decisions.
