# Module 20 Report 

## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

* The purpose of this Analysis is to evaluate loan risk models.
* The data used in the models contained various financial metrics of borrowers, such as income, debt to income ratio, and number of accounts, to predict if their loans are healthy or high risk.
* The process included separating out the X and y variables.  The y containing the high risk/healthy labels, and the X containing the rest of the metrics.  Then, after splitting the data into train and test variables, I made a logistic regression model, then fit it and predicted outcomes.


## Results

Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1:
  * Description of Model 1 Accuracy, Precision, and Recall scores.

    * Balanced Accuracy score: .9520479254722232 or ~95.2%
    * Precision score: 0 (healthy loan) - 100%, 1 (high-risk loan) - 85%
    * Recall score: 0 (healthy loan) - 99%, 1 (high-risk loan) - 91%

* Machine Learning Model 2:
  * Description of Model 2 Accuracy, Precision, and Recall scores.

    * Balanced Accuracy score: .9936781215845847 or ~99.4%
    * Precision score: 0 (healthy loan) - 100%, 1 (high-risk loan) - 84%
    * Recall score:0 (healthy loan) - 99%, 1 (high-risk loan) - 99%

## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. For example:
* The second model using oversampled data looks to be the better model to use due to higher accuracy and recall scores, so that would be my recommendation
* Performance does depend on what we are trying to solve.  In this instance we want a more reliable way to find the high-risk (0) loans rather than the healthy (1) loans.


If you do not recommend any of the models, please justify your reasoning.
