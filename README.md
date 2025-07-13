# Bank_Report_Power_BI
# 🏦 Bank Loan Report – Good Loans vs Bad Loans

This project presents an insightful analysis of a bank’s loan portfolio by comparing **Good Loans vs Bad Loans**. The dashboard helps stakeholders understand loan default patterns, customer risk profiles, and factors affecting repayment behavior.

---

## 🎯 Objective

- Analyze loan applications and outcomes to determine performance.
- Identify factors contributing to **loan defaults**.
- Segment customers based on creditworthiness.
- Support strategic decisions for improving loan approval and recovery.

---

## 📁 Dataset Overview

- **Source**: (e.g., Kaggle, bank's internal system, UCI dataset)
- **File**: `bank_loan_data.csv`
- **Rows**: ~50,000 loan applications
- **Key Columns**:
  - `loan_id` – Unique loan identifier  
  - `customer_id` – Unique customer  
  - `loan_amount`, `interest_rate`, `term`  
  - `income`, `employment_status`, `home_ownership`  
  - `credit_score`, `age`, `loan_purpose`  
  - `loan_status` – "Good" or "Bad"

📥 Sample dataset:  
[Example dataset on Kaggle](https://www.kaggle.com/datasets/itsmesunil/bank-loan-modelling)

---

## 📊 Dashboard Features

- ✅ **Good vs Bad Loan Ratio**
- 📈 **Loan Default Trends Over Time**
- 📍 **High Risk Segments by Income, Credit Score, and Age**
- 💳 **Loan Purpose Analysis (Education, Car, Home, etc.)**
- 🔢 **KPI Cards** for:
  - Total Loans
  - Default Rate
  - Average Credit Score
  - Total Loan Amount Disbursed
- 🧠 **Customer Segmentation** based on default probability

📸 **Dashboard Preview:**
(Add screenshot here if available)

---

## 🚀 How to Use

### Power BI:
1. Open `Bank_Loan_Report.pbix` in Power BI Desktop.
2. If dataset path is broken, go to **Transform Data > Edit Source** and update file path.
3. Click **Refresh** to update all visuals.

### Python:
Run `loan_analysis.py` to generate summary stats, graphs, and insights.

---

## 📂 File Structure

