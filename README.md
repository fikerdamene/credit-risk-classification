# credit-risk-classification

Overview of the Analysis

The purpose of this analysis was to develop a machine learning model to predict the status of loans (healthy or high-risk) using historical lending data. The goal was to accurately classify loans to assist in better decision-making for loan approvals, thereby minimizing risk and maximizing returns. We used logistic regression, a popular classification algorithm, to build the predictive model.

The Results

Below are the key performance metrics of the logistic regression model:

Accuracy Score: 0.99

Precision Score for Class 0 (Healthy Loan): 1.00

Recall Score for Class 0 (Healthy Loan): 0.99

Precision Score for Class 1 (High-Risk Loan): 0.85

Recall Score for Class 1 (High-Risk Loan): 0.91

F1-Score for Class 0 (Healthy Loan): 1.00

F1-Score for Class 1 (High-Risk Loan): 0.88


- Detailed Metrics

Class 0 (Healthy Loan):

Precision: 1.00

Recall: 0.99

F1-Score: 1.00

Support: 18765


Class 1 (High-Risk Loan):

Precision: 0.85

Recall: 0.91

F1-Score: 0.88

Support: 619


- Overall Metrics:

Macro Average Precision: 0.92

Macro Average Recall: 0.95

Macro Average F1-Score: 0.94

Weighted Average Precision: 0.99

Weighted Average Recall: 0.99

Weighted Average F1-Score: 0.99


- Confusion Matrix

Predicted 0 (Healthy Loan)	Predicted 1 (High-Risk Loan)

Actual 0	18663	102

Actual 1	56	563


Summary

The logistic regression model shows exceptional performance in predicting loan statuses, with an overall accuracy of 99%. The precision and recall scores indicate that the model is highly reliable, especially in predicting healthy loans.

Strengths:

Healthy Loans: The model achieves nearly perfect precision and recall, indicating it correctly identifies almost all healthy loans with minimal false positives and negatives.

High-Risk Loans: The model has good precision (0.85) and very good recall (0.91), demonstrating its capability to identify a significant portion of high-risk loans correctly.


Weaknesses:

The model's precision for high-risk loans, while good, shows some room for improvement, indicating that there are still some false positives which could be minimized.


Recommendation

Based on the analysis, I recommend the logistic regression model for use by the company. The model's high accuracy and strong performance metrics ensure that it will be highly effective in predicting loan statuses, thereby helping the company minimize risks associated with loan approvals. The minor weakness in predicting high-risk loans can potentially be addressed through further model tuning, feature engineering, or employing more complex algorithms in the future.

In conclusion, this logistic regression model offers a robust solution for classifying loans, providing a valuable tool for informed decision-making in the lending process.
