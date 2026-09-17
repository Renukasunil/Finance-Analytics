#  Finance Analysis Project — Power BI

##  Project Overview

The **Finance Analysis Project** is an interactive **Power BI dashboard** designed to analyze financial transactions, customer behavior, fees, taxes, and transaction performance.

The project provides management with a centralized view of financial performance across **time, transaction types, customer segments, states, occupations, categories, and demographics**.

##  Business Objectives

* Monitor overall transaction and financial performance
* Analyze monthly transaction trends
* Compare successful, failed, and pending transactions
* Identify high-performing customer segments and states
* Analyze transaction type performance
* Track fees and taxes
* Understand customer demographics
* Measure Year-over-Year (YoY) performance

##  Dashboard 1 — Finance Analytics

### Key KPIs

* **Total Amount** + YoY Growth
* **Total Transactions**
* **Average Transaction Value**
* **Total Fees**
* **Total Tax**

### Visualizations

| Analysis                     | Visualization     |
| ---------------------------- | ----------------- |
| Total Amount by Month        | Line / Area Chart |
| Amount by Transaction Status | Donut Chart       |
| Amount by Customer Segment   | Bar Chart         |
| Amount by State              | Bar Chart         |
| Transaction Type Analysis    | Matrix / Heatmap  |
| Amount by Gender             | Donut Chart       |

### Transaction Types

* Bill Payment
* Card Payment
* Deposit
* Fee Charge
* Interest Credit
* Investment
* Loan EMI
* Refund
* Transfer
* Withdrawal

##  Interactive Filters

Users can dynamically analyze the data using:

* Year
* Dynamic Measure
* Occupation
* Category

##  Dashboard 2 — Detailed Transaction Analysis

The second dashboard provides a **detailed grid view of financial transactions**.

Users can:

* View underlying transaction records
* Drill down from summary-level analysis to transaction-level details
* Filter and investigate specific transactions
* Analyze transaction attributes in greater detail

##  Tools & Technologies

* **Power BI**
* **Power Query**
* **DAX**
* **Data Modeling**
* **Interactive Visualizations**

##  Key DAX Measures

Examples of measures created:

```DAX
Total Amount = SUM(Transactions[Amount])

Total Transactions = COUNTROWS(Transactions)

Average Transaction Value =
DIVIDE([Total Amount], [Total Transactions])

Total Fees = SUM(Transactions[Fees])

Total Tax = SUM(Transactions[Tax])
```

##  Business Value

This dashboard provides a centralized analytical view that helps stakeholders **monitor financial performance, identify transaction trends, compare customer and regional performance, and investigate detailed transaction-level data** for informed business analysis.

##  Project Structure

```text
Finance-Analysis-PowerBI/
│
├── README.md
├── Finance_Analysis.pbix
```

##  Project Outcome


Built an interactive Power BI solution that transforms financial transaction data into **actionable dashboards and detailed analytical views**, enabling both high-level KPI monitoring and transaction-level investigation.
