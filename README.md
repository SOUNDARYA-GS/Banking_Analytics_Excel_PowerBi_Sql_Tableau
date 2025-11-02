# 🏦 Banking_Analytics_Excel_PowerBi_Sql_Tableau

Analyzing **Banking Operations** data to track client activity, loan performance, and transaction behavior — providing key performance indicators (KPIs) and actionable insights for lending, collections, and branch operations through **Tableau**, **Power BI**, and **Excel** dashboards.

---

## 📌 Table of Contents
- [Overview](#-overview)
- [Business Problem](#-business-problem)
- [Dataset](#-dataset)
- [Tools & Technologies](#-tools--technologies)
- [Project Structure](#-project-structure)
- [Data Preparation & SQL](#-data-preparation--sql)
- [Key Insights & Findings](#-key-insights--findings)
- [Challenges Faced](#-challenges-faced)
- [Dashboard Overview](#-dashboard-overview)
- [How to Run This Project](#-how-to-run-this-project)
- [Final Recommendations](#-final-recommendations)
- [Author & Contact](#-author--contact)

---

## 🔎 Overview
This project delivers a comprehensive analytical solution for **core banking operations** — focusing on **loan portfolio performance**, **client retention**, **repayment behavior**, and **transaction monitoring**.

Interactive dashboards built in **Excel**, **Tableau**, and **Power BI** provide a unified, data-driven view of critical banking metrics.  
These dashboards empower teams to make faster, evidence-based decisions on lending, collections, and branch management, while also highlighting **risk areas** and **growth opportunities**.

---

## ❗ Business Problem
Modern banks face challenges in maintaining visibility across operations, loan quality, and transaction security — all of which are essential for **risk mitigation** and **strategic growth**.

This project addresses key questions such as:
- What is the current health of the loan portfolio in terms of recovery and repayment rates?
- Which branches are performing best across loan disbursement and profitability?
- How can the bank identify, monitor, and act on suspicious transactions efficiently?
- What does the Credit-to-Debit Ratio and Net Transaction Flow reveal about financial stability?

---

## 💾 Dataset
**Source:** Consolidated Banking Operations data covering Client, Loan, Repayment, and Transaction records.  
**Format:** Excel datasets merged and processed using **MySQL** for analysis and dashboard integration.

### Key Variables Tracked:
- Client ID, Branch Name  
- Loan Amount Disbursed, Funded Amount  
- Disbursement Date, Repayment Status (On-Time, Late, Default)  
- Total Credit Amount, Total Debit Amount  
- Transaction Date, Transaction Method  
- Suspicious Transaction Flag, Risk Score

### Data Preparation:
- Data cleaning, standardization, and aggregation in **MySQL**  
- Calculated key metrics including:
  - Client Retention Rate  
  - Principal Recovery Rate  
  - Credit-to-Debit Ratio  
  - Suspicious Transaction Frequency  

---

## 🛠 Tools & Technologies

| Category | Tool | Purpose |
|-----------|------|----------|
| Database | **MySQL** | Data cleaning, transformation, aggregation, and KPI computation (e.g., Total Clients, Loan Amounts, Credit/Debit Ratios). |
| Visualization | **Tableau** | Interactive Banking Dashboard — focusing on loan performance, branch distribution, and client retention. |
| Visualization | **Power BI** | Dynamic Debit & Credit Dashboard — visualizing transaction trends, ratios, and risk metrics. |
| Reporting | **Excel** | Quick KPI summaries, data validation, and static dashboard creation. |

---

## 📂 Project Structure
Banking_Analytics_Excel_PowerBi_Sql_Tableau/

├── src/

│   └── sql/               # SQL scripts for data transformation & KPI calculation

│

├── dashboards/

│   ├── tableau/           # Tableau Dashboards (.twbx)

│   ├── power_bi/          # Power BI Dashboards (.pbix)

│   └── excel/             # Excel Dashboards (.xlsx)

│

└── README.md              # Project Documentation


---

## 🧹 Data Preparation & SQL
**MySQL** was used for all key computations and transformations after merging multiple raw Excel datasets.

## ❓ Key Insights & Findings

### 🔹 Key Performance Indicators (KPIs)

| Dashboard | KPI | Result |
|------------|-----|---------|
| **Banking Dashboard** | Total Clients | 65K+ total clients |
|  | Active Clients | 36K+ active clients |
|  | Total Loan Disbursed | ₹713.5M total |
|  | Principal Recovery | 87% principal recovery |
|  | On-Time Repayments | 72% repayment punctuality |
| **Debit & Credit Dashboard** | Total Credit Amount | ₹128M |
|  | Total Debit Amount | ₹127M |
|  | Net Financial Flow | +₹318K |
|  | High-Risk Transactions | ₹36M flagged monthly |
|  | Suspicious Activity Cases | ~5,000 flagged per month |


# 📊 Banking & Transaction Analytics Dashboards

## 🏦 1️⃣ Banking Dashboard (Tableau / Power BI / Excel)

**Focus:** Loan portfolio, client metrics, and branch performance.  
**KPIs:**  
- Total Clients  
- Loan Disbursed  
- Principal Recovery Rate  

**Visuals Included:**  
- Loan Distribution by Branch  
- Repayment Behavior Split  
- Loan Disbursement Trend  

### 🖼️ Dashboard Preview
#### 🔹 Banking Dashboard (Power BI)
![Banking Dashboard - Power BI](images/Banking_Dashboard_PowerBI.png)

#### 🔹 Bank Analysis Dashboard (Tableau)
![Bank Analysis Dashboard - Tableau](images/Bank_Analysis_Tableau.png)

#### 🔹 Bank Analysis Dashboard (Excel)
![Bank Analysis Dashboard - Excel](images/Bank_Analysis_Excel.png)

---

## 💳 2️⃣ Debit & Credit Dashboard (Power BI / Excel)

**Focus:** Transaction activity and risk analysis.  
**KPIs:**  
- Credit-to-Debit Ratio  
- Suspicious Transactions  
- Net Flow  

**Visuals Included:**  
- Credit vs. Debit Split  
- High-Risk Transaction Frequency  
- Transaction Mode Breakdown  

### 🖼️ Dashboard Preview
#### 🔹 Bank Credit & Debit Dashboard (Power BI)
![Bank Credit & Debit Dashboard - Power BI](images/Bank_Credit_Debit_PowerBI.png)

#### 🔹 Debit Credit Dashboard (Excel)
![Debit Credit Dashboard - Excel](images/Debit_Credit_Excel.png)

---

## 🧠 SQL Queries (Bank Analytics)
#### 🔹 SQL Query Preview
![SQL Queries - Bank Analytics](images/SQL_Queries_Bank_Analytics.png)

---

## 📘 About
These dashboards provide deep insights into **banking operations**, **loan management**, and **transaction risk analysis**.  
They are designed for decision-makers to track **branch performance**, **credit-debit ratios**, and **repayment behaviors** in real time.

---

## 📂 File Structure


---

### 🔹 Business Insights

- **Client Growth:** Steady increase in both new and active clients, signaling strong acquisition but room for improved retention.  
- **Repayment Risk:** While recovery rate stands at 87%, delayed repayments remain a profitability concern.  
- **Branch Performance:** 176-DBS, Dhuri, and Mathura branches outperform others — offering best-practice benchmarks.  
- **Financial Stability:** Balanced Credit-to-Debit ratio and positive net flow (+₹318K) confirm sound operations.  
- **Fraud & Risk:** 5K suspicious transactions/month highlight a need for automated fraud monitoring.  

---

### ⚠️ Challenges Faced

| Challenge Area | Description |
|----------------|-------------|
| **Data Integration** | Combining multiple Excel sources into SQL with consistent schema and accurate joins. |
| **Branch Performance Gaps** | Significant variation across branch metrics made benchmarking complex. |
| **Repayment Risk** | Managing delayed and defaulted loans without impacting customer trust. |
| **Fraud Detection** | Continuous increase in flagged high-risk transactions required advanced tracking. |

---

### 📊 Dashboard Overview

#### 1️⃣ Banking Dashboard (Tableau / Power BI / Excel)
**Focus:** Loan portfolio, client metrics, branch performance.  
**KPIs:** Total Clients, Loan Disbursed, Principal Recovery Rate.  

**Visuals:**
- Loan Distribution by Branch  
- Repayment Behavior Split  
- Loan Disbursement Trend  

#### 2️⃣ Debit & Credit Dashboard (Power BI / Excel)
**Focus:** Transaction activity and risk analysis.  
**KPIs:** Credit-to-Debit Ratio, Suspicious Transactions, Net Flow.  

**Visuals:**
- Credit vs. Debit Split  
- High-Risk Transaction Frequency  
- Transaction Mode Breakdown  

---

### ▶ How to Run This Project

1. **Database Setup:**  
   Load the cleaned DBS Banking dataset into MySQL.

2. **Run SQL Scripts:**  
   Execute scripts from `src/sql/` to generate aggregated tables and KPI outputs.

3. **Open Dashboards:**  
   - **Tableau:** Open `.twbx` files for the Banking Dashboard  
   - **Power BI:** Open `.pbix` files for the Debit & Credit Dashboard  
   - **Excel:** Open `.xlsx` dashboards for static views and quick summaries  

4. **Explore Interactivity:**  
   Use filters such as *Branch*, *Date Range*, and *Product Type* to explore insights dynamically.

---

### ✅ Final Recommendations

- **Fraud Automation:** Implement automated detection and alerting for the 5,000+ monthly suspicious cases.  
- **Operational Excellence:** Replicate successful strategies from top-performing branches (176-DBS, Dhuri, Mathura).  
- **Collections Strategy:** Strengthen follow-up mechanisms for delayed loans to improve recovery beyond 87%.  
- **Client Retention:** Launch data-driven campaigns to sustain active client growth.  
- **Data Governance:** Standardize reporting frequency and ensure consistent KPI definitions across dashboards.  

---

### 👤 Author & Contact

**Soundarya G S**  
*Business/Data Analyst*  

📧 **Email:** [soundaryags948@gmail.com](mailto:soundaryags948@gmail.com)  
🔗 **LinkedIn:** [linkedin.com/in/soundarya-g-s](https://linkedin.com/in/soundarya-g-s)
