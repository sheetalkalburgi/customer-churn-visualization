# Customer Attrition Prediction
Visualsation of customer data to predict churn rate

## Data Source
Deep Learning A-Z ANN Dataset: Bank Dataset to investigate high customer attrition rate.\
Source: https://www.kaggle.com/filippoo/deep-learning-az-ann

## Objective
The purpose of this project is to look into a bank dataset to analyze and predict the customer attrition rate at the European bank. This dataset investigates the high rate of customers leaving a bank. The dataset comprises of 14 columns and 10,000 rows that include details such as gender, credit score, geography, etc. The rate of customer attrition is an important KPI that any bank/company should track to ensure they are implementing the right strategic decisions. It might also indicate a failure in aspects such as the customer experience, product/service sold and how customer relationship management is handled. Therefore, we have chosen this dataset to highlight the importance of customer attrition rate KPI for an organization, as retaining existing customers is equally important and relatively cheaper than targeting new ones. We plan on analyzing this data and predicting the attrition rate using different Python libraries in Anaconda software. We also plan to find out the contributing factors to this high attrition rate in European banks.

Analyze all factors causing high customer attrition rate: 
- Credit Score: The customer’s current credit score.
- Geography: Country in which the customers’ bank account was opened.
- Gender type: Indicator if the customer is male or female. 
- Age: Age of the customer
- Tenure: Duration for which the customer has stayed with the bank.
- Debit Balance: The debit balance available in the customers’ bank account.
- Number of products: Number of products the customer has purchased from the bank such as loans, bonds etc.
- Has Credit Card: Indication if the customer has a credit card or not.
- IsActiveMember: Indication if the customer has an active transaction with their bank account.
- Estimated Salary: The estimated salary of the customer.

From the analysis of this dataset, we would like to understand what factors influence the customer attrition rate at the bank, and in turn, predict if a customer is likely to leave the bank or not based on the selected factors.

## Conclusion
Obtained an accuracy of 84% with this model which predicted whether the customer would leave or stay at the bank. The best model takes into consideration the predictor variables: Geography, Gender, Age, Tenure, IsActive Member, Age\*IsActiveMember to give us the best equation for our model. 

This dataset is rather small for prediction of the regression variable ‘Exited’ with high affirmation. Adding more data points to the model will definitely improve the accuracy and prediction strength of the equation. We also found many pivotal insights from the data discussed above but the addition of historical data would definitely help. Adding more independent variables would help us improve the R squared score and in return get a better equation for our prediction model. Based on the confusion matrix and the summary measures we can increase some measures like recall or precision according to the implementation of the model in different business situations. 
