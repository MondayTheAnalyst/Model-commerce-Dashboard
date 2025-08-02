
# 📊 Model Commerce Dashboard (Power BI)

This Power BI dashboard visualizes key business metrics from the Model Commerce dataset. It is built on top of SQL-based analysis(Model-commerce-analysis) and includes interactive features to help stakeholders explore sales trends, product performance, customer behavior, and order operations.

---

## 🧭 Overview

After analyzing the sales data using SQL, the dataset was imported into Power BI for dynamic reporting. The dashboard combines custom visuals, slicers, calculated measures, and a dedicated model to explore metrics such as:

- Sales by productline and Net Profit by product line
- Sales by customer country and Net Profit by customer country
- Sales by office and Net Profit by office
- Sales by cost of sales and Net Profit by cost of sales
- Net Profit by customer country, product line and customer name 
- Sales Overview (Month-over-Month (MoM) and Year-to-Date (YTD) performance)

---

## 🛠️ Data & Calculations

- **Data Source**: SQL view created from cleaned Model Commerce dataset
- **Import Mode**: Data imported via SQL Server connector
- **Calculated Measures**:
  - `Sales_Value`, `Net_Profit`, `Cost_of_Sales`
  - `Sales_Value MoM` (Month-over-Month %)
  - `Sales_Value YTD` (Year-to-Date running total)
- **Custom Table**: Created for controlling dynamic metrics and filters
- **Slicers**: Year, Date range, Product line, Customer country, Metric selector

---


## 📊 Dashboard Pages

### 📍 Page 1: Sales Overview
- Sales and Net Profit by Product Line
- Sales and Net Profit by Customer Country
- Sales and Net Profit by Office
- Sales vs Cost of Sales (Scatter)
- KPI Cards: Total Sales, Unique Orders, Avg Order Value
- MoM Sales Trend Line and Order Timeline

### 📍 Page 2: Drill-Down Insights
- Tree visual of Net Profit by Customer Country → Product Line → Customer Name
- Sales Overview Table with:
  - Month-over-Month (%) change
  - Year-to-Date (YTD) Sales Growth
---






### 🧾 Overall Strategic Takeaways

This dashboard provides a visual and interactive understanding of key business drivers across products, customers, offices, and time.

- **Focus** on high-performing combinations such as *Classic Cars* sold to USA-based clients through the USA and France offices. These consistently rank highest in both sales and profit.
  
- **Investigate** underperforming products like *Trains* and *Planes*, and low-impact countries like *Hong Kong* or *Philippines*, to determine whether performance is due to low demand, pricing, or distribution gaps.

- **Optimize margins** by identifying high-cost-of-sales items with weaker profit returns. Not all top sellers are profitable — focus on increasing efficiency or reconsidering product strategy.

- **Segment and nurture high-value customers**, as a few clients contribute disproportionately to net profit. Drill-down analysis shows that VIP accounts like *Anna Decorations, Ltd* have a strong cross-product impact.

- **Leverage timing and seasonality**: Month-over-month (MoM) and year-to-date (YTD) trends reveal strong periods like mid-2004 and early 2005. These can guide future promotional or inventory strategies.

---



## 🔍 Features Highlighted

- Dynamic visuals with responsive slicers and cards
- Drill-through & hierarchy navigation
- Conditional formatting and trend indicators
- Custom DAX measures for running totals and MoM %
- Dashboard theme: dark mode with clear typography and contrast

---

## 📁 Files Included

- `/pbix/Model_Commerce_Dashboard.pbix` – Power BI report file
- `/screenshots/` – Preview images of dashboard pages
- `README.md` – This project documentation

---


## 📬 Contact

- **GitHub:** [mondaytheanalyst](https://github.com/mondaytheanalyst)
- **Email:** Obotmonday680@gmail.com
