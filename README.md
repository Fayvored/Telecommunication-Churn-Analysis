#  Churn Analysis: Data-Driven Retention Strategy for Telecom

## **Table of Contents**
* [1.  Project Overview](#1-project-overview)
* [2.  Project Aims & Business Questions](#2-project-aims--business-questions)
* [3.  Data Preparation & Tools](#3-data-preparation--tools)
* [4.  Key Performance Indicators (KPIs)](#4-key-performance-indicators-kpis)
* [5.  Data Visualization & Dashboard](#5-data-visualization--dashboard)
* [6.  Key Insights](#6-key-insights)
* [7.  Actionable Recommendations](#7-actionable-recommendations)

---

## **1.  Project Overview**

### **Introduction**
The telecommunications company provides phone and internet services to more than **7,000 customers across California**. They are facing a major business challenge: **customer churn**—when customers discontinue services and move to competitors. This loss negatively impacts revenue, brand image, and overall growth potential.

The goal is to understand **why** customers are leaving, **who** they are, and what steps can be taken to retain them, requiring a detailed data-driven investigation of customer behavior.

### **Project Description**
This project focuses on analyzing [Source Dataset](https://drive.google.com/drive/folders/1LoO11nffFrHjLtpYsNycqTZuE2g6-WQA?usp=drive_link) using **Power BI**. The goal is to identify key patterns (churn rate) in the **Telecommunication Industry** to inform **retention strategies and boost customer satisfaction**
.

* **Problem Statement:** The client needed to understand **churn rates—why and who is leaving**—to help them improve retention and boost satisfaction.
* **Dataset Overview:** **Telecom Customer Churn dataset, 7,044 rows, 38 columns**.
* **Tool Stack:** **Microsoft Excel (Power Query), Power BI**.

---

## **2.  Project Aims & Business Questions**
The analysis seeks to answer these critical questions:

* **Question 1:** What is the **current churn rate**? 
* **Question 2:** Which customer **demographics** are most affected? 
* **Question 3:** Which **service types or contract models** are linked to higher churn? 
* **Question 4:** Do **payment methods or billing patterns** influence churn?
* **Question 5:** How does customer **tenure** affect churn probability? 

---

## **3.  Data Preparation & Tools**
The dataset was cleaned and transformed to ensure high integrity before analysis:

* **Missing Value Handling:** Nulls in usage metrics were replaced with $\mathbf{0}$ (zero).
* **Data Type Assignment:** Ensured all columns were set to the correct type (numeric, date, text).
* **Uniqueness Check:** Confirmed no duplicate records based on the primary identifier (**Customer ID**).
* **Data Enrichment/Merging:** Dataset was enriched by merging it with a **Zipcode Population dataset** using the **Zip Code** column to add demographic context.

---

## **4.  Key Performance Indicators (KPIs)**
The dashboard prominently features these core KPIs:

* **KPI 1:** Total Customers
* **KPI 2:** Churn Rate
* **KPI 3:** Total Churned Customers
* **KPI 4:** Total Revenue
* **KPI 5:** Revenue Lost to Churn

---

## **5.  Data Visualization & Dashboard**
The analysis is visualized using key charts to highlight the main drivers of churn:

* **Churn Rate by Tenure in Months** (Line Chart)
* **Churn Rate by Contract** (Bar Chart)
* **Churn Rate by Age Group** (Bar Chart)
* **Churn Rate by Payment Method** (Bar Chart)
* **Churn Rate by Internet Type** (Bar Chart)

### **View Dashboard**
[Telecom Churn Dashboard](https://drive.google.com/file/d/1Njblq_NghFs9eQGr7gXwiJR5_HaHhusz/view?usp=drive_link)

---

## **6.  Key Insights**

1.  **Contract Type is the Biggest Churn Driver:** The **Month-to-Month** contract is extremely unstable, driving a **46% churn rate**. This is significantly higher than One-Year (11%) and Two-Year (3%) contracts, and accounts for the largest portion of **Revenue Lost to Churn** (\$2.49 Million).
2.  **New Customers are Highly Vulnerable:** The **Churn Rate by Tenure** chart shows that churn is highest immediately after joining (around **60%** in the first few months) and decreases as customer tenure increases. This points to severe friction or dissatisfaction during the initial onboarding period.
3.  **Senior Customers and Specific Services/Payments are High Risk:** The **Senior** age group has the highest churn rate at **31%**. Furthermore, customers using **Mailed Check (37%)** and **Bank Withdrawal (34%)** show higher churn, and the **Fiber Optic** internet type exhibits a high percentage of churned customers (41%).

---

## **7.  Actionable Recommendations**

1.  **Incentivize Long-Term Contracts:** Immediately create **aggressive promotional offers** (e.g., significant discounts, free services) for customers to move from Month-to-Month contracts to One- or Two-Year agreements to **drastically increase stability and reduce financial loss**.
2.  **Overhaul the Onboarding Experience:** Launch a dedicated **90-Day Onboarding Program** focusing intensive retention efforts and high-touch customer support during the first three months of service to address the initial **60% churn peak** seen in new customers.
3.  **Target High-Risk Segments:**
    * **Payment:** Offer financial incentives (e.g., a small bill credit) to customers using Mailed Check or Bank Withdrawal to switch to **automated Credit Card payments**, reducing payment friction.
    * **Service/Demographics:** Investigate potential stability/quality issues with the **Fiber Optic** service and develop specialized, simplified support channels for the **Senior** age group to improve their experience.
