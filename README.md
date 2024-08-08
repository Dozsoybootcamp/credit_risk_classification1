# credit_risk_classification1
Answer:

The logistic regression model performs exceptionally well in predicting both 0 (healthy loan) and 1 (high-risk loan) labels. Here are the key points:

Accuracy:

The model's overall accuracy is 99%, indicating that 99% of the predictions are correct.
Healthy Loans (Label 0):

The precision and recall for healthy loans are both very high (1.00 and 0.99, respectively). This means the model is almost perfect in identifying healthy loans and rarely misclassifies them as high-risk.
High-Risk Loans (Label 1):

The precision for high-risk loans is 0.86, indicating that when the model predicts a loan is high-risk, it is correct 86% of the time.
The recall for high-risk loans is 0.94, indicating that the model correctly identifies 94% of the actual high-risk loans.
F1-Score:

The F1-score for healthy loans is 1.00, and for high-risk loans, it is 0.90. These scores show a strong balance between precision and recall.
Confusion Matrix:

The confusion matrix shows that out of 507 actual high-risk loans, the model correctly predicted 476 and misclassified 31 as healthy.
Out of 15001 actual healthy loans, the model correctly predicted 14924 and misclassified 77 as high-risk.
Summary:
The logistic regression model shows excellent performance in predicting loan status. It has high precision and recall for both healthy and high-risk loans, making it reliable for identifying loan defaults. Given the high accuracy, precision, recall, and F1-scores, the model is well-suited for deployment in a loan risk assessment system.
