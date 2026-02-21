# Power-BI_Financial-Analysis

# 📉 Loan Default & Portfolio Overview Dashboard

[![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=flat-square&logo=powerbi&logoColor=black)](https://powerbi.microsoft.com/)
[![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=sql&logoColor=white)]()

Interactive **Power BI dashboard** for monitoring loan portfolio performance, default risk, and borrower demographics. Helps credit risk managers identify high-risk segments and track year-over-year trends.

---

## 🖼️ Dashboard Previews

| Loan Default & Overview | Demographic & Financial Profile |
|:-----------------------:|:-------------------------------:|
| ![Loan Default Overview](images/loan_default_overview.png) | ![Demographic Profile](images/demographic_profile.png) |

---

## 💡 Key Insights

- **Home** and **Business** loans generate the highest volume (~6.5bn each).
- **Unemployed** borrowers have the highest default rate (**3.39%**) – nearly 1% higher than full-time employed.
- Default rates remained **stable around 11.5%** from 2014 to 2018.
- **Medium credit score** borrowers (not the highest) drive the largest loan volume (**4.6bn**).
- **Teens** have significantly lower average loan amounts ($106K) compared to other age groups ($127K+).
- **Bachelor's degree** holders lead in total loan volume.
- After several years of decline, **loan volume grew +1.73% in 2018** – a positive turnaround.

---

## 🛠️ Tech Stack

- **Data Extraction:** SQL (T-SQL), SQL Server Management Studio
- **Data Transformation:** Power BI Dataflows (M language)
- **Data Modeling & Visualization:** Power BI Desktop (DAX measures)
- **Data Refresh:** Power BI Service (scheduled refresh)

---

## 📁 Dataset

The dataset contains **18 fields** describing borrower demographics, loan characteristics, and repayment behavior. Key columns:

- `LoanAmount`, `CreditScore`, `EmploymentType`, `Education`, `MaritalStatus`, `LoanPurpose`, `Default`, `Loan Date`

📎 [`Loan.xlsx`](./Loan.xlsx) – Raw data with full metadata and column definitions.

---

## 📂 Repository Structure

```
├── Loan.xlsx                 # Raw dataset
├── SQL_queries.sql           # Data extraction scripts
├── dashboard.pbix            # Power BI file (available on request)
├── images/
│   ├── loan_default_overview.png
│   └── demographic_profile.png
└── README.md
```

---

## 🚀 Getting Started

1. Clone the repository.
2. Open `Loan.xlsx` to explore the data.
3. Load the data into Power BI Desktop or connect to your own SQL database using the provided scripts.
4. Request the `.pbix` file for the complete interactive dashboard.

---

**#PowerBI #DAX #SQL #CreditRisk #LoanDefault #DataAnalytics #Dashboard**
