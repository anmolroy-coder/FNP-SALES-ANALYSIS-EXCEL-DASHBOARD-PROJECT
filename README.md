#  FNP Sales Analysis Dashboard | Excel Project

##  Project Overview
This project is an interactive Excel Dashboard created using the Ferns N Petals (FNP) sales dataset. The dashboard helps analyze sales performance, customer behavior, delivery insights, category performance, and city-wise order distribution.

Using Power Query, Power Pivot, DAX, Pivot Tables, and Pivot Charts, the raw data was transformed into meaningful business insights through an interactive dashboard.

---

##  Tools & Technologies Used
- Microsoft Excel
- Power Query
- Power Pivot
- DAX (Data Analysis Expressions)
- Pivot Tables
- Pivot Charts
- Data Modeling
- Slicers

---

##  Data Cleaning & Transformation
Performed multiple data transformation tasks using Power Query:
- Imported data from folder
- Cleaned and transformed datasets
- Extracted Month Name from Order Date
- Extracted Hour from Order Time
- Calculated Order-Delivery Time Difference
- Merged Orders and Products tables using Merge Queries based on Product ID
- Added custom columns for analysis

---

##  Data Modeling
Created a proper data model using:
- Star Schema
- Fact Table & Dimension Tables
- Relationships in Orders, Customers, and Products tables

---

##  DAX Calculations

### Revenue Formula
```DAX
Revenue = [Price] * [Quantity]
```

### Day Name Formula
```DAX
Day Name = FORMAT(Orders[Order_Date], "DDDD")
```

---

##  Dashboard Insights
The dashboard provides insights on:
- Revenue by Occasion
- Revenue by Category
- Revenue by Hour (Order Time)
- Revenue by Month
- Top 5 Products by Revenue
- Top 10 Cities by Orders
- Total Orders
- Total Revenue
- Average Customer Spend
- Average Order Delivery Time

---

##  Key Insights
- Colors category generated the highest revenue among all categories.
- Maximum orders were received during evening hours.
- Anniversary and Raksha Bandhan occasions contributed significantly to revenue.
- Certain cities showed consistently higher order volume than others.
- Revenue trends varied across different months, showing seasonal demand patterns.
- Top-performing products contributed a major share of total revenue.

---

##  Dashboard Features
- Interactive Slicers & Filters  
- Dynamic Charts  
- KPI Cards  
- Business Insights Visualization  
- User-Friendly Dashboard Design  

---

##  Learning Outcomes
This project helped me improve my skills in:
- Excel Dashboarding
- Data Cleaning
- Data Transformation
- Data Modeling
- DAX Functions
- Business Analytics
- Data Visualization

---

##  Author
**Anmol Ray**

### 🔗 Connect With Me
- LinkedIn:www.linkedin.com/in/anmol-ray-7176a0397

---

#Excel #Dashboard #DataAnalytics #PowerQuery #PowerPivot #DAX #BusinessAnalytics #ExcelDashboard
