Module 12 Report
Overview of the Analysis
Purpose of the Analysis: The goal of this analysis was to develop machine learning models to predict credit risk using financial indicators.

Financial Information in the Data: The dataset included features such as loan size, interest rate, borrower income, debt-to-income ratio, number of accounts, derogatory marks, and total debt. The target variable was the loan_status, where 0 indicates a low-risk loan, and 1 indicates a high-risk loan.

Basic Information About Variables: We aimed to predict the loan_status variable, a binary classification task. The dataset contains both numerical and categorical variables relevant to determining credit risk.

Stages of the Machine Learning Process:

Data Preparation: The data was separated into features (X) and the target variable (y), followed by a split into training and testing datasets.
Model Training: A logistic regression model was trained using the training dataset.
Evaluation: The model's performance was assessed using accuracy, precision, and recall scores derived from a classification report and confusion matrix.
Methods Used: A logistic regression model was applied for this classification problem.

Results
Logistic Regression Model:
Accuracy: The logistic regression model achieved an accuracy of 99%.
Precision:
For 0 (healthy loan): 1.00
For 1 (high-risk loan): 0.84
Recall:
For 0 (healthy loan): 0.99
For 1 (high-risk loan): 0.94
Summary
Best Performing Model: The logistic regression model performed exceptionally well, with high accuracy, precision, and recall values. It demonstrated the ability to accurately classify both low-risk and high-risk loans, making it the preferred model for this analysis.

Problem Dependency: The model's recall for high-risk loans was strong, indicating that it effectively identifies high-risk cases. This performance is crucial if the goal is to minimize false negatives (i.e., loans wrongly classified as low risk).

Based on these results, the logistic regression model is recommended due to its balanced performance in predicting both classes accurately. ​