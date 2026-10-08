# Customer Segmentation Using K-Means Clustering

## Project Overview

This project applies **K-Means clustering** to identify distinct customer segments based on transaction behavior, account characteristics, and digital engagement metrics. The objective is to uncover meaningful customer groups that can support targeted marketing strategies, customer retention initiatives, and personalized banking services.

## Business Objective

By segmenting customers into data-driven groups, organizations can:

- Develop targeted marketing campaigns
- Improve customer experience
- Identify high-value customers
- Enhance digital engagement strategies
- Support customer retention efforts

## Methodology

The analysis used the **K-Means clustering algorithm** to group customers with similar characteristics. Features were standardized before clustering to ensure equal weighting across variables.

Key variables included:

- Customer Age
- Account Balance
- Transaction Amount
- Login Activity
- Transaction Behavior Metrics

The optimal clustering solution identified **four distinct customer segments**.

## Tools Used
- Pandas
- Numpy,
- Scikit-learn
- Matplotlib
- Seaborn
-  K-Means Clustering

## Key Findings

K-Means clustering revealed four unique customer groups differentiated primarily by:

- Account Balance
- Transaction Amount
- Login Behavior

These variables were the strongest drivers of customer segmentation.
<br></br>

<img width="900" height="500" alt="download" src="https://github.com/user-attachments/assets/5c541832-7567-46a5-b6c4-3fa02928fb1b" />

---

## Customer Segments

### Cluster 0: Young Banking Users

**Characteristics**:

- Youngest customer group (average age of 28)
- Lowest account balances
- Small-to-moderate transaction amounts
- Minimal login issues

**Business Insight**

These customers appear to use their accounts primarily for routine banking activities and maintain relatively low balances. They may represent customers early in their financial journey with potential for long-term growth.

---

### Cluster 1: High-Balance Conservative Customers

**Characteristics**:

- Oldest customer group (average age of 55)
- Highest account balances
- Lowest transaction amounts
- Stable account access patterns

**Business Insight**

These customers maintain substantial balances while conducting relatively few transactions. Their behavior suggests a savings-oriented or investment-oriented profile rather than an active transactional relationship.

---

### Cluster 2: Digitally Active Customers

**Characteristics**:

- Significantly higher login activity (count of 4 on average)
- Frequent account engagement
- Strong digital channel usage

**Business Insight**

This segment demonstrates the highest level of digital interaction, indicating frequent account monitoring, repeated authentication activity, or a strong preference for online banking services.

---

### Cluster 3: High-Value Transaction Customers

**Characteristics**:

- Largest transaction amounts (~ 900 dollars)
- Moderate account balances
- High transactional intensity

**Business Insight**

These customers regularly perform larger-value transactions than other segments, suggesting they may represent business users, affluent customers, or individuals with high financial activity.

---
## Conclusion
K-Means Clustering successfully identified four distinct customer segments with meaningful behavioral differences. The analysis showed that account balances, transaction amounts, and login activity are key factors that differentiate customer groups. These insights can help financial institutions design more targeted products, improve customer engagement, and allocate resources more strategically to maintain customer trust.

## Limitations
 
While the clustering analysis successfully identified distinct customer segments, the project focuses primarily on customer profiling and doesn't evaluate the effectiveness of potential business strategies for each segment. Additionally, K-Means clustering is sensitive to the selected number of clusters and assumes that customer groups are relatively well-separated, which may not fully capture complex customer behaviors.
