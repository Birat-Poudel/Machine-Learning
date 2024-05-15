# Car Price Prediction

#### Input Features
1. Year
2. Present_Price
3. Kms_Driven
4. Fuel_Type
5. Seller_Type
6. Transmission
7. Owner

#### Output Target
1. Selling_Price

#### Regression Models
1. Linear Regression Model
2. Lasso Regression Model
3. Ridge Regression Model

#### Conclusion
Linear Regression Model:
1. Training Data: R-squared error = 0.8799
2. Testing Data: R-squared error = 0.8366

Lasso Regresion Model:
1. Training Data: R-squared error = 0.8428
2. Testing Data: R-squared error = 0.8709

Ridge Regression Model:
1. Training Data: R-squared error = 0.8799
2. Testing Data: R-squared error = 0.8401

Comparing the R-squared values:

1. For the training data, the Linear and Ridge models have slightly higher R-squared values than the Lasso model.
2. For the testing data, the Lasso model has the highest R-squared value, followed by the Ridge model, and then the Linear model.

Since the primary goal is to have good performance on unseen data (testing data), the Lasso model seems to perform the best in this case. It has the highest R-squared value for the testing data, indicating better predictive performance compared to the other models. Therefore, based on the obtained R-squared error values, the Lasso model performed better for this car price prediction task.