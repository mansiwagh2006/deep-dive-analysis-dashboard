📊 Task 3: Deep-Dive Analysis & Interactive Dashboarding
📌 Objective

The objective of this task was to perform a deep-dive analysis on the cleaned sales dataset and build an interactive dashboard to answer complex business questions.
This task focuses on defining meaningful KPIs, analyzing trends, and presenting insights using a BI tool.

🔍 Approach & Methodology
1️⃣ Defining Core KPIs

Based on insights from Exploratory Data Analysis, the following Key Performance Indicators (KPIs) were defined to evaluate business performance:

🔹 KPIs Used
1. Total Revenue

Formula:
Total Revenue = SUM(total_sales)

Business Relevance:
Measures overall business performance and sales growth.

2. Total Orders

Formula:
Total Orders = DISTINCT COUNT(order_id)

Business Relevance:
Indicates customer demand and order volume.

3. Average Order Value (AOV)

Formula:
AOV = Total Revenue / Total Orders

Business Relevance:
Shows average revenue generated per order and helps in pricing and upselling decisions.

4. Total Quantity Sold

Formula:
Total Quantity Sold = SUM(weight_kg)

Business Relevance:
Helps understand product demand and inventory movement.

2️⃣ Deep-Dive Analysis

A Product Performance Analysis was selected as the deep-dive area.

The analysis focused on:

Revenue contribution by product

Quantity sold by product

Monthly revenue trends

Comparison between high-revenue and low-revenue products

This helped identify:

Top-performing products

Seasonal demand patterns

Products with high volume but low revenue (pricing insights)

3️⃣ Interactive Dashboard Development

An interactive dashboard was built using Power BI, allowing users to dynamically explore data.

📊 Dashboard Features
🔹 Visuals Included

KPI Cards:

Total Revenue

Total Orders

Average Order Value

Total Quantity Sold

Line Chart:
Monthly Revenue Trend

Bar / Column Charts:

Revenue by Product

Quantity Sold by Product

🔹 Filters (Slicers)

Year

Month

Product Name

These slicers allow users to:

Analyze performance by time period

Compare product-wise performance

Interact with KPIs in real time

📈 Key Insights

A few products contribute the majority of revenue.

Monthly revenue shows clear seasonal trends.

Some products sell in high quantity but generate lower revenue, indicating pricing differences.

🧠 Business Recommendations

Focus marketing efforts on high-revenue products.

Re-evaluate pricing strategies for high-volume, low-revenue products.

Use seasonal trends for better inventory planning.

🛠 Tools Used

Power BI – Interactive dashboard creation

Python (Pandas) – Data preparation

Excel – Validation and calculations

GitHub – Version control and documentation
