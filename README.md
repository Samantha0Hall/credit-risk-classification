# credit-risk-classification
Module 20 Challenge

## Overview of the Analysis

* The purpose of this anaylsis is to evaluate the accuracy of a data model to determine creditworthiness of borrowers.
  
* Some of the financial information used include: Loan size, income, debt to income, number of accounts, derogatory marks, total debt.

* Stages of the machine learning process used: Seperating data to test and training set. Create logistic regression model and evaluate accuracy (used: confusion matrix, classification report). Use resampled training data to predict a logistics regression model (used: RandomOverSampler, confusion matrix, classification report).

* Both models performed well with the given data, but I would recommend using the second learning model as it performed better with "high-risk" loans.

----------------------------------------------------------------------------------------------------------
## Machine Learning Model 1 Classification Report (Original Data):

![image](https://github.com/Samantha0Hall/credit-risk-classification/assets/140672220/dcdb6858-059c-46ed-81d6-22ab4f1ebecb)

### This model predicts "healthy loans" with a high accuracy of 100%, and "high-risk loans" with a 88% accuracy, and an average accuracy of 94%. However, it should be noted, there is a largely lower number of "high-risk" loans compared to "healthy" loans.
--------------------------------------------------------------------------------------------------------------
## Machine Learning Model 2 Classification Report (Resampled Training Data):

![image](https://github.com/Samantha0Hall/credit-risk-classification/assets/140672220/a0c678ff-7c6a-428d-b20f-da9c6724e89a)

### This model predicts "healthy" loans with a high accuracy of 100%, and "high-risk" loan" with a 91% accuracy, and an average accuracy of 95%. While the data is still heavily unbalanced, this model performed better with "high-risk" loans.
