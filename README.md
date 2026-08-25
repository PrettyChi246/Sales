# 🍪 Dinma's Cookie Sales Dashboard 2019/2020
## 📊 Project Overview

This project is an interactive **Cookie Sales Dashboard** developed using Microsoft Power BI.

The dashboard analyzes cookie sales performance for 2019 and 2020, providing insights into:

- Total Sales
- Total Profit
- Total O
- Average Purchase
- Sales by Cookie Type
- Profit by Cookie Type
- Revenue by State and City
- Cookie Sales Performance by City
- Sales trends over time

The goal of this project is to transform raw sales data into an interactive business intelligence dashboard that can support data-driven decision-making.

#Dataset

[Orders.xlsx](https://github.com/user-attachments/files/31427030/Orders.xlsx)
[Customers (1).xlsx](https://github.com/user-attachments/files/31427003/Customers.1.xlsx)
[Cookie Types (1).xlsx](https://github.com/user-attachments/files/31426980/Cookie.Types.1.xl

# DAX Measures

## 1. Total Sales

```DAX
Total Sales =
SUM(Sales[Revenue])
## 2. Total Profit =
SUM(Sales[Profit])
Total Orders =
DISTINCTCOUNT(Sales[Order ID])
Average Purchase =
DIVIDE(
    [Total Sales],
    [Total Orders],
    0
)


---

## 🛠️ Tools Used

- Microsoft Power BI
- Power Query
- DAX
- Microsoft Excel
- Data Visualization
- Data Cleaning
- Data Analysis

---

## 📁 Repository Structure

```text
cookie-sales-dashboard/
│
├── README.md
│
├── Dashboard/
│   └── Cookie_Sales_Dashboard.pbix
│
├── Data/
│   └── cookie_sales_data.xlsx
│
├── Images/
│   └── cookie-sales-dashboard.png
│
└── Documentation/
    └── DAX_Measures.md
