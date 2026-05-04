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

**Descriptive Analysis:**

**Bank Performance Analysis**

•     State Bank of India leads with ~167B transactions, followed by HDFC Bank (~55.7B) and Bank of Baroda (~41.4B), indicating strong dominance by a few top banks.

•     Public Sector Banks have ~8.4B active customers, significantly higher than Private Sector Banks (~4.0B) and Payment Banks (~1.6B).

•     State Bank of India leads in active customers (~5.66B), followed by HDFC Bank (~1.13B), while Kotak Mahindra Bank, ICICI Bank, and Axis Bank form the next tier.

•     Efficiency analysis highlights SBI as both a high-volume and high-value performing bank.

**Customer Behavior & Regional Insights**

•     Maharashtra leads with 5,441 active customers, followed by Gujarat (3,681) and Karnataka (2,042), showing concentration in major economic regions.

•     Large customers (~10.46B) contribute significantly more than Small (~3.63B) and Medium (~0.47B) segments.

•     Urban regions show higher adoption rates compared to rural areas.

•     Maharashtra leads in average transactions (~175M), followed by Punjab (~59M) and Delhi (~44M).

**Trend & Time Analysis**

•     Transaction count increased from 797 (2016) to 6,966 (2025), showing consistent growth.

•     Peak YoY growth occurred in 2018 (201.80%), followed by gradual stabilization to 28.78% in 2025.

•     Mobile banking usage has significantly increased, with a major surge in 2024.

**Diagnostic Analysis:**

•     The dominance of SBI is driven by its extensive branch network, strong digital infrastructure, and high trust among customers.

•     Public Sector Banks lead in customer base due to government backing and wider rural penetration.

•     High concentration in Maharashtra, Gujarat, and Karnataka is due to stronger economic activity, urbanization, and higher financial inclusion.

•     Large customers contribute more due to higher transaction volumes and business-related banking activities.

•     Rapid growth between 2018–2021 is linked to increased digital adoption, UPI expansion, and policy shifts towards cashless transactions.

•     Slowing growth after 2021 indicates market maturity and saturation in urban digital adoption.

**Predictive Insights:**

•     Mobile banking is expected to continue strong upward growth, driven by digital transformation and fintech innovations.

•     Transaction volumes are projected to steadily increase, though at a more stable growth rate compared to earlier years.

•     Public Sector Banks may continue leading in customer base, but Private Banks could gain share through better digital experiences.

•     Regional growth is likely to expand into semi-urban and rural areas as digital penetration increases.

•     Forecast trends suggest transaction values could nearly double between 2025 and 2030, indicating long-term scalability of digital banking.

<img width="700" height="350" alt="image" src="https://github.com/user-attachments/assets/0299b395-70d5-4715-ba8e-0a4422b6146a" />

**10.	 Conclusion:**

Mobile banking has grown significantly over the years with strong digital adoption.This analysis helps understand bank performance, customer behavior, and future growth trends, enabling data-driven decisions.

#dataanalyst #dataanalysis #PowerBi #Excel
