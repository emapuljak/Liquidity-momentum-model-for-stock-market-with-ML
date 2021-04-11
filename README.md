# Liquidity-momentum-model-for-stock-market-with-ML
Liquidity and momentum model for stock market movements based on machine learning algorithms
  The goal was to develop a model based on machine learning methods, which could, based on an assessment of the trends of individual stock and its liquidity, explain the future movement of the stock return. Comparing multiple simple and complicated machine learning models.

 - models.ipynb -> Linear regression, Decision Tree, SVM, MLP, LSTM
 - xgboost1.ipynb -> XGBoost model with WML, IML and market return as input parameters
 - xgboost2.ipynb -> XGBoost model where input data X = feature set with names {market_volume(t-k)} where k from 1. to 6. month
