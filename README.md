# Learning-from-Data
Learning from data module Exeter

Dataset and Task:

Credit Card Fraud Detection
Fraudulent transactions happen every day and it is important that credit card companies are able to recognize these fraudulent credit card transactions.

The dataset contains transactions made by credit cards in September 2013 by European cardholders. This dataset presents transactions that occurred in two days:

492 fraudulent out of 284,807 transactions. The dataset is highly unbalanced where the positive class (frauds) account for 0.172% of all transactions.

https://www.kaggle.com/mlg-ulb/creditcardfraud

It contains only numerical variable inputs which are the result of a PCA transformation. Due to confidentiality the original features and more background information about the data are not included. Features V1, V2, … V28 are the principal components obtained with PCA, the only features which have not been transformed with the PCA are the variables 'Time' and 'Amount'.

'Time'- contains the seconds elapsed between each transaction and the first transaction in the dataset. 'Amount' - transaction Amount; this feature can be used for example-dependant cost-sensitive learning.

'Class' - is the response variable and it takes. Value 1 = Fraud and 0 = Not fraud.
