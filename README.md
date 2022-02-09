# Surprise Housing Analysis - Advanced Regression
> A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia. The data is provided in the CSV file below.

The company is looking at prospective properties to buy to enter the market. You are required to build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not.

The company wants to know:

 1. Which variables are significant in predicting the price of a house, and

 2. How well those variables describe the price of a house.

## Business Goal
You are required to model the price of houses with the available independent variables. This model will then be used by the management to understand how exactly the prices vary with the variables. They can accordingly manipulate the strategy of the firm and concentrate on areas that will yield high returns. Further, the model will be a good way for management to understand the pricing dynamics of a new market.


### Model Building

The model is built using Ridge and Lasso regression, and to get best alpha score from both. Both the model has to be compared and best model has to be selected. Also, top predictor variables has to be identified. Below are top top feature identified from Ridge and Lasso.

### Conclusion

### Lasso:
- `GrLivArea`
- `OverallQual_Excellent`
- `Neighborhood_StoneBr`
- `OverallQual_Very Good`
- `Functional_Typ`

Lasso is preffered regularisation method as it gives benefit of reducing coefficient for some lower significant feature to 0 and improve the accuracy.

### Steps for Model Building
1. Reading and Understanding Data  
2. Visualising the Data  
3. Data Preparation(Numerical/Categorical) 
4. Splitting the Data into Training and Testing Sets
5. Building the Linear Regrssion Model  
6. Ridge Regularization  
7. Lasso Regularization  
8. Model Evaluation

