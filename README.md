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

- Customer occupation was one of the strongest predictors of account balance.
- Tree-based models significantly outperformed linear models for both regression and classification tasks.
- Transaction behavior and customer attributes contributed substantially to predictive performance.
- Customer segments revealed distinct spending and transaction patterns.
- Anomaly detection highlighted transactions that deviated from normal behavioral trends.

## Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- XGBoost
- Jupyter Notebook

