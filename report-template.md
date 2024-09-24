# Module 12 Report Template

## Overview of the Analysis

In order to optimize our decision-making in regards to who is accepted and rejecting during the loan application process, we used a logistic regression model to predict who would default on their loan. We used a variety of factors in our algorithm including information about the loan and information about the borrower's past credit history. Our goal was to predict whether a loan was healthy (0) or unhealthy (1). We had to split our data into training and testing sets using train_test_split so that we could verify the validity of our model after creating it. We fit the model using the training data, and then created predictions on our testing data. We visualized our model's accuracy using the confusion matrix and classification report. We were able to confirm the accuracy of our predictions as we knew as the actual values for our testing set.

## Results

Machine Learning Model 1: Logistic Regression (0 = Healthy Loan, 1 = High-Risk Loan)
    * Accuracy: 99% - The model correctly predicted the outcome for 99% of the test set.
    * Precision (0): 100% - The model's predictions for healthy loans were correct 100% of the time.
    * Precision (1): 84% - The model's predictions for high-risk loans were correct 84% of the time.
    * Recall (0): 99% - The model correctly identified 99% of actual healthy loans.
    * Recall (1) .94% - The model correctly identified 94% of actual high-risk loans

## Summary

The logistic regression model performed exceptionally well, achieving a 99% accuracy rate. It was particularly effective at predicting healthy loans (0s), with near-perfect precision and recall. This means the model almost never misclassified healthy loans and successfully identified nearly all of them.

For high-risk loans (1s), the model's performance was strong but slightly less reliable. It correctly identified 94% of actual high-risk loans, but its precision was lower at 84%, indicating that some healthy loans were misclassified as high-risk.

The overall takeaway is that the model excels at predicting healthy loans but may need refinement if correctly identifying high-risk loans is the priority. The importance of improving precision for high-risk loans depends on the specific business problem. If avoiding loan defaults is critical, more attention may be needed on enhancing the model's ability to accurately flag high-risk loans, even at the cost of slightly reducing its performance on healthy loans.
