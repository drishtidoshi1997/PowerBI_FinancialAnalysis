# 📉 Loan Default & Portfolio Overview Dashboard

[![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=flat-square&logo=powerbi&logoColor=black)](https://powerbi.microsoft.com/)
[![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=sql&logoColor=white)]()

Interactive **Power BI dashboard** for monitoring loan portfolio performance, default risk, and borrower demographics. Helps credit risk managers identify high-risk segments and track year-over-year trends.

---

## 🖼️ Dashboard Previews

| Loan Default & Overview | Demographic & Financial Profile |
|:-----------------------:|:-------------------------------:|
| ![Customer Dashboard](Customer%20Dashboard.png) | ![Applicants Demographic](Applicants%20Demographic%20and%20Financial%20Profile.png) |

*Click images to enlarge.*

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

- **Data Extraction:** SQL (T-SQL), SQL Server Management Studio – [`LoanTable.sql`](./LoanTable.sql)
- **Data Transformation:** Power BI Dataflows (M language)
- **Data Modeling & Visualization:** Power BI Desktop (DAX measures) – [`loan.pbix`](./loan.pbix)
- **Data Refresh:** Power BI Service (scheduled refresh)

---

## 📁 Dataset

The dataset contains **18 fields** describing borrower demographics, loan characteristics, and repayment behavior.

- **Raw Data:** [`Loan.csv.gz`](./Loan.csv.gz) (compressed CSV)
- **Metadata:** [`Meta Data Loan.xlsx`](./Meta%20Data%20Loan.xlsx) – column definitions and data dictionary

Key columns: `LoanAmount`, `CreditScore`, `EmploymentType`, `Education`, `MaritalStatus`, `LoanPurpose`, `Default`, `Loan Date`

---

## 📂 Repository Structure

```
├── Loan.csv.gz                           # Raw loan dataset (compressed)
├── Meta Data Loan.xlsx                   # Column definitions and metadata
├── LoanTable.sql                          # SQL extraction script
├── loan.pbix                               # Power BI dashboard file
├── Customer Dashboard.png                  # Sales dashboard preview
├── Applicants Demographic and Financial Profile.png  # Demographic dashboard preview
└── README.md                                # This file
```
---

**#PowerBI #DAX #SQL #CreditRisk #LoanDefault #DataAnalytics #Dashboard**
