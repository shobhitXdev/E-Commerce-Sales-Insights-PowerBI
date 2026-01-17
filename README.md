# E-Commerce Sales Analysis Dashboard

## 📌 Project Objective
The goal of this project is to analyze the sales performance of an e-commerce business (referred to as **Delhi Retail Mart**). By connecting different data sources, the dashboard identifies key sales drivers, regional performance, and customer trends to help in data-driven decision-making.

## 📊 Dataset Description
The project uses two primary CSV files:
1. **Orders Table:** Contains Order ID, Date, Customer Name, State, and City.
2. **Details Table:** Contains Order ID, Amount, Profit, Quantity, and Category.

## 🛠️ Project Steps Followed
1. **Data Cleaning (Power Query):** - Imported CSV files into Power BI.
   - Performed data profiling to check for null values.
   - Changed data types for 'Date' and 'Amount' columns for accurate calculations.
2. **Data Modeling:** - Established a **1:1 Relationship** between the 'Orders' and 'Details' tables using the `Order ID` column.
3. **DAX Measures:** - Created custom measures for Total Sales, Total Quantity, and Average Order Value.
4. **Data Visualization:** - Used Bar Charts for Category analysis.
   - Integrated Slicers for 'State' to allow granular filtering (specifically for Delhi).
   - Designed a clean UI with KPI cards for instant insights.

## 💡 Key Insights
- **Regional Focus:** The dashboard highlights performance in the Delhi region, showing how it contributes to overall sales.
- **Product Performance:** Identified which product categories are driving the maximum profit margin.
- **Trend Identification:** Visualized sales spikes during specific periods.

## 📷 Screenshots

### 1. Overall Dashboard Performance
<img width="1153" height="712" alt="dashboard_unfiltered" src="https://github.com/user-attachments/assets/4881d6de-8d39-4f7e-8dac-c5edd6d2dd54" />


### 2. Delhi State Analysis (Slicer Applied)
<img width="1153" height="717" alt="dashboard_delhi_filter" src="https://github.com/user-attachments/assets/d5b51a14-b04f-462a-99e7-d9d8f226b898" />


---
## How to Run
1. Download the `Sales_Analysis_Dashboard.pbix` file.
2. Ensure you have **Power BI Desktop** installed.
3. Open the file to interact with the filters.
