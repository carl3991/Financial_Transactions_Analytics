# Financial Transactions Analytics

## Overview

This project explores customer banking behavior through exploratory data analysis (EDA), machine learning, anomaly detection, and customer segmentation techniques. Using a synthetic financial transactions dataset, the project investigates spending patterns, account balances, transaction behavior, and customer characteristics to generate business insights and develop predictive models.

## Project Objectives

- Analyze customer spending and transaction patterns.
- Identify factors influencing account balances.
- Predict account balances using machine learning models.
- Classify transaction types (Credit vs. Debit).
- Detect unusual or potentially anomalous transactions.
- Segment customers into meaningful groups based on financial behavior.

  
## Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- XGBoost
- Google Colab


## Project Components

### Exploratory Data Analysis (EDA)
- Transaction distribution analysis
- Customer demographic analysis
- Spending behavior analysis by occupation, location, and channel
- Account balance trend analysis
- Data visualization and business insights

### Regression Modeling
Predicted customer account balances using:

- Linear Regression
- Random Forest Regressor
- XGBoost Regressor

Models were evaluated using:
- R squared Score
- Root Mean Squared Error (RMSE)

### Classification Modeling
Classified transaction types (Credit vs. Debit) using:

- Logistic Regression
- Random Forest Classifier
- XGBoost Classifier

Models were evaluated using:
- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix

### Customer Segmentation
Applied clustering techniques to identify distinct customer groups based on spending behavior and transaction characteristics.

- K-Means Clustering
- Cluster profiling and interpretation
- Customer segment visualization

### Anomaly Detection
Detected unusual transaction behavior using unsupervised machine learning techniques.
- Isolation Forest
- Outlier identification

## Key Insights

- Customer occupation was a major determinant of account balance and financial behavior.
- Tree-based models outperformed linear models, achieving stronger predictive performance across machine learning tasks.
- Transaction patterns, customer demographics, and account characteristics were the most influential features in predicting outcomes.
- Customer segmentation revealed four distinct profiles based on age, balances, transaction value, and digital engagement.
- Anomaly detection exposed unusual transaction behaviors that traditional segmentation techniques did not capture.
- Using clustering, predictive modeling, and anomaly detection together provided a holistic understanding of customer behavior and banking activity.

