# SALES PERFORMANCE DASHBOARD(SUPERSTORE ANALYSIS)

![sales im](https://github.com/user-attachments/assets/9efda9f6-2fa6-4ebc-868b-a861110748c1)

# INTRODUCTION
This project provides a detailed visualization of sales performance data over a 4-year period. It breaks down total sales, profits, losses, best-selling products, sub-category performance, regional analysis, and monthly trends. The aim is to support decision-making by identifying high-performing areas and loss-making zones.

# ABOUT DATASET
The the dataset consist of  25 columns and 9,995 rows with some being string datatypes and decimal datatypes as well as datetime datatype. The dataset consists of:
Covers sales data from 2014 to 2017 The dataset includes details like Order Date, Ship Date, Customer Name, Product Category, Sales, Profit, Discount, Quantity, Order ID, Region and others. [Find the dataset]( https://www.kaggle.com/datasets/mohamed38/superstoredataset)

# OBJECTIVES

• To evaluate overall sales, profit, and loss trends over the 4-year period (2011–2014).
• To understand how key performance indicators (KPIs) evolved over time. 
• To identify the most and least profitable product categories and sub-categories.
• To determine which individual products contribute most to sales revenue.
• To analyze regional performance and identify top- and low-performing areas.
• To recommend targeted strategies for each region based on profitability and sales volume.
• To identify segments, products, or time periods with high loss values.
• To suggest corrective actions to minimize losses and increase profit margins.

# Key Metrics Overview

• Total Sales: $2.3M
• Total Profit: $286.4K (12.47% profit margin)
• Total Loss: $156.13K (6.80% loss rate) which is equivalent to the percentae of total discount given.

<img width="312" height="50" alt="image" src="https://github.com/user-attachments/assets/3f32fe05-dd29-4a43-b5b3-1f3ccc35b4ae" />


# KEY TABLES IN DATASET
From the model look into the data, a few core tables were observed namely; Customer, Date, Orders, People, Product, Returns and as well the report measures that were created in modelling the data to enahance efficient data relationship.

# Power BI Concepts Applied
The following Power BI features and functionalities were utilized:
**Data Import and Transformation**: Using Power Query to clean and shape data.
**Relationships & Star Schema**: Establishing one-to-many relationships for efficient filtering and slicer interactions.
**DAX Measures**: Creating KPIs like Total profits, Total Sales, and Total losses made.
**Visualizations**: Leveraging cards, bar charts, trend lines, treemaps, tables and image visuals.
**Drill-through and Tooltips**: Enabling detailed analysis at product and customer levels.
**Slicers & Filters**: Allowing users to filter data by customer name, category, mode of shipping and segment

# Data Modeling
The model follows a star schema approach:
The central Orders fact table holds core transactional data.
It connects to dimension tables like:
- Date (for time-based analysis)
- People
- Product(for data relating to the products)
- Customer
- Returns
The report meausures table holds reusable DAX measures and logic to simplify the report-building process and enhance performance.
This model ensures optimized relationships and efficient data retrieval for visual interactions.

<img width="865" height="337" alt="image" src="https://github.com/user-attachments/assets/4c6012fc-34d1-4b16-98bd-90b6769a51e8" />

# VISUALIZATION AND DATA INSIGHTS
**[Interact with full dashboard here](https://app.powerbi.com/links/F_xQQCp7lj?ctid=f66fae02-5d36-495b-bfe0-78a6ff9f8e6e&pbi_source=linkShare)**

# Category and Product Performance Analysis
• Technology is the highest contributor to both sales and profit.
• Furniture generates relatively high sales but has very low profit, indicating potential inefficiencies or high costs of the product category
**The top bestselling product is Canon Image CLASS 2200 Advanced Copier which is approximately $27.45K with other best performing products like Fellowes PB500 Electric Punch, Cisco VoIP Phones, and Acco Binders**.
• Products from Technology and Office Supplies dominate the best-seller product list.
• Aligning inventory and promotions around these products can drive profitability.
• Copiers and Phones generate the highest profits, suggesting a strategic opportunity to focus on expanding these lines.

<img width="296" height="221" alt="image" src="https://github.com/user-attachments/assets/e36f5ced-93d7-40e8-8bfb-17e92a91dde2" />

**Trend Analysis of Sales and Profits Made**
Monthly sales and profit show fluctuations with peaks in January 2014 and December 2014
Lowest points seen in 2011 and mid 2012 with some months even generating losses.
Trend Analysis shows that despite the month’s volatility; the overall profit trend is positive and there are strong end-of-year sales imply seasonal demand.

<img width="594" height="434" alt="Screenshot 2025-08-17 205810" src="https://github.com/user-attachments/assets/ee49ca37-a759-41f5-9b37-0debb03e9d25" />


# CONCLUSIONS AND RECOMMENDATIONS

1. **Improve Furniture Category Profitability**
• Investigate pricing, supplier costs, and organization for Furniture.
• Consider product bundling or promotions to boost margin.
2. **Focus on High-Margin Sub-Categories**
• Copiers, Phones, and Accessories are high-profit areas — consider upselling and expanding these lines.
3. **Regional Strategy Optimization**
• Replicate strategies used in the West and East regions to uplift performance in Central and South.
4. **Leverage Seasonal Trends**
• Prepare for end-of-year spikes with adequate inventory and marketing campaigns.
5. **Customer Segmentation**
• Identify high-frequency buyers and create loyalty programs tailored for them.
 



