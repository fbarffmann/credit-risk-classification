# Module 12 Report Template

## Overview of the Analysis

In order to optimize our decision-making in regards to who is accepted and rejecting during the loan application process, we used a logistic regression model to predict who would default on their loan. We used a variety of factors in our algorithm including information about the loan and information about the borrower's past credit history. Our goal was to predict whether a loan was healthy (0) or unhealthy (1). We had to split our data into training and testing sets using train_test_split so that we could verify the validity of our model after creating it. We fit the model using the training data, and then created predictions on our testing data. We visualized our model's accuracy using the confusion matrix and classification report. We were able to confirm the accuracy of our predictions as we knew as the actual values for our testing set.

## Results

* Machine Learning Model 1: Logistic Regression (0 = Healthy Loan, 1 = High-Risk Loan)
    * Accuracy: 99% - The model correctly predicted the outcome for 99% of the test set.
    * Precision (0): 100% - The model's predictions for healthy loans were correct 100% of the time.
    * Precision (1): 84% - The model's predictions for high-risk loans were correct 84% of the time.
    * Recall (0): 99% - The model correctly identified 99% of actual healthy loans.
    * Recall (1) .94% - The model correctly identified 94% of actual high-risk loans

## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. For example:

* Which one seems to perform best? How do you know it performs best?
* Does performance depend on the problem we are trying to solve? (For example, is it more important to predict the `1`'s, or predict the `0`'s? )

If you do not recommend any of the models, please justify your reasoning.
