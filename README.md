Indonesia Credit Risk & Fraud Analysis

Credit Risk Assessment and Fraud Detection Dashboard using Python and Power BI

 1. Project Overview

This project focuses on analyzing credit risk characteristics and identifying fraud patterns using a synthetic Indonesian credit risk dataset containing 15,000 records.
The analysis explores customer profiles, credit scores, debt-to-income (DTI) ratios, loan characteristics, and fraud distribution. Python was used for data preparation and exploratory data analysis (EDA), while Power BI was used to develop an interactive dashboard.

 2. Project Objectives

The main objectives of this project are:

- Analyze customer credit risk characteristics.
- Examine fraud distribution across different customer categories.
- Identify patterns associated with fraudulent transactions.
- Explore relationships between credit scores, DTI ratios, loan amounts, and interest rates.
- Present analytical findings through an interactive Power BI dashboard.

 3. Dataset Description

| Attribute | Description |
|---|---|
| Dataset Name | Indonesia Credit Risk Dataset |
| Total Records | 15,000 |
| Total Features | 19 |
| Fraud Cases | 293 |
| Non-Fraud Cases | 14,707 |
| Fraud Rate | 1.95% |
| Missing Values | None identified after data preparation |
| Dataset Type | Synthetic Dataset |

The dataset contains customer and loan-related information, including:

- Credit Score
- Income Category
- DTI Ratio
- Loan Amount
- Interest Rate
- Loan Category
- Loan Intent
- Loan Status
- Age Category
- Indonesia Province
- Fraud Status

Note: This dataset is synthetically generated for educational and portfolio purposes. It does not represent actual Indonesian banking customers or real financial transactions.

 4. Tools & Technologies

The following tools were used:

- Python: Data preparation and exploratory data analysis.
- Pandas: Data manipulation and analysis.
- NumPy: Numerical operations.
- Google Colab: Python development environment.
- Power BI: Data visualization and interactive dashboard development.
- GitHub: Project documentation and portfolio hosting.

 5. Data Preparation

The data preparation process included:

1. Loading the dataset into Python.
2. Understanding dataset structure and variables.
3. Checking data types and data quality.
4. Examining missing values.
5. Preparing the cleaned dataset for further analysis.

The prepared dataset was exported as a CSV file for use in Power BI.

 6. Exploratory Data Analysis (EDA)

Exploratory Data Analysis was conducted to understand the distribution and characteristics of the dataset.
The analysis included:

- Descriptive statistics.
- Fraud distribution analysis.
- Credit score analysis.
- DTI ratio analysis.
- Income category analysis.
- Loan amount and interest rate analysis.
- Customer segmentation.

 7. Power BI Dashboard

The Power BI dashboard consists of three analytical pages.

 Page 1: Dashboard Overview

Provides a general overview of the dataset through key performance indicators and visualizations.

Main KPIs:
- Total Customers: 15,000
- Total Fraud Cases: 293
- Fraud Rate: 1.95%

 Page 2: Fraud Analysis & Insights

Focuses on identifying fraud patterns across different customer and loan categories.
Key analysis:
- Fraud Cases by DTI Category.
- Fraud Rate by Age Category.
- Fraud Cases by Loan Intent.
- Average Credit Score by Fraud Status.
- Fraud Cases by Income Category.
- Fraud Cases by Province.
- Fraud Cases by Loan Status.

 Page 3: Credit Risk Analysis
Examines credit risk characteristics and loan distribution.

Key analysis:
- Average Credit Score by Income Category.
- Average DTI Ratio by Income Category.
- Average Loan Amount by Loan Category.
- Average Credit Score by Loan Status.
- Average Loan Amount by Age Category.
- Average Interest Rate by Loan Category.

The dashboard also includes interactive slicers to filter the analysis by loan status, loan intent, loan category, and Indonesian province.

 8. Key Findings

 Fraud Analysis

- The dataset contains 293 fraud cases, representing 1.95% of all records.
- Low DTI category recorded the highest fraud count, with 116 cases.
- Young Adult customers recorded the highest fraud rate at 2.14%.
- Medium income category recorded the highest fraud count, with 138 cases.
- DKI Jakarta recorded the highest fraud count among the reported provinces, with 82 cases.
- Customers classified as fraud had an average credit score of 482.42, compared with 577.22 for non-fraud customers.
- Loan Status 1 recorded 259 fraud cases, while Loan Status 0 recorded 34 cases.

 Credit Risk Analysis

- Medium income category recorded the highest average credit score at 553.46.
- Low income category showed the highest average DTI ratio at 32.46.
- Large loan category had the highest average loan amount, approximately Rp831.15 million.
- Loan Status 0 recorded an average credit score of 598.85, compared with 516.45 for Loan Status 1.
- Young Adult customers recorded the highest average loan amount at approximately Rp302.87 million.
- Average interest rates were approximately 21% across the three loan categories.

 9. Conclusion

This project demonstrates how Python and Power BI can be used together to prepare, explore, analyze, and visualize credit risk data.
The findings provide an overview of fraud distribution and credit risk characteristics across different customer and loan categories.
The interactive dashboard helps users explore the dataset and identify patterns that may support further risk assessment.
Because the dataset is synthetic, the findings should be interpreted as analytical exercises rather than evidence of actual banking fraud patterns.

 10. Project Structure

```text
Indonesia-Credit-Risk-Fraud-Analysis/
│
├── Dashboard/
│   └── Indonesia_Credit_Risk_Fraud_Analysis.pbix
│
├── Dataset/
│   └── indonesia_credit_risk_cleaned_FIX_1.csv
│
└── README.md
```


Project Category: Data Analytics | Credit Risk Analysis | Fraud Detection

Author: Alhimni Rusydi (Data Analyst Portfolio Project)
