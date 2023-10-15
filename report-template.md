
## Overview of the Analysis

 * The purpose of this analysis is to predict the credit risk associated with loans by using machine learing model. 

* The given financial data consists of loan size,	interest rate,	borrower income,	debt to income,	number of accounts,	derogatory marks,	total debt,	and loan status. The objective is to predict the loan status as healthy loan or high risk loan. 

* Loan status is valued either (0) as a healthy loan or (1) as a high-risk loan. As this label has categorical dependent values 0 to 1, Logical Regression model is assisted for prediction.

The stages of the machine learning process:

* Splitting the data into training and testing datasets.
* Creating and fitting a logistic regression model with the original data.
* Evaluate the model’s performance by generating a confusion matrix.
* Generate a classification report that gives accuracy, precision,recall scores and F1 Score.



## Results

* Machine Learning Model 1:

* Description of Model 1: Accuracy, Precision, and Recall scores.

Accuracy: The overall accuracy of the model is 0.99, shows 99% of the instances predicted correctly. 

Precision:

Healthy loans (0): The model has a precision of 1.00, which means it's prediction is good at identifying true positives with very few false positives.
High-risk loans (1): The model has a precision of 0.87, so this model identified high-risk loans with some false positives.

Recall:

Healthy loans (0): The model has a recall of 1.00, which means it's correctly predicted healthy loans with very few false negatives.
High-risk loans (1): The model has a recall of 0.89, so this model identified high-risk loans with some false negatives.


## Summary

The logical Regression model performed well for the original data set. 
It is very important to predict 1 (High-risk loans) and its precision , recall and F1-score are more than 85% . My recommendation is to ensure the effectiveness and accuracy, we can train this model with resampled data. 
