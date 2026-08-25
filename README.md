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

### Product Analysis

- Which cookie type generates the highest revenue?
- Which cookie generates the highest profit?
- Which products have lower sales?

### Geographic Analysis

- Which city generates the most revenue?
- Which city generates the least revenue?
- How does product performance differ by city?

### Time Analysis

- How are sales changing over time?
- Which months have the highest sales?
- Which periods have lower sales?
- How does one year compare with another?

### Financial Analysis

- What is total revenue?
- What is total profit?
- What is the profit margin?
- What is the average order value?

---

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
### Key Features

- 💰 **Total Sales** – $4.69M
- 💵 **Total Profit** – $2.72M
- 🧾 **Total Orders** – 700
- 🛒 **Average Purchase** – $6.7K
- 🍪 **Cookie Type Analysis**
- 📈 **Sales Trend Analysis**
- 🏙️ **Revenue by City**
- 🗺️ **Geographic Analysis**

### Interactive Filters

Users can filter the dashboard by:

- 📅 Date
- 🏙️ City
- 🍪 Cookie Type

### Visualizations

- KPI Cards
- Bar Charts
- Line Charts
- Map
- Interactive Slicers


## 🔍 Key Findings

### 1. Product Performance
- The dashboard shows differences in sales and profitability across cookie types.
- **Best-performing cookie:** `CHOCOLATE COOKIE`
- **Lowest-performing cookie:** `FORTUNE COOKIE`

### 2. Geographic Performance
- Sales performance varies across cities.
- **Highest-performing city:** `GREEN BAY CITY`
- **Lowest-performing city:** `SEATTLE CITY`

### 3. Sales Trends
- Sales performance changed throughout 2019–2020.
- **Highest-performing period:** `2020`
- **Lowest-performing period:** `2019`

---

# 💡 Business Recommendations

### 1. Focus on High-Performing Products
Increase marketing and inventory for products generating the highest sales and profit.

### 2. Investigate Low-Performing Products
Review pricing, customer demand, availability, and marketing strategies for weaker products.

### 3. Prioritize High-Performing Cities
Allocate more inventory and targeted promotions to cities generating strong revenue.

### 4. Improve Low-Performing Locations
Investigate the reasons for weaker sales and develop location-specific strategies.

### 5. Use Sales Trends for Planning
Use historical sales patterns to improve inventory management, promotions, and future sales planning.

### 6. Monitor Profitability
Track profit alongside revenue to ensure that sales growth translates into sustainable business performance.

---

# 📚 Lessons Learned

Through this project, I learned how to:

- Clean and transform raw data using **Power Query**
- Build relationships between tables
- Create calculated measures using **DAX**
- Design interactive Power BI dashboards
- Use KPIs to monitor business performance
- Analyze sales trends and product performance
- Perform geographic analysis
- Turn data into actionable business insights
- Document and present a data analytics project on **GitHub**

---

# ⚠️ Limitations

Although the Cookie Sales Dashboard provides useful insights, there are some limitations to the analysis.

### 1. Limited Time Period
The analysis covers only **2019–2020**, so it may not reflect more recent sales performance.

### 2. Limited Dataset
The available dataset contains a limited number of business variables, which restricts the depth of analysis.

### 3. No Customer Demographics
The dataset does not provide detailed customer information such as age or gender.

### 4. No Marketing Data
Marketing campaigns, advertising costs, and promotional activities are not included, making it difficult to determine their impact on sales.

### 5. No Forecasting
The current dashboard focuses mainly on historical performance and does not include predictive sales forecasting.

### 6. Data Quality
The accuracy of the analysis depends on the quality and completeness of the original dataset.

---

## 🔮 Future Improvements

Future versions of the dashboard could include:

- More recent sales data
- Customer segmentation
- Marketing and campaign data
- Sales forecasting
- Profit forecasting
- Year-over-Year growth analysis
- Customer behavior analysis
- Automated data refresh

---

## 🎯 Conclusion

These limitations provide opportunities to expand the analysis and make the dashboard more comprehensive for future business decision-making.


