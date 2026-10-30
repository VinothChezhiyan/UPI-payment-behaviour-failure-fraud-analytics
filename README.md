# UPI Payment Behaviour, Failure and Fraud Analytics Using 2024 Transaction Data

## Overview
This project analyses 250,000 UPI (Unified Payments Interface) transactions from 2024 to understand customer, merchant and bank behaviour, and to find where payments fail or face fraud. Data was cleaned and explored in Python (Google Colab), and two interactive dashboards were built in Power BI.

## Dataset
- UPI Transactions 2024, from Kaggle
- 250,000 rows and 28 columns after cleaning
- Cleaned dataset (upi_cleaned.csv): [Download from Google Drive](https://drive.google.com/file/d/16UE4SAVgbqSgXXO-TgxgEgBOUAZldHO9/view?usp=sharing)

## Tools
- Python (pandas), Google Colab
- Power BI Desktop, DAX

## Repository contents
- Colab notebook (.ipynb): problem definition, cleaning, EDA and insights
- `UPI_Dashboard.pbix`: Power BI file with both dashboards
- `UPI_Dashboard.png`: Dashboard 1, Payment Behaviour, Failure and Fraud Analytics
- `UPI Customer, Merchant & Bank Behaviour Analytics.PNG`: Dashboard 2, Customer, Merchant and Bank Behaviour Analytics
- `UPI_Project_Documentation.docx`: full project documentation

## Key insights
- Overall failure rate is 4.95% and fraud rate is 0.19%
- 3G has the highest failure rate (5.22%), and 5G and WiFi have the lowest (4.86%)
- Very High amount transactions have the highest fraud rate (0.30%)
- Evening (31%) and afternoon (28%) carry about 60% of transactions
- The 26-35 age group is the largest (about 35%), and SBI, HDFC and ICICI send about 52% of transactions

## Recommendations
- Improve reliability on 3G
- Review the hours with the highest failure rates and add capacity
- Add extra verification for very high-value transactions
- Track failure rate and fraud rate monthly on a dashboard

## Author
Vinoth
