# Credit-Card-Fraud-Detection
R programming

Objective: 

The purpose of this project is to train a machine learning algorithm on the dataset and build a model to predict fraudulent transactions. Given this is a highly unbalanced dataset, we will be using the Area Under the Precision-Recall Curve (AUC) to the model accuracy. Confusion matrix accuracy is not meaningful for unbalanced classification.

Kaggle Dataset description:

It is important that credit card companies are able to recognize fraudulent credit card transactions so that customers are not charged for items that they did not purchase.
The data sets contains transactions made by credit cards by cardholders. This dataset we have found 492 frauds out of 284,807 transactions. The dataset is highly unbalanced, the frauds account for 0.172% of all transactions.
It contains only numerical input variables which are the result of a PCA transformation. Features V1, V2, … V28 are the principal components obtained with PCA, the only features which have not been transformed with PCA is Time and Amount. 
Feature Time contains the seconds between each transaction and the first transaction in the dataset. 
The feature Amount is the transaction Amount, this feature can be used for example-dependant cost-senstive learning. 
Feature Class is the response variable and it takes value 1 in case of fraud and 0 otherwise.

