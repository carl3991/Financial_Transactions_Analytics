
## Model Performance Summary

| Model | R Squared | RMSE | Performance|
|-------|-----------|-------|-----------|
|Linear Regression| 0.4901|2783.25| Baseline model with moderate predictive power
|XGBoost|0.9021|1219.57| Strong preformance that captures non-linear relationships|
|Random Forest|0.9989|128.57| Best performing model on the data
<br></br>

## Methods
- Implemented and compared Linear Regression, Random Forest, and XGBoost models to predict customer account balances. Evaluated model performance using R² and RMSE, demonstrating the impact of nonlinear machine learning techniques on predictive accuracy.


## Key Findings
- Student occupation was the most influential feature in both random forest and XGBoost models, indicating that customers classified as students demonstrated the strongest relationship with account balance.
- Engineer and Retired occupations were also consistently ranked among the most important predictors, suggesting that occupation is a major driver of balance differences within the dataset.
- Transaction Duration was the second most important feature in the Random Forest model, indicating that transaction behavior contributes substantially to predicting account balances.
- Location-based variables, Channel (Branch and Online) and Transaction Type (Debit&Credit) had minor influence overall.

## Conclusion
The feature importance results suggest that **customer characteristics, particularly occupation, are the strongest determinants of account balance**, while transaction behavior variables such as transaction duration and transaction amount provide additional predictive value.
