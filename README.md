# financial-loan-data-analysis
End-to-end financial loan data analysis using Python, Pandas, and data visualization to track KPIs, analyze good vs bad loans, and identify trends across time, region, and borrower attributes.
Great 👍
I’ve reviewed your **problem statement, dataset, and notebook**, and based on what you’ve done, here is a **professional, GitHub-ready `README.md`** for your **Data Analytics project**.

I’ve aligned it **exactly** with:

* Your BRD (Business Requirement Document)
* The KPIs you calculated
* All the visualizations you created in the notebook


---

 📊 Financial Loan Data Analysis Project

📌 Project Overview

This project focuses on analyzing **financial loan data** to evaluate lending performance, borrower behavior, and portfolio health. The analysis provides key insights into loan applications, funded amounts, repayments, and borrower characteristics using **Python-based data analytics and visualization** techniques.

The goal is to support **business decision-making** by tracking KPIs, identifying trends, and comparing **Good Loans vs Bad Loans**.

---

🎯 Problem Statement

The objective of this project is to:

* Monitor **loan performance metrics**
* Identify **seasonal and regional trends**
* Assess **borrower risk and repayment behavior**
* Compare **good loans and bad loans**
* Present insights through **clear visualizations**

This analysis follows structured business requirements defined in the BRD. 

---

 📂 Dataset Description

* **Source:** Financial Loan Dataset (Excel)
* **File:** `financial_loan.xlsx`
* **Records:** Loan-level transactional data
* **Key Columns:**

  * `id`
  * `issue_date`
  * `loan_amount`
  * `total_payment`
  * `int_rate`
  * `dti`
  * `loan_status`
  * `term`
  * `emp_length`
  * `purpose`
  * `home_ownership`
  * `address_state`

---

 🧰 Tools & Technologies Used

* **Python**
* **Pandas** – Data cleaning & aggregation
* **Matplotlib** – Data visualization
* **Plotly Express** – Interactive treemap visualization
* **Jupyter Notebook**
* **Excel** – Dataset source

---

 📊 Key Performance Indicators (KPIs)

 🔹 Loan Portfolio KPIs

* Total Loan Applications
* Month-to-Date (MTD) Loan Applications
* Total Funded Amount
* MTD Total Funded Amount
* Total Amount Received
* MTD Total Amount Received
* Average Interest Rate
* Average Debt-to-Income Ratio (DTI)

---

 ✅ Good Loan vs ❌ Bad Loan Analysis

 Good Loans (`Fully Paid`, `Current`)

* Good Loan Application Percentage
* Good Loan Applications Count
* Good Loan Funded Amount
* Good Loan Total Amount Received

 Bad Loans (`Charged Off`)

* Bad Loan Application Percentage
* Bad Loan Applications Count
* Bad Loan Funded Amount
* Bad Loan Total Amount Received

This comparison helps assess **credit risk and portfolio quality**.

---

 📈 Visualizations & Insights

 📅 Monthly Trends (Issue Date)

* Total Loan Applications
* Total Funded Amount
* Total Amount Received
  👉 Identifies **seasonality and growth trends**

 🌍 Regional Analysis (State-wise)

* Total Funded Amount by State
  👉 Highlights **regional lending concentration**

⏳ Loan Term Analysis

* Funded Amount by Loan Term (36 vs 60 months)
  👉 Shows **borrower preference and risk distribution**

 👨‍💼 Employment Length Analysis

* Funded Amount by Employment Length
  👉 Assesses **employment stability impact**

 🎯 Loan Purpose Analysis

* Funded Amount by Loan Purpose
  👉 Reveals **primary borrowing reasons**

 🏠 Home Ownership Analysis

* Treemap of Funded Amount by Home Ownership
  👉 Visualizes **home ownership influence on lending**

---

 🔍 Methodology

1. Data loading and preprocessing
2. Date formatting and feature engineering
3. KPI calculations using Pandas
4. Group-by aggregations
5. Visualization using Matplotlib & Plotly
6. Business interpretation of results

---

 ▶️ How to Run the Project

1. Clone the repository
2. Install required libraries:

   ```bash
   pip install pandas matplotlib plotly
   ```
3. Open Jupyter Notebook:

   ```bash
   jupyter notebook
 
4. Run `financial data analysis.ipynb`



📁 Project Structure

📦 Financial-Loan-Analysis
  📊 financial_loan.xlsx
  📓 financial data analysis.ipynb
  📄 Problem Statement.pptx
 📘 README.md


🚀 Key Business Insights

* Majority of loans are **good loans**, indicating a healthy portfolio
* Certain states dominate loan funding
* 36-month loans contribute more to funded amounts
* Employment length and home ownership strongly influence loan approvals
* Seasonal patterns exist in loan issuance


Just tell me what you want next 👍
