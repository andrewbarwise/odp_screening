# odp_screening

For this project I have decided to use a linear regression model.
This is for both simplicity and interpretability. A linear regression model allows 
relationships between the dependent and independent variables to be explored.
If time permitted other models such as Ensemble models (Bagging and Boosting)
or Autoregressive models could have been investigated. The analysis is
deeply constrained by the lack of data.

Feature engineering was used to create lag variables so that future values for 
revenue_index can be predicted from the previous time period. 

## Linear Regression
With linear regression we are assuming the relationship between the independent variables and dependent variables to be approximately linear.
The objective is to estimate the coefficeints that best fit the observed data. The best fit is usually defined
as minimising the sum of squared differences between the observed and predicted values (residual sum of squares or mse)

Linear regression relies on four key assumptions:
i) Linearity: the relationship between the independent and dependent variables is approx. linear
ii) Independence: the observations are independent of each other
iii) Homoscedasticity: the variance of the error terms is constant across all levels of the independent variables.
iv) Normality of residuals: the residuals follow a normal distribution

## Order Numbers
 Where it was determined that the order number has not increased, 
 I have taken the decision to delete that row. This has resulted in the deletion of 218 data points. 
 It is alot of data to delete however with the time constraint of the assessment I felt is was the easiest solution.