# 📊 Telecom Customer Churn Analysis

This project explores the factors influencing customer churn in the telecom industry using Python data analysis and visualization tools. It provides meaningful insights into customer behavior to help develop retention strategies and reduce attrition rates.

---

## 🧠 Project Objective

To analyze customer data and uncover churn patterns across different demographics, service types, payment methods, and contract durations—ultimately enabling telecom businesses to improve customer loyalty.

---

## 📂 Dataset Overview

- **Source:** `Telco-Customer-Churn.csv`
- **Total Records:** 7,043
- **Key Features:**
  - Demographics: `gender`, `SeniorCitizen`, `Partner`, `Dependents`
  - Services: `PhoneService`, `InternetService`, `StreamingTV`, `TechSupport`, etc.
  - Financials: `MonthlyCharges`, `TotalCharges`
  - Customer status: `Contract`, `tenure`, `Churn`, `PaymentMethod`

---

## 📈 Key Insights

- Senior citizens have a **41.7% churn rate**, nearly twice that of younger customers.
- **Month-to-month contracts** show the highest churn.
- Customers with **tenure < 10 months** are most likely to leave.
- Electronic check payments result in the **highest churn**.
- Use of value-added services (e.g. `TechSupport`, `DeviceProtection`) correlates with **lower churn**.

---

## 🧰 Tools & Libraries Used

| Tool/Library       | Purpose                   |
|--------------------|---------------------------|
| Python             | Programming language      |
| Pandas, NumPy      | Data manipulation         |
| Matplotlib         | Plotting and charting     |
| Seaborn            | Statistical visualization |
| Jupyter Notebook   | Exploratory analysis      |

---

## 📊 Visualization Highlights

- Churn by contract type, tenure, payment method, internet usage
- Stacked bar charts comparing churn across demographics
- Pie charts and count plots with pastel color schemes
- Service usage comparison (e.g. streaming, backup, tech support)

---

## 🔍 Analytical Techniques

- Data cleaning and transformation (`replace`, `astype`, `apply`)
- Grouped calculations for churn percentages
- Custom churn comparison plots using Seaborn
- Trend analysis based on tenure, senior status, and service choices

---

## 💡 Business Recommendations

- Offer incentives for longer contracts to reduce churn.
- Improve onboarding for new customers (first 10 months).
- Promote automatic payment methods (credit card, bank transfer).
- Tailor offerings and support for senior citizens.
- Bundle essential services (security, tech support, streaming) to boost loyalty.

---

## 📌 Getting Started

```bash
# Clone the repository
git clone https://github.com/your-username/telecom-churn-analysis.git

# Navigate into the project directory
cd telecom-churn-analysis

# Install required packages
pip install pandas numpy matplotlib seaborn

# Open the Jupyter notebook
jupyter notebook Analysis.ipynb
