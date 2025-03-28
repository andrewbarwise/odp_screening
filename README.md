# odp_screening

For this project I have decided to use a linear regression model.
This is for both simplicity and interpretability. A linear regression model allows 
relationships between the dependent and independent variables to be explored.
If time permitted other models such as Ensemble models (Bagging and Boosting)
or Autoregressive models could have been investigated. The analysis is
deeply constrained by the lack of data.

Feature engineering was used to create lag variables so that future values for 
revenue_index can be predicted from historical data. 

## Order Numbers
    - Where it was determined that the order number has not increased, 
     I have taken the decision to delete that row. This has resulted
     in the deletion of 218 data points. 