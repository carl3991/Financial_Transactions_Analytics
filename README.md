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

## Key Features:
`TransactionID`: Unique alphanumeric identifier for each transaction.
`AccountID`: Unique identifier for each account, with multiple transactions per account.
`TransactionAmount`: Monetary value of each transaction, ranging from small everyday expenses to larger purchases.
`TransactionDate`: Timestamp of each transaction, capturing date and time.
`TransactionType`: Categorical field indicating 'Credit' or 'Debit' transactions.
`Location`: Geographic location of the transaction, represented by U.S. city names.
`DeviceID`: Alphanumeric identifier for devices used to perform the transaction.
`IP Address`: IPv4 address associated with the transaction, with occasional changes for some accounts.
`MerchantID`: Unique identifier for merchants, showing preferred and outlier merchants for each account.
`AccountBalance`: Balance in the account post-transaction, with logical correlations based on transaction type and amount.
`PreviousTransactionDate`: Timestamp of the last transaction for the account, aiding in calculating transaction frequency.
`Channel`: Channel through which the transaction was performed (e.g., Online, ATM, Branch).
`CustomerAge`: Age of the account holder, with logical groupings based on occupation.
`CustomerOccupation`: Occupation of the account holder (e.g., Doctor, Engineer, Student, Retired), reflecting income patterns.
`TransactionDuration`: Duration of the transaction in seconds, varying by transaction type.
`LoginAttempts`: Number of login attempts before the transaction, with higher values indicating potential anomalies.

<br></br>

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

