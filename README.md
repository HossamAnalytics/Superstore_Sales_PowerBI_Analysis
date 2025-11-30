## 🛒 Superstore Sales and Profitability Analysis Dashboard

This project provides a comprehensive analysis of the Superstore dataset, focusing on key performance indicators (KPIs) like Sales, Profit, and Quantity across various segments (Regions, Categories, and Customer Types).

### 📊 Technology Stack

* **Tool:** Power BI Desktop (Visualizations and Report Design)
* **Core Skills:** DAX (Data Analysis Expressions), Power Query (M Language), Data Modeling

---

### 🛠️ Key Analytical Steps & Value

* **Data Cleaning & Transformation:** Utilized Power Query to resolve data quality issues, handle date hierarchies, and ensure accurate calculation of margins and discounts.
* **Data Modeling:** Established a robust **Star Schema model** to ensure data integrity and optimize report performance, defining clear relationships between transactional data (Fact) and dimensional attributes (as shown in the accompanying image).
* **DAX Implementation:** Created complex measures to calculate:
    * **Profit Ratio** (`Total Profit / Total Sales`)
    * **Year-over-Year (YoY) Profit Growth**
    * **Top N Analysis** for Products and Customers.

### 💡 Key Business Insights

1.  **Profitability Anomaly:** Identified that the 'West' region, while having the highest sales volume, maintains a lower overall profit margin (10% vs. the average 14%) due to aggressive discounting in the 'Technology' category, suggesting a need for pricing optimization.
2.  **Customer Value:** Analyzed customer segmentation and found that 'Corporate' customers generate the highest average Customer Lifetime Value (CLV), recommending an increased focus on B2B sales strategies.
3.  **Strategic Forecasting:** Developed a 'What If' analysis page to allow stakeholders to simulate potential revenue based on variable growth rates.

### 📝 Report Structure (4 Pages)

The full interactive report is built with four dedicated pages, demonstrating a complete analytical workflow:

* **Summary Analysis:** High-level KPIs and performance snapshots (Sales, Profit, Discounts).
* **Product Analysis (Drill Through):** Detailed root cause analysis for performance gaps by State, City, and Product.
* **Customers Segmentation:** Deep dive into customer behavior, retention, and lifetime value (LTV) metrics.
* **What If? - Sales Forecasting:** A simulation/forecasting tool for future planning.

### 🖼️ Dashboard Preview

This image shows the **Summary Analysis** page. The full report includes detailed pages for deep-dive analysis.



[Image of Power BI Dashboard]


*(Reference: **dashboard\_preview.png**)*
