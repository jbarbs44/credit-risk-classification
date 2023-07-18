# Module 12 Report Template

## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

The financial information in the csv is:
* loan size
* interest rate
* borrower income
* debt to income
* number of accounts 
* derogatory makrs
* total debt 

* The value counts show that we have 75306 healthy loans, while we had 2500 high risk loans.
* After finding the value counts, we split the data into training and testing datasets. We used those datasets to fit into the logistic regression model and save the predictions. We then used this information in order to calculate the accuarcy of the model, the confusion matrix and printed the classification report.
## Results

Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1:
  * Description of Model 1 Accuracy, Precision, and Recall scores.
    * The precision for healthy loans is 100% and for high risk loans it is 85%.
    * The recall for healthy loans is 99% and for high risk loans is 91%.
    * The accuary is 99%.


* Machine Learning Model 2:
  * Description of Model 2 Accuracy, Precision, and Recall scores.
    * The precision for healthy loans is 100% and for high risk loans it is 84%.
    * The recall for healthy loans is 99% and for high risk loans is 99%.
    * The accuary is 99%.

## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. For example:
* Which one seems to perform best? How do you know it performs best? They seem to perform the same as we see from the precision scores of each.
* Does performance depend on the problem we are trying to solve? (For example, is it more important to predict the `1`'s, or predict the `0`'s? )

If you do not recommend any of the models, please justify your reasoning.
