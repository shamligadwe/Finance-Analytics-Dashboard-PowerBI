# Finance-Analytics-Dashboard-PowerBI
📊Project Overview

This project is an interactive Finance Analytics Dashboard developed using
Microsoft Power BI to provide insights into financial transactions,
customer behavior, transaction performance, fees, and tax analysis.

The project was developed based on a Business Requirements Document (BRD)
and uses customer and financial transaction data stored in Excel files.

The dashboard enables users to analyze financial performance across
different years, transaction types, customer segments, states, genders,
occupations, and transaction categories.



🎯 Business Objective

The main objective of this project is to transform raw customer and
financial transaction data into meaningful business insights that can
support financial performance monitoring and decision-making.

The dashboard helps answer questions such as:

- What is the total transaction amount?
- How many transactions were processed?
- What is the average transaction value?
- How much fee and tax were generated?
- Which transaction types contribute the most revenue?
- Which customer segments generate the highest tax?
- Which states contribute the highest tax?
- What is the transaction success/failure/pending distribution?
- How does financial performance vary by month?
- How does performance differ between male and female customers?


 🗂️ Data Sources

The project uses the following data sources:

 1. Customer Data
Excel file containing customer-related information such as:

- Customer details
- Gender
- Customer segment
- Occupation
- Category

 2. Finance Transaction Data
Excel file containing financial transaction information such as:

- Transaction ID
- Customer
- Transaction Date
- Transaction Type
- Transaction Status
- Transaction Amount
- Fees
- Tax
- State

 3. Business Requirements Document
A PDF containing the business requirements and reporting expectations
used as a reference for designing the Power BI solution.

---

 🛠️ Tools & Technologies

- Microsoft Power BI
- Power Query
- DAX
- Microsoft Excel
- Data Modeling
- Data Visualization
- Business Requirements Analysis



 🔄 Project Workflow

The project followed an end-to-end BI development process:

1. Reviewed the Business Requirements Document
2. Analyzed the available Excel datasets
3. Imported data into Power BI
4. Cleaned and transformed data using Power Query
5. Created relationships between datasets
6. Developed calculated measures using DAX
7. Designed interactive dashboard pages
8. Added slicers and dynamic filtering
9. Validated dashboard outputs against business requirements
10. Created the final Power BI report



 📈 Key KPIs

The dashboard provides the following key performance indicators:

- Total Amount
- Total Transactions
- Average Transaction Value
- Total Fees
- Total Tax

The KPIs dynamically respond to the selected filters.


 Overview Analysis

The Overview Analysis page provides a high-level view of financial
performance.

It includes:

- Total Amount
- Total Transactions
- Average Transaction Value
- Total Fees
- Total Tax
- Monthly Tax Trend
- Tax by Transaction Status
- Tax by Customer Segment
- Tax by State
- Transaction Type Analysis
- Tax by Gender

Interactive filters are available for:

- Year
- Dynamic Metric
- Occupation
- Category



 Transaction Analysis

The Transaction Analysis page provides detailed transaction-level
information.

Users can analyze:

- Transaction ID
- Customer Name
- Transaction Date
- Transaction Type
- Transaction Status
- Gender
- Customer Segment
- State
- Total Amount
- Total Fees
- Total Tax

This page allows users to drill into individual transactions while
maintaining the selected dashboard filters.



💡 Key Insights

Based on the dashboard, some of the major observations include:

- Retail customers contribute the highest share of total tax among
  customer segments.
- Successful transactions represent the majority of transaction status.
- Maharashtra contributes the highest tax among the states displayed.
- Loan EMI and Transfer are among the major contributors to transaction
  amount.
- The dashboard shows monthly variation in tax generation throughout the
  year.
- Tax contribution is relatively balanced between male and female
  customers.


 📷 Dashboard Preview

 Overview Analysis

 Transaction Analysis





 📁 Project Structure


Finance-Analytics-Dashboard-PowerBI/
│
├── README.md
│
├── PowerBI/
│   └── Finance_Analytics_Dashboard.pbix
│
├── Data/
│   ├── Customer_Data.xlsx
│   └── Finance_Transaction_Data.xlsx
│
├── Business-Requirements/
│   └── Business_Requirements.pdf
│
└── Screenshots/
    ├── Overview_Analysis.png
    └── Transaction_Analysis.png
