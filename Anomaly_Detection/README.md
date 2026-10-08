### Anomaly Detection Objective

Identify unusual transaction patterns that may indicate fraud, operational issues, or atypical customer behavior using unsupervised machine learning techniques.

### Methodology

Two anomaly detection algorithms were applied:

- Isolation Forest (IF)
- Local Outlier Factor (LOF)

Both models were trained on transaction and customer attributes to detect observations that deviated from normal behavioral patterns.

### Results

- The IF model classified 99.81% of transactions as normal and flagged 0.19% as anomalous, indicating that unusual transaction activity was relatively rare within the dataset.
- The LOF classified 99.8% of transactions as normal and flagged 0.2% as anomalous, indicating a similar anomalous pattern as the IF model.


### Conclusion

Although Isolation Forest and LOF detected a similar proportion of anomalies, none of the transactions identified by one method were simultaneously flagged by the other. This suggests that each algorithm captures different dimensions of anomalous behavior:
LOF identifies observations that are unusual relative to their local neighborhood and Isolation Forest identifies observations that are globally different from the overall population. Compared with normal transactions, anomalies generally showed:

- Lower transaction amounts ➡️ Higher average account balances ➡️  Older customer profiles ➡️ Longer transaction durations


