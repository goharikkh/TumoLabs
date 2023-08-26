Waiter Tip Prediction Model ReadMe

Introduction
This project focuses on building a predictive model to estimate tips given by customers to waiters. The dataset originally contained categorical columns, which I encoded into numerical values. The goal of the project is to predict the tip amount a waiter might receive based on various features.

I  added a new column for the percentage of the tip.
Imported the Linear Regression model from a suitable library (e.g., scikit-learn) andf fitted the model using the training data.
Print the model's score, mean absolute error (MAE), and residual sum of squares (MSE).

Linear Regression Model
Score: 0.806166331084734
Mean Absolute Error (MAE): 0.35
Residual Sum of Squares (MSE): 0.24


Random Forest Regressor Model:

I Imported the Random Forest Regressor model from a suitable library.
Plot a graph showing the relationship between the maximum depth of trees and the score.
Identify the maximum depth that yields the highest score.
Train the model using the identified maximum depth.

Random Forest Regressor Model
Best Max Depth: 12
Score: 0.86390588039663

Model Choice and Training Method
The choice of using both Linear Regression and Random Forest Regressor models was made to compare their performance in predicting tips. Linear Regression is a simple model that establishes linear relationships between the features and the target variable. On the other hand, Random Forest Regressor is an ensemble model that can capture complex non-linear relationships in the data.

The accuracy values (scores) of both models were considered for evaluation. The Random Forest Regressor outperformed the Linear Regression model, achieving a higher accuracy score (0.8639 compared to 0.8061). The choice of the Random Forest Regressor was therefore based on its ability to capture more intricate patterns in the data.

Conclusion
In this project, we developed predictive models to estimate tips received by waiters. The Random Forest Regressor model with a maximum depth of 12 proved to be the most accurate, achieving a score of 0.8639. This project showcases the process of data preprocessing, model training, evaluation, and selection for predicting tips in a restaurant setting.