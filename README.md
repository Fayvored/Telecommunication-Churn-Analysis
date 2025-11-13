## Churn Analysis 
**Introduction**

The telecommunications company provides phone and internet services to more than 7,000 customers across California. However, they are facing a major business challenge, customer churn. Customer churn refers to when customers discontinue using the company’s services and move to competitors. This loss of customers negatively affects revenue, brand image, and overall growth potential.

The company wants to understand why customers are leaving, who they are, and what steps can be taken to retain them. This requires a detailed data-driven investigation of customer demographics, service usage, subscription types, contract durations, and payment behaviors.


This project focuses on analyzing [Source Dataset](https://drive.google.com/drive/folders/1LoO11nffFrHjLtpYsNycqTZuE2g6-WQA?usp=drive_link) using [Power BI]. The goal is to identify key patterns (churn rate) in [Telecommunication Industry] to inform [Stakeholder/Decision].

**Project Description**

**Problem Statement:** [The client needed to understand churn rates -why and who is leaving and  to help them improve retention and boost satisfaction...]

**Dataset Overview:** [ "Telecom Customer Churn dataset, 7,044 rows, 38 columns."] (https://drive.google.com/drive/folders/1LoO11nffFrHjLtpYsNycqTZuE2g6-WQA?usp=drive_link) 

**Tool Stack:** [ Microsoft Excel (Power Query), Power BI]

Project Aim / Key Business Questions
[Question 1 What is the current churn rate?]
[Question 2: Which customer demographics are most affected?]
[Question 3: Which service types or contract models are linked to higher churn? ]
[Question 4: Do payment methods or billing patterns influence churn?]
[Question 5: How does customer tenure affect churn probability?]

**Preparation of the Dataset: Cleaning and Transformation**
Missing Value Handling: [ Nulls in usage metrics replaced with 0.]
Data Type Assignment: [Ensured all columns were set to the correct type (numeric, date, text).]
Uniqueness Check: [Confirmed no duplicate records based on the primary identifier (e.g., Customer ID).]
Data Enrichment/Merging: [Dataset merged with [Zipcode Population dataset] using [Zip Code] to add demographic context.]

**Data Visualization & Dashboard Structure**
Key Performance Indicators (KPIs) Analyzed:
[KPI 1: Total Customer]
[KPI 2: Churn Rate]
[KPI 3: Total Churned Customers]
[KPI 4: Total Revenue]
[KPI 5: Revenue Lost to Churn]

[Chart Type]: Churn Rate by Tenure in Months (Line Chart) 
[Chart Type]: Churn Rate by Contract (Bar Chart) 
[Chart Type]: Churn Rate by Age Group (Bar Chart) 
[Chart Type]: Churn Rate by Payment Method (Bar Chart)
[Chart Type]: Churn Rate by Internet Type (Bar Chart)

**View Dashboards**
[Dashboard] (https://drive.google.com/file/d/1Njblq_NghFs9eQGr7gXwiJR5_HaHhusz/view?usp=drive_link)

**Insights from the Data Analysis**
[Insight 1]: [Contract Type is the Biggest Churn Driver: The Month-to-Month contract is extremely unstable, driving a 46% churn rate. This is significantly higher than One-Year (11% churn) and Two-Year (3% churn) contracts. Furthermore, Month-to-Month contracts account for the largest portion of Revenue Lost to Churn ($2.49 Million)]

[Insight 2]: [New Customers are Highly Vulnerable: The Churn Rate by Tenure in Months line chart shows that churn is highest immediately after joining (around 60% in the first few months) and decreases as customer tenure increases. This points to severe friction or dissatisfaction during the initial onboarding period.]

[Insight 3]: [Senior Customers and Specific Services/Payments are High Risk: The Senior age group has the highest churn rate at 31%. Additionally, customers using Mailed Check (37%) and Bank Withdrawal (34%) payment methods show higher churn compared to Credit Card (14%). The Fiber Optic internet type also exhibits a high percentage of churned customers (41%).]

**Recommendations from the Data Analysis**
[1]: [Incentivize Long-Term Contracts: Immediately create aggressive promotional offers (e.g., significant discounts, free services) for customers to move from Month-to-Month contracts to One- or Two-Year agreements to drastically increase stability and reduce financial loss]

[2]: [Overhaul the Onboarding Experience: Launch a dedicated 90-Day Onboarding Program focusing intensive retention efforts and high-touch customer support during the first three months of service to address the initial 60% churn peak seen in new customers.]

[3]: [Payment: Offer financial incentives (e.g., a small bill credit) to customers using Mailed Check or Bank Withdrawal to switch to automated Credit Card payments, reducing payment friction.
Service/Demographics: Investigate potential stability/quality issues with the Fiber Optic service and develop specialized, simplified support channels for the Senior age group to improve their experience..]

