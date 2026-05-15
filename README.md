# Customer Retention & Revenue Analysis

## Project Overview
This project analyses retail transaction data to identify customer retention patterns, revenue trends and high-value customer segments using SQL and Power BI.

The project focuses on transforming raw transactional retail data into meaningful business insights and presenting them through a professional business dashboard.

Key Business Questions answered:
- What is the total revenue generated?
- What percentage of customers are repeat customers?
- Which customers generate the highest revenue?
- Which countries generate the most revenue?
- How does revenue change over time?
- How are customers distributed across customer value segments?

---

## Tools & Technologies
- PostgreSQL
- pgAdmin 4
- Power BI
- DAX
- Power Query

---

## Data Source

Dataset: Online Retail II Data Set from ML Repository  
Source: Kaggle  
Original source: UCI Machine Learning Repository  
Link: https://www.kaggle.com/datasets/mathchi/online-retail-ii-data-set-from-ml-repository  

The dataset contains transactions from a UK-based online retailer between 01/12/2009 and 09/12/2011.

---

## Licence

This dataset is licensed under the Open Data Commons Open Database License (ODbL) v1.0.

Licence details:
https://opendatacommons.org/licenses/dbcl/1-0/

---

## Project Workflow

### 1. Data Cleaning
- Inspected data structure
- Combined worksheets representing each year into one table
- Removed cancelled transactions
- Removed rows containing missing customer IDs
- Created revenue calculation field
- Standardised and validated data types

### 2. SQL Analysis
- Calculated total revenue
- Identified repeat customers
- Calculated repeat customer rate
- Analysed top customers by revenue
- Performed customer segmentation
- Analysed revenue by country
- Analysed monthly revenue trends

### 3. Power BI Dashboard Development
- Imported cleaned dataset into Power BI
- Created DAX measures for KPI calculations
- Designed KPI summary cards
- Built trend and segmentation visuals
- Applied dashboard formatting and layout improvements

## Key Insights
- The business demonstrates a strong repeat customer rate of approximately 72%, indicating high customer retention and repeat purchasing behaviour.
- Revenue is heavily concentrated among a relatively small group of high-value customers, highlighting the importance of customer retention strategies for high-value customers.
- The United Kingdom generates the overwhelming majority of total revenue, suggesting that the business is strongly dependent on its domestic market despite having international customers.
- Monthly revenue trends show clear seasonal fluctuations, with significant revenue increases toward the end of the year, likely reflecting increased holiday-season purchasing activity. This can help forecast demand, prepare inventory and plan marketing.

---

## Dashboard Features
- KPI cards for key business metrics
- Monthly revenue trend analysis
- Revenue by country visualisation
- Customer segmentation analysis
- High-value customer identification

---

## Dashboard

![Dashboard Preview](customer_retention_and_revenue_analysis.png)

---

## Skills Demonstrated
- Data cleaning
- SQL querying
- Customer retention analysis
- Revenue analysis
- DAX measures
- Dashboard design
- Business data storytelling
