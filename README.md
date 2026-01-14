# Luxury-Retail-Risk-Compliance-Platform
To build a practical, end-to-end data science project demonstrating proficiency with core industry tools (Python/Pandas, SQL, Power BI) while applying core concepts of risk management (e.g., fraud detection, compliance) in an industry I’m passionate about: Luxury Retail.

# Luxury Retail Risk & Compliance Monitoring Platform

## 1. Problem Statement

### Luxury Retail Challenge
High-end retailers face a unique risk profile characterized by low transaction volume but **extremely high average transaction value (ATV)**. A single fraudulent transaction can result in significant financial loss and damage to brand reputation.

### Operational Risk
Current processes often lack automated controls, leading to delays in identifying suspicious activity and compliance breaches (e.g., missing key payment data).

---

## 2. Project Goal & Business Objective

### Goal
To build a practical, end-to-end data science project demonstrating proficiency with core industry tools (**Python/Pandas, SQL, Power BI**) while applying core concepts of **risk management** (e.g., fraud detection, compliance) in an industry I’m passionate about: **Luxury Retail**.

### Business Objective

* **Mitigate Risk:** Design a scalable platform to shift from reactive loss recovery to **proactive risk mitigation**.
* **Establish Internal Control:** Develop automated compliance checks to ensure all transactional data adheres to required audit standards, creating a robust, reliable, and **auditable process control**.

---

## 3. My Approach (The Technical Workflow)

The project follows a standard Extract, Transform, Load (ETL) pipeline:

* **Data Ingestion & Transformation (Python/Pandas):** Use Python and the **Pandas** library to load raw transaction data, perform cleaning, and convert key fields (like time/date) for analysis.
* **Compliance Layer (Python/Pandas):** Implement specific business rules to flag or remove transactions that fail mandatory checks (e.g., missing `Payment_Method` or unusual age/location patterns).
* **Data Persistence & Modeling (SQL):** Load the cleaned, compliant, and pre-scored data into an **SQL database**. This models the data into a structured format ready for consumption by BI tools.
* **Visualization & Monitoring (Power BI):** Connect **Power BI** to the SQL database to create an interactive dashboard for risk officers to monitor key metrics and drill down into flagged transactions.
## Key Performance Indicators (KPIs)

| Metric | Purpose | Resume Impact |
| :--- | :--- | :--- |
| **Transaction/Compliance Breach Rate** | Measures the percentage of transactions failing internal control checks (e.g., missing data, non-compliant amount ranges). | Demonstrates ability to **design and enforce process controls**. |
| **High-Value Transaction Volume** | Tracks the volume of purchases exceeding a set risk threshold (e.g., >$250) across different locations. | Shows understanding of **quantifying high-risk exposure** in luxury retail. |
| **Anomaly Detection Rate** | Measures the percentage of transactions flagged as fraudulent (Fraud\_Flag=1 in the dataset) that the system correctly isolates. | Highlights **data analysis and fraud detection skills**. |


## Project Tech Stack

| Technology | Role in the Project | Key Function (What it will do) |
| :--- | :--- | :--- |
| **Python** | Automation & Data Manipulation | The core programming language. It will handle the entire workflow, from reading the initial CSV data to performing complex cleaning, processing logic, and outputting the final report files. |
| **Pandas** | Data Structuring & Analysis | Python's primary library for working with structured data. It will be used to load the CSV, apply **data cleaning rules**, perform filtering based on compliance criteria, and calculate risk metrics. |
| **SQL** | Data Persistence & Querying | Used to store the processed and cleaned transaction data in a relational database. This demonstrates knowledge of **data modeling** and the ability to retrieve (query) specific information needed for risk analysis and reporting. |
| **Power BI** | Business Intelligence (BI) & Visualization | The platform for building the final "Risk & Compliance Monitoring Dashboard." It will connect to the SQL data and visualize **Key Risk Indicators (KRIs)** like fraud rates, high-value transactions, and geographic compliance breaches. |

## Dashboards
<img width="702" height="500" alt="image" src="https://github.com/user-attachments/assets/d2866994-dec5-4c57-853d-8e7cd35b6f5e" />
<img width="690" height="494" alt="image" src="https://github.com/user-attachments/assets/82df672c-4885-4d6c-aa17-88db2d557b40" />


This dashboard identifies Bronze and Silver tiers as the primary targets for fraud in this dataset, with 24 and 16 confirmed cases respectively. By filtering for these high-risk clusters, security teams can prioritize investigations where the 'Fraud Flag' is most concentrated.
