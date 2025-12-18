# Fraud-Detection-Transaction-Monitoring-

## Project Overview
This project analyzes transactional data to identify fraud patterns and monitor risk signals commonly used in financial services. This focuses on operational fraud detection, emphasizing transaction behavior, channel risk, and high-risk flag validation rather than predictive modeling.
The Tableau dashboard shows how fraud and payments teams monitor risk, making this project particularly relevant for banking and credit card analytics roles

## Business Problem 
Financial institutions process thousands of transactions daily and must quickly identify potentially fraudulent activity to reduce losses and mitigate customer frustration.
This project addresses:
- What transaction characteristics are most associated with fraud?
- How fraud risk varies by channel, timing, and merchant category.
- Whether simple rule-based flags effectively seperate fradulent activity.

## Dataset
- 8,000 synthetic transaction records
- Realistic transaction behaviors and fraudulent patterns
### Key Fields
- Transaction amount
- Transaction hour (0-23)
- Merchant category
- Channel (card-present vs card-not-present)
- Foreign transaction indicator
- Region
- Fraud indicator (is_fraud)
### Target Variable 
is_fraud (1 = fraudulent transaction)

## Tools Used
#### Python
- pandas
- numpy
#### Tableau
- Operational monitoring dashboards
- KPI reporting
- Interactive filtering
Key Insights
- Card-not-present transactions exhibit significantly higher fraud rates than card-present transactions
- Foreign transactions are riskier than domestic transactions
- Fraud Rates peak during late-night and early morning hours
- Electronics and online retail merchant categories show the highest fraud exposure
- Transactions flagged as high risk demonstrate  higher fraud rates, confirming the effectiveness of the rule-based approach

## Tableau
An interactive Tableau dashboard was built to support fraud monitoring, featuring:
- Transaction Volume and fraud KPIs
- Fraud rate by channel, time of day, and foreign status
- Fraud rate by merchant categroy
- Validation of high-risk transaction flag
- Filter for region
