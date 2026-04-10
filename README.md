# 📊 Customer Churn Analysis

### Telco Customer Dataset | Python | 7,043 Records

---

## 🎯 Project Overview

This project analyzes customer churn patterns for a telecommunications company.
The goal is to identify the key factors driving customer loss and provide
actionable business recommendations to improve retention.

---

## 📁 Project Structure

Customer-Churn-Analysis/
├── data/
│ └── WA*Fn-UseC*-Telco-Customer-Churn.csv
├── images/
│ ├── churn_distribution.png
│ ├── churn_by_contract.png
│ ├── churn_by_internet.png
│ ├── churn_by_tenure.png
│ ├── churn_by_charges.png
│ └── churn_by_senior.png
├── notebook/
│ └── churn_analysis.ipynb
└── README.md

---

## 🔍 Key Findings

| Factor               | Finding                                   |
| -------------------- | ----------------------------------------- |
| Overall Churn Rate   | 26.54% — 1 in 4 customers left            |
| Contract Type        | Month-to-month had highest churn          |
| Internet Service     | Fiber optic customers churned most        |
| Avg Tenure (Churned) | 17.98 months vs 37.57 for loyal customers |
| Avg Monthly Charges  | $74.44 churned vs $61.27 loyal customers  |
| Age Group            | Non-senior customers churned more         |

---

## 💡 Business Recommendations

1. **Incentivize annual contracts** — month-to-month customers churn 3x more
2. **Review Fiber Optic pricing** — highest churn despite premium service
3. **Focus retention on first 18 months** — critical churn window
4. **Introduce loyalty discounts** for customers paying above $70/month
5. **Target younger customers** with retention campaigns

---

## 🛠️ Tools Used

- Python 3
- Pandas — data manipulation
- Matplotlib — data visualization
- Jupyter Notebook (VS Code)

---

## 📊 Dataset

- Source: [Kaggle — Telco Customer Churn](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)
- Size: 7,043 rows × 21 columns
- No missing values found

---

## 📈 Visualizations

Six charts were produced covering:

- Overall churn distribution
- Churn by contract type
- Churn by internet service
- Churn by customer tenure
- Churn by monthly charges
- Churn by senior citizen status
