# Credit Risk Classification using Logistic Regression

Built and evaluated a machine learning model to classify loans as high-risk or healthy based on borrower data. Used logistic regression to predict loan status with a focus on precision and recall for high-risk loans.

## Tools & Technologies Used

- Python
- Pandas
- Scikit-learn (Logistic Regression)
- Classification Report
- Confusion Matrix
- Jupyter Notebooks

## File Structure

```text
.
├── Credit_Risk/
│   ├── credit_risk_classification.ipynb    # Full model workflow
│   └── lending_data.csv                    # Loan dataset
```

## Skills Demonstrated

- Binary classification using Logistic Regression
- Data preparation and feature engineering
- Splitting data into training and testing sets
- Evaluating model accuracy, precision, recall, and F1-score
- Generating confusion matrix and classification report

## Key Findings

- Analyzed 19,384 loans, classifying them as healthy or high-risk.
- Model achieved 100% precision and F1-score for healthy loans (label 0).
- Model achieved 84% precision and 89% F1-score for high-risk loans (label 1), with 94% recall.
- Model tends to predict healthy loans extremely well but occasionally misclassifies high-risk loans as healthy.
