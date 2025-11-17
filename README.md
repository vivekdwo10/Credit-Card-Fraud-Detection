# Credit-Card-Fraud-Detection


Credit card transactions have become one of the most common means of payment in modern economies. With the increase in online and card-present purchases, fraudulent transactions have also increased significantly. According to industry reports, credit card fraud accounts for billions of dollars in losses annually. Fraudulent transactions can involve stolen cards, fake identities, account takeover, or manipulation of transaction details. 
Machine Learning (ML) provides effective tools for identifying hidden patterns in transaction data to detect fraudulent activities. By training models on historical transaction data, ML systems can learn the distinguishing features of fraudulent and non-fraudulent transactions. This project aims to design and implement a fraud detection system using Python and suitable ML algorithms, demonstrating the end-to-end pipeline from data pre-processing to model evaluation.

Chosen Algorithm:
1.	Logistic Regression
Chosen as a baseline model due to its simplicity, interpretability, and effectiveness in binary classification.
Helps in understanding the relationship between features and fraud probability.
2.	XGBoost (Extreme Gradient Boosting)
Selected as an advanced machine learning model for higher accuracy.
Handles imbalanced data better, captures complex relationships, and prevents overfitting with regularization.
3.	SMOTE (Synthetic Minority Oversampling Technique)
Used to balance the dataset by generating synthetic fraudulent samples.
Ensures both Logistic Regression and XGBoost models learn fraud patterns effectively.

 Reason for Selection:
Handles large datasets well.
Works with unbalanced classes.
Provides feature importance for interpretability.
Non-linear and captures complex patterns.
