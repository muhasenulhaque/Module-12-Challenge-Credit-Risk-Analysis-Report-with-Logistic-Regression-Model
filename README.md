# Module-12-Challenge-Credit-Risk-Analysis-Report-with-Logistic-Regression-Model
RandomOverSampler, LogisticRegression, train_test_split, value_counts

## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

* The purpose of the analysis is to predic the loan status based on the infromation in the dataset
* The given information to the model was loan_size, interest_rate, borrower_income, debt_to_income,num_of_accounts,derogatory_marks and total_debt to predict the loan status.
* The predicted value of loan status 0 is 75036 and 1 is 2500
* In the machine learning model we needed to train the data, assign a random state, fit the data and then predict the data.   
* BLogistic regression is a statistical method for predicting binary outcomes from data. 
* Resampling imports the data, then seperate the data into target and feature datasets, encode the data and scale the data. We used the RandomOverSampler for resampling the data. 

## Results

Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1:
  precision    recall  f1-score   support

           0       1.00      1.00      1.00     56271
           1       0.86      0.90      0.88      1881

    accuracy                           0.99     58152
   macro avg       0.93      0.95      0.94     58152
weighted avg       0.99      0.99      0.99     58152

* Machine Learning Model 2:
  precision    recall  f1-score   support

           0       0.99      0.99      0.99     56271
           1       0.99      0.99      0.99     56271

    accuracy                           0.99    112542
   macro avg       0.99      0.99      0.99    112542
weighted avg       0.99      0.99      0.99    112542


## Summary


* The logistic regression model predict quite accurately and the accuracy level is 99%    
* The oversampled data fitted well and the overal accuracy of the model improved from 0.9918489475856377 to 0.9947308560359688
