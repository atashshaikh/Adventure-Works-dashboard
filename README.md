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
The best dashboard explanation format. 
•	Business problem
•	Goal of the dashboard
•	Walk through of key visuals (briefly!)
•	Business impact & Insights

Example:
•	Business Problem
The global ski tourism industry generates billions in revenue, yet travelers, tour operators, and analysts often lack an intuitive way to compare resorts across countries. 

Key questions such as:
Which regions offer the most family-friendly or expert-level skiing?
Where is summer skiing available?
What countries have the most well-equipped resorts?
… are difficult to answer quickly with raw data.

•	Goal of the Dashboard
To deliver an interactive visual tool that:
Enables users to explore ski resorts globally.
Supports decisions such as vacation planning, regional marketing, or infrastructure investment.
Uncovers trends in terrain, accessibility, and tourism capacity by region and resort.

•	Walkthrough of Key Visuals
-	Key KPIs (Top Left)
Total number of resorts: 499
Resorts with summer skiing: 29
Resorts with night skiing: 204
Child-friendly resorts: 495
Countries covered: 38
Continents represented: 5
-	Continent Filter Panel
An interactive slicer lets users filter all visuals by selected continents, such as Europe or Asia.
-	Top Countries with Most Resorts (Bar Chart)
Bar chart ranks countries like Austria, France, and the U.S. by number of ski resorts.
-	Slopes by Resort (Line Chart)
Displays the distribution of slope types (beginner, intermediate, expert, and total). Helps identify which resorts favor beginners vs. experts.
-	 Resorts by Skill Level (Dual Line Charts)
Two line visuals side by side: one for resorts that cater to beginners, another for experts—allowing skill-level segmentation.
-	Elevation Stats (Grouped Bar Chart)
Compare the highest and lowest elevation points of resorts to understand terrain steepness and potential snow quality.
-	Lift Types by Resort (Stacked Bar Chart)
Stacked bar chart showing:
Gondola lifts
Chair lifts
Surface lifts
Total lifts
This helps users gauge resort infrastructure and capacity.

•	Business Impact & Insights

• Enabled faster decision-making with real-time performance tracking.
• Improved marketing focus by identifying high-value customers.
• Boosted profitability by revealing product and region-level insights.
• Reduced manual reporting with automated, interactive visuals.

### 6.	Screenshots / Demos
Show what the dashboard looks like. - ![Alt text](https://github.com/username/repo/assets/image.png)
Example: ![Dashboard Preview](https://github.com/atashshaikh/Adventure-Works-dashboard/blob/main/executive_dashboard.png)
 ![Dashboard Preview](https://github.com/atashshaikh/Adventure-Works-dashboard/blob/main/executive_dashboard.png)

