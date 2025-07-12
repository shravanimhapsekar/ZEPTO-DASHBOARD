# Zepto-Dashboard
The Zepto Power BI Analysis project was initiated to derive meaningful business insights from sales and customer data. Zepto, as a growing quick-commerce platform, handles a large volume of transactional and product data across different outlets, locations, and product types. To make sense of this data and drive better decision-making, a Power BI dashboard was developed. This dashboard focuses on tracking key performance indicators (KPIs), visualizing trends, and identifying opportunities for business optimization.

## Problem Statement
Zepto required a detailed analysis of its sales performance, customer satisfaction levels, and inventory distribution across various outlets and regions. The objective was to understand which product categories perform best, how outlet characteristics affect sales, and how customer feedback varies with product attributes. The challenge was to compile and visualize this data in a way that’s easily interpretable and actionable for business stakeholders.

## Steps Followed
- Step 1 (Requirement Gathering / Business Understanding): Understanding the key metrics Zepto wanted to track, such as total revenue, item popularity, outlet performance, and customer ratings. Business goals were converted into measurable KPIs.
- Step 2 (Data Walkthrough): A thorough review of the dataset was conducted. This included identifying columns like Item Type, Outlet Size, Sales, Fat Content, Ratings, etc., and understanding how they could relate to each other.
- Step 3 (Data Connection): The raw data was connected to Power BI. Data was imported through Excel/CSV connectors and structured for analysis.
- Step 4 (Data Cleaning / Quality Check): The dataset was cleaned by removing duplicates, handling missing or incorrect values, and standardizing data formats. Ensured the integrity of the 'Sales' and 'Rating' fields, which were crucial for KPI calculations.
- Step 5 (Data Modeling): Relationships between relevant columns (e.g., Item Type and Sales, Outlet Type and Size) were created.
- Step 6 (Data Processing): Using Power Query, transformations were done such as grouping items, categorizing outlets, and splitting columns where needed for better granularity.
- Step 7 (DAX Calculations): Custom measures were created using DAX formulas:

      Total Sales = SUM('Zepto Grocery Data'[Sales])
      Average Sales = AVERAGE('Zepto Grocery Data'[Sales])
      No. of Items = COUNTROWS('Zepto Grocery Data')
      Average Rating = AVERAGE('Zepto Grocery Data'[Rating])
- Step 8 (Dashboard Layouting): The dashboard layout was structured logically, grouping charts by theme: product metrics, outlet performance, and customer insights. KPIs were placed at the top for quick reference.
- Step 9 (Charts Development and Formatting): Multiple charts were created including donut charts, bar graphs, funnel maps, stacked columns, and matrix cards. Each chart was styled consistently to maintain readability and visual harmony.

## Snapshot of Zepto Dashboard (Power BI Service)
<img width="1301" height="738" alt="Image" src="https://github.com/user-attachments/assets/43708ae6-b624-488e-82fa-fd7471798303" />

## Insights
1. The company achieved total sales of $1.20 million, with an average sale of $141 and a total of 8,523 items sold.
2. Customer satisfaction appears moderately high with an average rating of 3.9, consistent across outlet types.
3. Medium-sized outlets recorded the highest sales ($507.9K), followed by small ($444.79K) and high-sized ones ($248.99K).
4. Tier 3 outlets lead in total sales with $472.13K, showing strong rural or semi-urban performance.
5. Products with low fat content generated $776.32K in sales, nearly double the $425.36K from regular fat products.
6. Fruits & snacks lead with $0.18M each, followed by household items ($0.14M), indicating customer preference for daily essentials.
7. Supermarket Type1 leads with $787.55K in sales and 5,577 items sold, maintaining a consistent average sale ($141) and rating (3.9).
8. While sales are lower ($151.94K), grocery stores have the highest item visibility score (0.10), likely helping product discovery.
9. Outlet establishment peaked in 2018 with $205K, but dipped significantly in 2020 ($129K), likely due to pandemic effects.
10. After the 2020 dip, sales rebounded slightly, stabilizing around $131K in 2022, showing recovery and adaptation.

## Acknowledgements
This dashboard is built as part of a Data Visualization and Analytics learning project. Inspired by Data Tutorials – YouTube.
