# Regression Techniques on Datasets (California Housing Dataset, Boston Housing prices, Banking Finance Dataset)

1. This is a repositoty consisting of ML techniques implemented on Housing dataset (XGBoost, Linear Regression, Random Forest)
 
## Key Definitions of R^2, RMSE and MSE 

1. R-squared, also known as the coefficient of determination, is a statistical measure that represents the proportion of the variance in the dependent variable that is explained by the independent variable(s) in a regression model.

It ranges from 0 to 1, where 0 means that none of the variance in the dependent variable is explained by the independent variable(s) and 1 means that all of the variance in the dependent variable is explained by the independent variable(s).

In other words, R-squared measures the goodness of fit of the regression model, indicating how well the model fits the observed data points. 

2. RMSE stands for Root Mean Squared Error, which is a commonly used statistical measure of the differences between the values predicted by a model and the actual observed values.

It is calculated by taking the square root of the average of the squared differences between the predicted values and the actual values. Mathematically, it can be represented as:

RMSE = sqrt(1/n * Sum[(predicted_i - actual_i)^2])

where n is the number of observations, predicted_i is the predicted value for observation i, and actual_i is the actual observed value for observation i.

3. MSE stands for Mean Squared Error, which is a statistical measure of the average squared differences between the values predicted by a model and the actual observed values.

It is calculated by taking the average of the squared differences between the predicted values and the actual values. Mathematically, it can be represented as:

MSE = 1/n * Sum[(predicted_i - actual_i)^2]
