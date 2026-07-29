# NovaPay Fraud Transaction Detection

This project develops a machine learning-based fraud detection system for NovaPay. The objective is to identify potentially fraudulent transactions more effectively than traditional static, rules-based approaches while reducing unnecessary disruption to legitimate customers.

## Business Challenges

### 1. Limitations of Static Rule-Based Systems

Traditional fraud detection systems often depend on fixed rules and thresholds. These systems may struggle to adapt to changing fraud patterns and newly emerging fraudulent behaviour.

### 2. Direct Financial Impact

Fraudulent transactions can cause financial losses through refunds, chargebacks, investigation costs, operational expenses, and penalties associated with undetected fraud.

### 3. Customer Attrition Caused by False Positives

False positives occur when legitimate transactions are incorrectly classified as fraudulent. Excessive false positives can interrupt valid transactions, reduce customer trust, and encourage customers to move to competing platforms.

### 4. Class Imbalance

Fraud detection is a class-imbalanced classification problem because fraudulent transactions occur less frequently than legitimate transactions.

In the cleaned NovaPay dataset, fraudulent transactions represent approximately 8.8% of the available records. This imbalance means that model performance should not be evaluated using accuracy alone.

Metrics such as precision, recall, F1-score, ROC-AUC, and precision-recall AUC will also be considered.

### 5. Regulatory and Compliance Risk

Anti-Money Laundering and Know Your Customer requirements make transparency and auditability important in financial systems. Fraud predictions should therefore be supported by understandable features and explainable model outputs.

## Target Variable

The target variable is `is_fraud`, a binary classification label:

- `1` — Fraudulent transaction
- `0` — Legitimate transaction

## Current Project Status

The following stages have been completed:

- Initial data inspection
- Data-quality assessment
- Missing-value treatment
- Invalid-value correction
- Exploratory data analysis
- Numerical and categorical fraud analysis
- Initial feature preparation

The next stages will include feature engineering, preprocessing, model development, model evaluation, and explainability.