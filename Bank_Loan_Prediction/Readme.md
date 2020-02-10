## Bank Loan Prediction
### Problem Description:
#### When a customer applies for a loan, banks and other credit providers use statistical models to determine whether or not to grant the loan  based on the likelihood of the loan being repaid. The factors involved in determining this likelihood are complex, and extensive statistical analysis and modeling are required to predict the outcome for each individual case.

#### I analyzed a loan dataset using logistic regression, random forests, and boosting to predict loan repayment or default based on the following features:

Loan ID: A unique Identifier for the loan information.

Customer ID: A unique identifier for the customer. Customers may have more than one loan.

Loan Status: A categorical variable indicating if the loan was paid back or defaulted. Target variable

Current Loan Amount: This is the loan amount that was either completely paid off, or the amount that was defaulted.

Term: A categorical variable indicating if it is a short term or long term loan.

Credit Score: A value between 300 and 850 indicating the riskiness of the borrowers credit history.

Years in current job: A categorical variable indicating how many years the customer has been in their current job.

Home Ownership: Categorical variable indicating home ownership. Values are“Rent”,“Home Mort- gage”, and “Own”. If the value is OWN, then the customer is a home owner with no mortgage

Annual Income: The customer’s annual income

Purpose: A description of the purpose of the loan.

Monthly Debt: The customer’s monthly payment for their existing loans

Years of Credit History: The years since the first entry in the customerss credit history

Months since last delinquent: Months since the last loan delinquent payment

Number of Open Accounts: The total number of open credit cards

Number of Credit Problems: The number of credit problems in the customer records

Current Credit Balance: The current total debt for the customer

Maximum Open Credit: The maximum credit limit for all credit sources

Bankruptcies: The number of bankruptcies

Tax Liens: The number of tax liens

## Steps Followed:
### 1] Data Analysis
### 2] Data Cleaning(Delete duplicates etc..)
### 3] Data Munging (Outliers, Null values treated with imputing technique)
### 4] Data Visualization
### 5] Machine learning (Logistic Regression, Lasso & Riege regression, Randome Forest, Boosting, Bagging)
