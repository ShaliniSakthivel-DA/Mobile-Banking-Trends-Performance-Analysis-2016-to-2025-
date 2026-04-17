# Mobile-Banking-Trends-Performance-Analysis (2016 to 2025) - Excel & PowerBI

This project analyzes mobile banking data using Excel and Power BI to understand transaction trends, customer behavior, and bank performance.

**1. Project Objective:**

•     Analyze mobile banking transactions and customer activity

•     Compare performance across bank types (Public, Private, Co-operative)

•     Identify growth trends and digital adoption patterns

•     Generate insights for better business decision-making

**2. Data Sources:**

•	Sources: India Data Portal https://indiadataportal.com/p/reserve-bank-of-india/r/rbi-bankwise_mobile_banking_transactions-in-mn-aaa

•	Timeline: January 2016 to December 2025

•	Domain: Financial Analytics

•     45+ Rows and 14 Column

**3. Tools & Technologies**

•     Microsoft Excel

•     Power Query

•     Power BI

**3. Problem Statement:**

•     Understand the growth of mobile banking over time

•     Analyze transaction volume and transaction value

•     Study customer activity and usage patterns

•     Compare performance of different bank types (Public, Private, Co-operative)

•     Identify top and low performing banks

•     Analyze state-wise adoption of mobile banking

•     Understand customer segments (Small, Medium, Large)

•     Identify trends and patterns for better decision-making

**4.	Attribute Details:**

The dataset includes fields such as id, date, month, year, bank name, state, number and amount of transactions, active customers, transaction category, bank type, average transaction value, customer tier, and transaction frequency per customer, used to analyze mobile banking performance and customer behavior.

**5.	Data Preparation (Excel / Power Query/ Power BI):**

•     Removed duplicates and handled missing values

•     Standardized data formats and data types

**Created new columns:**

     •     Transaction Category (Small / Medium / Large)

     •     Customer Tier

     •     Average Transaction Value

     •     Transaction Frequency per Customer

 **Built a Calendar Table for time-based analysis**

**6.	Fact and Dimension Table Creation:**

•    Used Star Schema
     
•	Fact Table: Mobile Banking Statistics 

•	Dimension Tables: Calendar Table

•    Created relationships for time intelligence analysis

<img width="700" height="350" alt="image" src="https://github.com/user-attachments/assets/5cfdc0dd-e761-418f-88f9-489ee5774fe0" />


**7. DAX Measures & Calculated Columns:**

**Calculated Measure:**

Implemented DAX measures for key metrics, including:

•	Total Transactions – Represents the total number of transactions 

•	Total Amount – Represents the overall transaction value 

•	Total Active Customers – Shows the number of customers actively performing transactions 

•	Total Customers – Represents the total number of customers in the dataset 

•	Total Banks – Represents the total number of unique banks 

•	Transaction Value – Indicates the average value per transaction 

•	Growth Percentage – Measures the percentage change between current and previous period 

•	YoY Growth % – Measures the year-over-year percentage change in performance 

•	Cumulative Transactions – Displays the running total of transactions over time

**Calculated Columns:**

•	Month: Represents the month of the transaction.

•	Year: Represents the year of the transaction.

•	State: Identifies the state where the bank operates.

•	Transaction Frequency per Customer (Integer): Calculates the average number of transactions per customer.

•	Customer Tier: Segmented customers into small, medium, and large tiers.

•	Transaction Frequency per Customer: Derived the average number of transactions per customer.

•	Data Categorization:

Classified data based on Transaction Category, Bank Type, and Customer Tier for better segmentation and analysis. 

**Table Creation:**

•     Built a Calendar table with attributes like Year, Month, Quarter, and Day to enable time based filtering and trend analysis.
   
•     Created a BankWiseCount table to store aggregated bank level information such as Record Count, Total Transactions, and Total Amount.
   
**8.	 Analysis and Visualizations (Power BI):**

**Bank Performance Analysis**

•	KPI Cards for transactions, amount, and customers

•     Bank-wise comparison (Bar & Column Charts)

•     Bank Type distribution (Donut Chart)

•     Efficiency analysis (Scatter Plot)

<img width="700" height="350" alt="image" src="https://github.com/user-attachments/assets/a2312aa1-5b92-465c-9edd-e40f2f0c3da1" />

**Customer Behavior & Regional Insights** 

•	Customers by State

•     Customer Tier segmentation

•     State-wise transaction analysis (Map)

•     Spending behavior by region

<img width="700" height="350" alt="image" src="https://github.com/user-attachments/assets/4788d8fa-b4f1-4a9e-b3e2-be00313905a8" />

**Trend & Time Analysis**

•	Year-wise transaction growth

•     YoY Growth trends

•     Monthly transaction patterns

•     Forecasting future growth

**9.	 Insights & Conclusions:**

•     Mobile banking transactions show consistent growth from 2016 to 2025

•     Growth peaked in early years and is now stabilizing

•     Public sector banks dominate in customer base and transactions

•     Top banks contribute the majority of transaction volume

•     Urban states show higher adoption compared to rural areas

•     Large customers contribute the highest transaction value

<img width="700" height="350" alt="image" src="https://github.com/user-attachments/assets/0299b395-70d5-4715-ba8e-0a4422b6146a" />

**10.	 Conclusion:**

Mobile banking has grown significantly over the years with strong digital adoption.This analysis helps understand bank performance, customer behavior, and future growth trends, enabling data-driven decisions.

#dataanalyst #dataanalysis #PowerBi #Excel
