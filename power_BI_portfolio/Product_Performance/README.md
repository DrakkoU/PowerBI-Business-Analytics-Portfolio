Product Performance and Profile - Power BI Dashboard

Overview
This single-page dashboard is an interactive diagnostic tool for analyzing the product portfolio. It connects high-level profit rankings with detailed trends, key market performance, and strategic unit economics for any product, enabling comprehensive strategic and operational reviews.

Business Questions Answered
The dashboard is engineered to answer four critical business questions:
1. What Is The Product Profit Growth Over Time?
2. Which Items Are Producing The Most Profit?
3. In Which Countries Are The Most Units Sold?
4. What Are The Product's Efficiency and Strategic Profile?

Dashboard Features and Insights
The dashboard integrates four coordinated visuals, all synchronized by a master product slicer:

1. Product Profit Ranking (Clustered Column Chart)
- Purpose: To identify the top and bottom contributors to overall profit at a glance.
- Metric: Total Profit by Item Type.
- Insight: Instantly answers "Which Items Are Producing The Most Profit?" (e.g., Cosmetics leads at ~63B, followed by Household at ~60B).

2. Profitability Health Trend (Area Chart)
- Purpose: To assess the stability and trajectory of a product's profit quality over time.
- Metric: Profit Margin %` trend over the 7-year period.
- Insight: Answers "What Is The Product's Profit Growth Over Time?" by showing whether a product's margin is improving, stable, or declining, indicating the sustainability of its profitability.

3. Key Market Analysis (Line Chart)
- Purpose: To reveal the geographic markets that drive the highest sales volume for a selected product.
- Metric: Total Units Sold for the Top 5 Countries.
- Insight: Directly answers "In Which Countries Are The Most Units Sold?" for the selected item (e.g., Cosmetics top volume market is Greenland, Household's is Honduras).

4. Strategic Profile (Scatter Plot)
- Purpose: To diagnose the fundamental business model and efficiency of each product.
- Metrics: Cost per Unit vs. Profit (or Margin per Unit), with bubble size representing Total Units Sold.
- Insight: Answers "What Are The Product's Efficiency and Strategic Profile?" by classifying it as a high-cost premium item, a low-cost volume driver, or another archetype based on its position on the plot.

Interactive Workflow
A master Item Type slicer controls the page. Selecting a product (e.g., "Cosmetics") filters the Area Chart, Line Chart, and Scatter Plot to display coordinated data exclusively for that item. The Clustered Column Chart provides the constant ranking context. This creates a seamless analytical path from general ranking to specific product diagnosis.

Technical Implementation
- Data Model: Built on a star schema with a central sales fact table connected to dimensions for Date, Product (Item Type), and Country.
- Key DAX Measures: The analysis is powered by custom measures, including:
    - `Total Profit`
    - `Profit Margin %`
    - `Cost per Unit`, `Margin per Unit`
    - Market concentration logic for Top N countries.
- Interactivity: Utilizes slicer-based filtering and visual interactions to ensure all diagnostic visuals respond to the selected product, providing a unified profile.

Sample Insight: Analyzing a Top Performer
Selecting "Cosmetics" reveals a complete strategic profile:
- Scale: Confirmed as the #1 profit contributor (~63B).
- Profit Health: The Profit Margin Area Chart shows whether this leading margin is stable or trending.
- Key Market: The Line Chart identifies Greenland as its primary volume hub.
- Strategic Profile: The Scatter Plot shows whether its high profit is driven by superior unit economics (high margin per unit) or sheer volume, defining its strategic category.

This workflow moves from a simple ranking to a deep understanding of why a product is successful and where its potential vulnerabilities or opportunities lie.

Files in This Folder
- Product_Performance.pdf: Static PDF export of the dashboard.
- screenshots/: Folder containing images demonstrating the interactive layout and the filtered views of specific products.