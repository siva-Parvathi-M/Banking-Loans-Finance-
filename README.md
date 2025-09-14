# 📊 Banking & Financial Loan Risk Analysis (Power BI Dashboard)

## 📌 Project Overview

This project analyzes **loan applications data** to uncover patterns in **income, loan amount, credit score, default history, and approval status**.
The dashboard helps banks and financial institutions to:

* Understand customer profiles.
* Identify key risk factors.
* Track approval vs. rejection trends.
* Support data-driven lending decisions.

Dataset used: **cleaned\_banking & financial data** (Kaggle-based banking loan dataset).

---

## 🗂 Dataset Description

The dataset contains customer demographic, financial, and loan application details.

**Key Fields**:

* `person_age` → Applicant age
* `person_gender` → Gender
* `person_education` → Education level
* `person_income` → Annual income
* `person_emp_exp` → Employment experience (years)
* `person_home_ownership` → RENT / OWN / MORTGAGE
* `loan_amnt` → Loan amount applied
* `loan_intent` → Loan purpose (Education, Medical, Personal, Venture, etc.)
* `loan_int_rate` → Interest rate
* `loan_percent_income` → Loan as % of income
* `credit_score` → Applicant credit score
* `previous_loan_defaults_on_file` → Yes / No
* `loan_status` → Loan Approved (1) / Rejected (0)

---

## 🛠 Tools Used

* **Power BI** → Data visualization & dashboard building
* **Python (Google Colab)** → Data cleaning & preprocessing
* **GitHub** → Project sharing and version control

---

## 📈 Dashboard Features

### 1️⃣ KPI Cards

* **Total Applications** → Total loan requests
* **Approval Rate %** → Approved loans as percentage of total
* **Rejection Rate %** → Rejected loans as percentage of total
* **Average Income & Loan Amount** → Applicant financial profile

---

### 2️⃣ Visualizations

* **Bar Chart** → Loan Applications by Education & Home Ownership
* **Pie Chart** → Loan Purpose Distribution
* **Scatter Plot** → Income vs Loan Amount (Risk View)
* **Clustered Column Chart** → Approval/Rejection by Credit Score
* **Map Visualization** → (Optional if geo data available) Loan distribution by region
* **Trend Line** → Approval % over time (if time data available)

---

## 📊 Key Insights

✔ Higher income generally leads to higher loan approval chances.
✔ Applicants with **previous defaults** have a higher rejection rate.
✔ Education level & home ownership strongly influence loan approval.
✔ Credit score is the most significant factor in approval decisions.

---

## 🚀 How to Use

1. Clone this repo

   ```bash
   git clone https://github.com/yourusername/loan-risk-powerbi.git
   ```
2. Open the Power BI file (`Loan_Risk_Analysis.pbix`)
3. Connect to the dataset (`cleaned_banking & financial data.csv`)
4. Explore dashboard insights

---

## 📌 Future Enhancements

* Add predictive ML model integration for **loan default prediction**.
* Build a Tableau version of the same dashboard.
* Automate data refresh using Power BI Gateway.

---

## 📷 Dashboard Preview

* <img width="1315" height="733" alt="Banking   Finanace" src="https://github.com/user-attachments/assets/ce1e7a8f-d86a-411d-a27a-ad8c771291bb" />
*
