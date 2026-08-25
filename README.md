# 🍪 Dinma's Cookie Sales Dashboard 2019/2020

## 📊 Project Overview

This project is an interactive **Cookie Sales Dashboard** developed using Microsoft Power BI.

The dashboard analyzes cookie sales performance for 2019 and 2020, providing insights into:

- Total Sales
- Total Profit
- Total Orders
- Average Purchase
- Sales by Cookie Type
- Profit by Cookie Type
- Revenue by State and City
- Cookie Sales Performance by City
- Sales trends over time

The project demonstrates my ability to transform raw sales data into an interactive business intelligence dashboard that can support data-driven decision-making.

## 🎯 Project Objectives

The objectives of this project are to:

- Analyze total sales performance
- Analyze total profit
- Monitor total orders
- Calculate average order value
- Analyze profit margin
- Compare cookie types
- Analyze sales trends over time
- Analyze revenue by city
- Compare cookie performance across cities
- Create an interactive Power BI dashboard
- Generate useful business insights

---

## 🏢 Business Problem

A business may have a large amount of sales data but still struggle to understand its overall performance.

Raw sales data can make it difficult to quickly answer questions such as:

- How much revenue was generated?
- How much profit was made?
- Which cookie performs best?
- Which city generates the most revenue?
- How are sales changing over time?
- Which products need more attention?

This project addresses these questions by transforming raw sales data into an interactive Power BI dashboard.

---

## 💡 Proposed Solution

I developed an interactive dashboard that allows users to explore sales performance through:

- KPI cards
- Sales trend analysis
- Product analysis
- Geographic analysis
- Revenue analysis
- Profit analysis
- Interactive filters

Users can filter the dashboard by:

- Date
- City
- Cookie Type.

---


#### Dataset

[Orders.xlsx](https://github.com/user-attachments/files/31427030/Orders.xlsx)
[Customers (1).xlsx](https://github.com/user-attachments/files/31427003/Customers.1.xlsx)
[Cookie Types (1).xlsx](https://github.com/user-attachments/files/31426980/Cookie.Types.1.xl

### 🔄 DATA ANALYTICS WORKFLOW
Raw Data
   ↓
Data Import
   ↓
Data Inspection
   ↓
Data Cleaning
   ↓
Data Transformation
   ↓
Data Modeling
   ↓
DAX Measures
   ↓
Dashboard
   ↓
Business Insights


# 🔄 Data Cleaning and Transformation

## Overview

The raw cookie sales dataset was prepared using Power Query before being used for dashboard development.

The objective of the data preparation process was to ensure that the dataset was clean, consistent, and suitable for analysis.

---

# Step 1 — Import the Dataset

The raw sales data was imported into Microsoft Power BI.

---

# Step 2 — Inspect the Dataset

The dataset was reviewed to identify:

- Column names
- Data types
- Missing values
- Duplicate records
- Incorrect values
- Inconsistent text
- Unnecessary columns

---

# Step 3 — Remove Unnecessary Columns

Columns that were not required for the analysis were removed.

This helps simplify the data model and improve dashboard performance.

---

# Step 4 — Handle Missing Values

Missing values were reviewed and handled according to the requirements of the analysis.

---

# Step 5 — Correct Data Types

Appropriate data types were assigned to the columns.

Examples:

| Column | Data Type |
|---|---|
| Date | Date |
| Revenue | Decimal Number |
| Profit | Decimal Number |
| Quantity | Whole Number |
| Order ID | Text |
| City | Text |
| Cookie Type | Text |

---

# Step 6 — Clean Text Fields

Text fields were reviewed for:

- Extra spaces
- Inconsistent capitalization
- Spelling inconsistencies
- Duplicate categories

---

# Step 7 — Validate the Data

The cleaned dataset was checked to ensure that:

- Revenue values were valid
- Profit values were valid
- Dates were correctly formatted
- Cities were correctly categorized
- Cookie types were correctly categorized
- Order IDs were usable for order calculations

---

# Step 8 — Load Data Into Power BI

After transformation, the cleaned dataset was loaded into Power BI for:

- Data modeling
- DAX calculations
- Visualization
- Dashboard development

---



# DAX Measures

Total Sales =
SUM(Sales[Revenue])
Total Profit =
SUM(Sales[Profit])
Total Orders =
DISTINCTCOUNT(Sales[Order ID])
Average Purchase =
DIVIDE(
    [Total Sales],
    [Total Orders],
    0
)
Profit Margin =
DIVIDE(
    [Total Profit],
    [Total Sales],
    0
)

## 🛠️ Tools Used

| Tool | Purpose |
|---|---|
| Microsoft Excel | Data source |
| Power Query | Data cleaning and transformation |
| Power BI | Dashboard development |
| DAX | Calculations and KPIs |
| GitHub | Portfolio and project documentation |

---

# DASHBOARD PREVIEW
[SALES DASHBOARD.pdf](https://github.com/user-attachments/files/31427769/SALES.DASHBOARD.pdf)


---







# 📂 Repository Structure

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
    ├── DAX_Measures.md
    ├── Data_Cleaning.md
    └── Business_Insights.md

