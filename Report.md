# Overview 
The purpose of this analysis is to show how machine learning methods can be applied to Financial Datasets. In this analysis, lending dataset was used to calculate loan status, as measured by healthy loan of class 0 and high risk at default loan as measured by class 1 using variables such as loan size, interest rate, burrowers income, total debt, etc. 

This report concludes its findings by classifying each observation’s loan status through a logistic regression machine learning model and then criticizes its performance by splitting the dataset into testing and training data. Applying a logistic regression is most appropriate as output data is measured through binary classification such that 0 reflecting healthy loans and 1 reflection high risk loans.

## Results 
Results are obtained by the confusion matrix function to indicate the performance of the model and is reported through the following: 
Balanced Accuracy Score: 99%
Healthy Loans:
Precision Score: 100%
This means that all predicted positives were correct
Recall Score: 100%
Showing that the ratio of actual positives occurred at 100%
High-Risk Loan: 
Precision Score: 87%
This means that 87% of predicted positives were correct 
Recall Score: 89%
Shows that the ratio of actual positives occurring was 89%
## Summary
This model shows a high level of accuracy, precision and recalling and would find it reliable to apply for most datasets. However the model does show some room for improvement with classifying high risk loans with a low precision and recall score. It is also important to be cautious of high risk loans because it can be more difficult to make up for lost money in a loan. Therefore I would recommend this model to company’s with precaution. 
