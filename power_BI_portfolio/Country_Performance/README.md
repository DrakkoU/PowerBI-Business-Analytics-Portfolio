Country Performance Analysis - Power BI Dashboard

Overview
This dashboard provides a strategic analysis of global market performance. It moves beyond basic revenue reporting to answer critical questions about profitability, efficiency, and the strategic value of each country.

Business Questions Answered
The dashboard is structured to answer seven core strategic questions:

    Which countries bring in the most revenue?

    How efficient are our top markets?

    Which countries bring in the least revenue?

    How efficient are our bottom markets?

    Which countries are the most profit efficient?

    Which countries are producing the most profits?

    How much revenue are our efficient markets generating?

Dashboard Features and Insights
The analysis is spread across three focused pages:

Page 1: Top 5 by Revenue
Purpose: Identifies the largest markets by sales volume.
Key Visuals: Ranking charts highlighting top revenue generators.
Insight: Answers questions 1 and provides context for 2.

Page 2: Bottom 5 by Revenue
Purpose: Highlights smallest or emerging markets.
Key Visuals: Ranking charts for the lowest revenue contributors.
Insight: Answers questions 3 and provides context for 4.

Page 3: Top 5 Profit: Efficient vs. Producing (Strategic Core)
Purpose: Compares raw profit production against operational efficiency.
Key Visuals:
Side-by-Scatter Plots: Directly compares the unit-economic profiles (Revenue per Unit vs. Cost per Unit) of the Top 5 Most Profitable Countries against the Top 5 Most Efficient Countries.
Interactive Trends: Supporting charts show historical performance.
Insight: Directly answers questions 5, 6, and 7. This page reveals if your largest profit generators (e.g., Singapore) are also your most efficient, or if you have highly efficient smaller markets (e.g., Cameroon, Lesotho) that provide a model for optimization.

Technical Implementation
Data Model: Built on a star schema with fact tables for sales and dimensions for Date, Country, and Product.
Key DAX Measures: The analysis is powered by custom DAX, including:
Profit Efficiency Score: A composite metric balancing Profit Margin % and Cost-to-Revenue Ratio.
Profit YoY Change: Calculates year-over-year profit growth.
Core unit economic metrics: Cost per Unit, Revenue per Unit, Profit Margin %.
Interactivity: Uses slicers and cross-filtering to enable drill down from regional views to country specific diagnostics.

Sample Insight
The dashboard enables direct comparison. For example, it can show that while Singapore is the 1 profit producer, Cameroon holds the top Profit Efficiency Score. Comparing their unit economics on the scatter plot reveals whether Cameroon's efficiency stems from superior cost control or pricing power, providing a clear strategic directive for improving other markets.

Files in This Folder
Country_Performance.pdf: Static PDF export of the dashboard.
screenshots/: Folder containing images of key interactions and insights.