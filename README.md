🚴 Bike Sales Analysis | Power BI End-to-End Project  

Power BI end-to-end Bike Sales Analysis project showcasing data transformation, cleaning, DAX measures, and interactive dashboards.


## 📌 Project Overview  
This project is a complete end-to-end Power BI solution built to analyze Bike Sales data and extract meaningful business insights. It focuses on sales performance, customer behavior, product performance, and return analysis.

The project demonstrates:
- Data cleaning & transformation using Power Query  
- Data modeling using Star Schema  
- KPI creation using DAX  
- Interactive and business-driven dashboards  


## 🛠️ Tools & Technologies  
- Power BI  
- Power Query (for data cleaning & transformation)  
- DAX (for calculations & KPIs)  
- Excel / CSV (Data Source)


## 💼 Business Problem
The bike sales company generates large volumes of transactional data across multiple regions, products, and customers. As the comapany wants to know the:
-  Real-time visibility into sales, profit, and order performance.
- Identifying top customers and repeat buyers.
- Highlighting profitable and underperforming territories
- Tracking monthly trends and seasonality.
- Analyzing product-wise returns and return rates.
- Helping management make data-driven decisions for marketing, inventory, and quality control.


## 🔁 Project Workflow

1. Data Loading  
   - Imported all raw datasets (Sales, Customers, Products, Territories, Returns, and Calendar) into Power BI using Power Query.

2. Data Cleaning & Preparation (Power Query)
   - Promoted the first row as headers.
   - Corrected column data types (Date, Decimal, Whole Number, Text).
   - Removed duplicates where required.
   - Checked for null and blank values and handled them appropriately.
   - Standardized column names for better readability.
   - Created calculated columns where necessary.

3. Data Consolidation  
   - Combined three years of sales data into a single unified Sales table using **Append Queries** for easier analysis and calculations.

4. Data Modeling  
   - Created relationships between fact and dimension tables.
   - Designed a **Star Schema** with:
     - Fact Table: SalesRecord  
     - Dimension Tables: Customers, Products, Categories, Subcategories, Territories, Calendar, Returns
   - Ensured correct cardinality and filter direction for accurate reporting.

5. DAX Measures Creation  
   - Created a separate **Measure Table** to store all DAX measures.
   - Developed key business KPIs such as:
     - Total Revenue  
     - Total Profit  
     - Total Orders  
     - Quantity Sold  
     - Distinct Customers
     -  Average Order Value  
     - Average Spend per Customer  
     - Rebuy Rate %  
     - Return Rate %  
     - Profit Margin %  
     - MoM Growth %  
     - YTD Revenue
  6. Dashboard Design & Visualization  
   - Designed interactive dashboards with slicers and filters.
   - Created four analytical pages:
     - Sales Overview  
     - Map Overview  
     - Customer & Territory Insights  
     - Product & Return Performance  
   - Used appropriate visuals (Cards, Line charts, Bar charts, Maps, Matrix, Treemap).

7. Business Insight Generation  
   - Interpreted trends in sales growth, seasonality, customer behavior, territory profitability, and product return performance.
   - Converted raw data into actionable business insights.

  
🗂️ Data Modeling
Fact Table: Sales
Dimensions: Customers, Products, Returns, Territories, Categories, Subcategories, Date
Preview of Star Schema Model
<img width="976" height="458" alt="Data Model" src="https://github.com/user-attachments/assets/05b7e2cf-8794-4fe8-bdab-095e3a89e72c" />


## 🎯 Skills Demonstrated  
- Data Cleaning (Power Query)  
- Data Modeling  
- DAX Calculations  
- Dashboard Design  
- Business Storytelling  
- Analytical Thinking  


## 📄 Dashboard Pages

### 1️⃣ Sales Overview

**KPIs:** Total Revenue, Profit, Orders, Quantity Sold  

**Visuals:**  
- Waterfall Chart – Revenue by Year & Order Type  
- Line Chart – Revenue Trend (Year, Quarter, Month)  
- Pie Chart – Revenue by Order Type & Subcategory  
- Bar Chart – Sales by Subcategory  
- Sync Slicers – Year, Category, Order Type  
 
Preview
  <img width="877" height="484" alt="Overview and Dashboard" src="https://github.com/user-attachments/assets/3d6e35db-94bf-4892-8748-bc6939e77977" />


### 2️⃣ Map Overview

- Revenue by Country  
- Profit by Continent  
- Profit Distribution Map  
- Sync Slicer  
  
Preview
<img width="878" height="484" alt="Map Overview" src="https://github.com/user-attachments/assets/cea0b7b1-371a-4a37-9240-bde42dc51c8e" />


### 3️⃣ Product and Return Performance

**KPIs:** Quantity Sold, Total Returns, Return Rate %  

**Visuals:**  
- Column Chart – Returns by Product  
- Donut Chart – Sales vs Returns by Category  
- Treemap – Sales by Category & Subcategory  
- Matrix – Product-wise Sales, Profit, Returns  
- Sync Slicers

Preview
<img width="876" height="483" alt="Product   Return Performance" src="https://github.com/user-attachments/assets/81bcff06-4da7-47f8-8b9f-cfd12f9306a2" />


### 3️⃣ Customer & Territory Insights
**KPIs:**  
- Distinct Customers  
- Average Spend per Customer  
- Average Order Value  

**Visuals:**  
- Bar Chart – Top 10 Customers  
- Column Chart – Territory-wise Profit  
- Line Chart – Customer Purchase Trend  
- Pie Chart – Monthly Return Rate  
- Matrix – Territory-wise Sales, Profit, Orders, Returns

Preview
<img width="877" height="484" alt="Customer   Territory Insights" src="https://github.com/user-attachments/assets/5625e901-f903-40a1-a65c-c1b89124c456" />


## 📈 Key Business Insights  
- Total Revenue: $24.91M | Total Profit: $10M  
- Quantity Sold: 84K | Total Returns: 1,828  
- Distinct Customers: 17K  
- Average Spend per Customer: 4.83  
- Repeat customers generate a significant portion of revenue  
- The USA leads in total revenue  
- North America contributes the highest profit  
- Accessories category generates the highest profit  
- Certain products show high return rates, indicating quality or logistics issues  
- High dependency on top customers indicates customer concentration risk  

