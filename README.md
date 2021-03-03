# Customer-Spend-Prediction
A regression model to predict customer spend based on 299 masked features.

Feature selection techniques include removing features with > 0.70 missing values, constant features, duplicated features, correlated features, and L1 Regularization.

After hyperparameter tuning of a XGBoost regression model, a MSE of 912 was achieved, significantly outperforming the baseline Linear Regression model that had MSE of 38575.
