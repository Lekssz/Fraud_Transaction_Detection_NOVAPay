# Fraud_Transaction_Detection_NOVAPay
A machine learning-based fraud detection system for NovaPay to replace outdated, rules-based methods. 



# BUSINESS CHALLENGES 

1. Vulnerability of Static Systems: The current reliance on rigid, rules-based detection methods creates a significant security gap. These systems are too static to adapt to the rapidly evolving tactics used by fraudsters, leaving the platform vulnerable to sophisticated and emerging threats.

2. Direct Financial Impact: Fraudulent activity leads to immediate financial erosion. This includes the mounting costs of processing refunds, managing chargebacks, and paying penalties for missed fraud, all of which directly diminish the company's profitability.

3. Customer Attrition from False Positives: High rates of false positives, situations where legitimate transactions are incorrectly flagged as fraud  negatively impacts the customer experience and leads to increased attrition as users move to more seamless competitors.

4. Severe Class Imbalance: The detection process is complicated by a high degree of data imbalance, where fraudulent transactions represent less than 1% of total volume. Identifying these rare anomalies without disrupting the vast majority of legitimate traffic is a major technical hurdle.

5. Regulatory and Compliance RiskStrict AML and KYC frameworks require fraud detection systems to be transparent and auditable. The inability to provide explainable decision-making for flagged transactions poses a risk of regulatory scrutiny and heavy financial penalties.

## TARGET VARIABLES 
Target VariableThe target variable is the Fraud Label, a binary classification output:Value 1 (Fraud): Confirmed fraud, chargebacks, or verified disputes.Value 0 (Legitimate): Valid transactions that cleared successfully.