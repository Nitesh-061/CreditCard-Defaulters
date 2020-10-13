# CreditCard-Defaulters
A classification methodology to determine whether a person defaults the credit card payment for the next month. 

The data contains 32561 instances with the following attributes:
Features:

1.	LIMIT_BAL: continuous.Credit Limit of the person.
2.	SEX: Categorical: 1 = male; 2 = female
3.	EDUCATION: Categorical: 1 = graduate school; 2 = university; 3 = high school; 4 = others
4.	MARRIAGE: 1 = married; 2 = single; 3 = others
5.	AGE-num: continuous. 
6.	PAY_0 to PAY_6: History of past payment. We tracked the past monthly payment records (from April to September, 2005)
7.	BILL_AMT1 to BILL_AMT6: Amount of bill statements.
8.	PAY_AMT1 to PAY_AMT6: Amount of previous payments. 


Target Label:
Whether a person shall default in the credit card payment or not.
9.	default payment next month:  Yes = 1, No = 0.

### Clustering - KMeans algorithm is used to create clusters in the preprocessed data.
### Model Selection – To find the best model for each cluster. We are using two algorithms, “Naïve Bayes” and "XGBoost"
