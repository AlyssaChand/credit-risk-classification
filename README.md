# credit-risk-classification

These are the sources I used to help write my code: scikit-learn.org, google, and BCS — watching our cloud recordings, using instructor activity solutions and the class activities as references.

## Credit Risk Analysis Report
### Overview of the Analysis
The purpose of this analysis is to evaluate the performance of a logistic regression model in predicting credit risk. Specifically, it is aim to determine how accurately the model can classify loans as either healthy `0` or high-risk `1`. 
This analysis is critical for financial institutions seeking to minimize default rates and manage credit risk effectively.

### The Results
#### Machine Learning Model: Logistic Regression
* Accuracy Score: 0.99
* Precision Score:
    * Healthy Loans `0`: 1.00
    * High-Risk Loans `1`: 0.85
* Recall Score:
    * Healthy Loans `0`: 0.99
    * High-Risk Loans `1`: 0.91
* F1-Score:
    * Healthy Loans `0`: 1.00
    * High-Risk Loans `1`: 0.88
### Summary
The logistic regression model demonstrates outstanding performance in predicting both healthy and high-risk loans. With an overall accuracy of 99%, the model correctly classifies 99% of all loan instances. It achieves perfect precision (1.00) and an F1-score (1.00) for healthy loans, indicating almost flawless identification. For high-risk loans, the model maintains a good balance with a precision of 0.85, recall of 0.91, and F1-score of 0.88.

Based on these results, I recommend using this logistic regression model for credit risk prediction. The model's high accuracy and strong performance in identifying both healthy and high-risk loans make it a reliable tool for financial decision-making. Its ability to correctly identify the majority of high-risk loans will help the company manage credit risk effectively, while its perfect precision for healthy loans ensures that low-risk customers are not mistakenly classified as high-risk.
