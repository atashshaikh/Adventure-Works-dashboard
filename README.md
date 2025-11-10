  # Adventure Works bike shop -dashboard
  
### 1.	🚴‍♂️ Adventure Works Power Bi Dashboard - Sales, Customer & Product Insights
An interactive Power BI dashboard built for AdventureWorks, a global cycling equipment manufacturer. The project transforms raw CSV data into meaningful business insights through data modeling, DAX measures, and visually rich dashboards.

### 2. Purpose
As a newly hired Business Intelligence Analyst at AdventureWorks, the goal was to help management track key performance metrics — including sales, revenue, profit, and returns — while enabling detailed analysis of regional performance, product trends, and high-value customers.

The dataset included raw CSV files on transactions, returns, products, customers, and sales territories. Using Power BI Desktop, the following tasks were completed:

🔗 Connected and transformed raw data into a clean data model

🧩 Built a relational data model with proper relationships

⚙️ Created calculated columns and measures using DAX

📈 Designed interactive dashboards — Executive, Customer, and Product pages

### 3.	🧰 Tools & Technologies Used

The dashboard was built using the following tools and technologies:<br>
•	📊 Power BI Desktop – Main data visualization platform used for report creation.<br>
•	📂 Power Query – Data transformation and cleaning layer for reshaping and preparing the data.<br>
•	🧠 DAX (Data Analysis Expressions) – Used for calculated measures, dynamic visuals, and conditional logic.<br>
•	📝 Data Modeling – Relationships established among tables (resorts, snow, and data_dictionary) to enable cross-filtering and aggregation.<br>
•	📁 File Format – .pbix for development and .png for dashboard previews.


### 4.	Data Source

The dashboard was built using the AdventureWorks dataset — a sample business database representing a global manufacturing company that sells bicycles and related accessories.
The raw data was provided as multiple CSV files containing information on customers, products, Sales, Returns, Territory and calendar dates.

1. Calendar Lookup-
Provides the date dimension used for building time-based analyses such as monthly, quarterly, and yearly sales trends.

2. Customer Lookup-
Contains detailed customer information used for segmentation, demographics analysis, and identifying high-value customers.

3. Product Categories Lookup
Defines the top-level product categories (e.g., Bikes, Accessories, Clothing).

4. Product Subcategory Lookup
Acts as a bridge between product and category tables, allowing category-wise performance breakdown.

5. Product Lookup
Contains product-level information used to analyze profitability, sales trends, and product performance by category or model.

6. Sales Data
Main fact table used to calculate sales, revenue, and profit metrics across different dimensions.

7. Returns Data
Tracks returned items to calculate return rates and adjust profitability metrics.

8. Territory Lookup
Used for regional and geographical analysis of sales performance.


### 5.	Features / Highlights
• Business Problem

Adventure Works needed a unified reporting system to track business performance across customers, products, and overall revenue. The challenge was to understand which customers contribute the most revenue, which products are most profitable, and how sales trends evolve over time — insights that were previously buried in complex raw data.

• Goal of the Dashboard

To design an interactive Power BI solution that:
Monitors company-wide performance metrics (Revenue, Profit, Orders, Return Rate).<br>
Identifies top-performing customers and products driving profitability.<br>
Enables executives and managers to make data-driven pricing, marketing, and sales decisions.<br>
Provides drill-down views from a company-wide summary to individual customer and product levels.<br>

• Walkthrough of Key Visuals

1. Executive Dashboard (Overall Summary)

• Top KPIs: Revenue ($24.9M), Profit ($10.5M), Orders (25.2K), Return Rate (2.2%).

• Revenue Trending Line Chart: Tracks revenue growth from 2020–2022 with visible upward trajectory.

• Orders by Category (Bar Chart): Highlights contribution by Accessories, Bikes, and Clothing.

• Top 10 Products (Table): Lists best-selling items with their total revenue and return rates.

• Monthly Metrics: Compares current vs. previous month’s Revenue, Orders, and Returns.

• Most Ordered/Returned Products: Tires & Tubes lead in sales, Shorts show the highest return rate.

2. Customer Detail Dashboard

• KPIs: 17.4K Unique Customers | $1,431 Revenue per Customer.

• Customer Trend (Line Chart): Displays customer growth and average revenue per customer over time.

• Orders by Income & Occupation (Donut Charts): Show customer demographics and purchasing patterns.

• Top 100 Customers (Table): Lists customers by revenue, with Mr. Maurice Shan as the top contributor ($12.4K).

• Interactive Year Filter (2020–2022): Allows users to explore performance across different years.

3. Product Detail Dashboard

• Selected Product View: Example: AWC Logo Cap.

• KPIs: Monthly Orders (232), Monthly Revenue ($4,037), Monthly Profit ($1,373).

• Price Adjustment Slider: Simulates impact of pricing changes on revenue and profit.

• Profit Trending Line Chart: Compares actual vs. adjusted profit trends over time.

• Metric Selector: Switch between visualizing Orders, Revenue, Profit, or Return % dynamically.<br>
•	Business Impact & Insights

• Enabled faster decision-making with real-time performance tracking.
• Improved marketing focus by identifying high-value customers.
• Boosted profitability by revealing product and region-level insights.
• Reduced manual reporting with automated, interactive visuals.

### 6.	Screenshots / Demos

Executive Dashboard: ![Dashboard Preview](https://github.com/atashshaikh/Adventure-Works-dashboard/blob/main/executive_dashboard.png)
Customer Detail Dashboard: ![Dashboard Preview](https://github.com/atashshaikh/Adventure-Works-dashboard/blob/main/Customer_detail_dashboard.png)
Product Detail Dashboard: ![Dashboard Preview](https://github.com/atashshaikh/Adventure-Works-dashboard/blob/main/product_detail_dashboard.png)

