# Insurance-claim-fraud-analysis-using-ai-tools
Insurance Claim Fraud Analysis using AI techniques to detect anomalies and patterns in claim data, highlighting suspicious cases for improved fraud detection and risk management.
Insurance Claim Fraud Analysis Using AI Techniques
Project Overview

This project is about finding suspicious insurance claims that might be fraudulent. Fraudulent claims cost insurance companies a lot of money, so detecting them early helps save money and prevent misuse.

We used AI techniques to analyze past insurance claims and predict which claims might be suspicious.

Goal

Identify potentially fraudulent insurance claims.
Help insurance agents focus on high-risk claims for further investigation.
Understand patterns in the data that indicate fraud.

Tools Used

Python for data analysis and modeling
Pandas for handling and exploring data
Scikit-learn for creating prediction models
Matplotlib for making charts and graphs
Excel for checking and cleaning the data

Dataset Details
the dataset contains information about insurance claims. Some important columns:

Column	Description
AGE	Age of the person making the claim
MARITAL_STATUS	0 = Single, 1 = Married
EMPLOYMENT_STATUS	0 = Unemployed, 1 = Employed
NO_OF_FAMILY_MEMBERS	Number of family members
INSURANCE_TYPE	Type of insurance policy
PREMIUM_AMOUNT	Amount paid for the insurance
CLAIM_AMOUNT	Amount claimed
CLAIM_STATUS	0 = Rejected, 1 = Approved
INCIDENT_SEVERITY	0 = Low, 1 = Medium, 2 = High
ANY_INJURY	0 = No, 1 = Yes
POLICE_REPORT_AVAILABLE	0 = No, 1 = Yes
AGENT_ID / AGENT_NAME	Insurance agent handling the claim
VENDOR_ID / VENDOR_NAME	Vendor details for the claim
Fraud_Predicted	AI model prediction: 0 = Not Fraud, 1 = Fraud
Model Results

The AI model predicts whether a claim is fraudulent.

Accuracy: ~90% (correct predictions overall)

Problem: There are very few fraudulent claims, so the model sometimes misses frauds.

Confusion Matrix Example:

[[1790  118]
 [  86    6]]
This means the model predicts most normal claims correctly but struggles to detect fraud.

Outcome

Highlighted suspicious claims for further checking.
Helped understand patterns like high claim amounts, incident severity, or missing police reports that could indicate fraud.
Gave a starting point for better fraud detection using AI.
