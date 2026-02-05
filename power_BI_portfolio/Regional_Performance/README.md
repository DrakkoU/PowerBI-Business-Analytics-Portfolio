Regional Performance Analysis - Power BI Dashboard



Overview

This dashboard provides a high-level strategic scorecard for regional business performance. It analyzes profitability concentration and operational efficiency at the regional level, offering leaders a clear view of which geographic areas are the primary profit drivers and how efficiently they operate.



Business Questions Answered

The dashboard is built to answer two core strategic questions for leadership:

1. Which Regions Have The Most Profit?

2. How Efficient Are They?



Dashboard Features and Insights

The dashboard answers these questions through a focused, regional-level lens:



Profit Concentration and Ranking

- Purpose: To visually and quantitatively identify which regions contribute the most to overall profit.

- Key Visuals: A thermal map (heatmap) shows profit concentration by region through color intensity. A supporting bar chart provides an exact ranking of regional profit.

- Key Insight: "Sub-Saharan Africa accounted for 26.03% of Total Profit," clearly identifying the core profit centers.



Regional Efficiency Diagnosis

- Purpose: To compare the fundamental unit economics (cost and revenue per transaction) across regions.

- Key Visuals: A scatter plot compares Cost per Unit against Revenue per Unit for each region.

- Key Insight: This visual allows for direct comparison of business models, revealing, for example, that "North America operates on a high-cost, high-revenue unit economic model" compared to other regions.



Profit Health Trend Analysis

- Purpose: To track the stability and year-over-year changes in regional profitability over time.

- Key Visuals: A line chart tracks Profit Margin % and Profit Margin YoY % Change across the 7-year period.

- Key Insight: Automated analysis can describe trends and stability, noting that "Profit Margin ranged from 29.48% to 29.56%" and identifying years of divergence between margin levels and growth rates.



Technical Implementation

- Data Model: Built on a star schema with sales data aggregated to the regional level, linked to a Date dimension for time intelligence.

- Key DAX Measures: The analysis is powered by custom measures, including:

	- Profit Margin % and Profit Margin YoY % Change

	- Cost per Unit and Revenue per Unit (calculated at the regional level)

	- Regional contribution to total metrics (e.g., % of Total Profit)

- Interactivity: The dashboard uses slicers for high-level filtering and visual interactions (e.g., clicking a region on the bar chart to highlight its position on the scatter plot) to connect related insights. It is designed as a regional summary; country-level drill-through is not part of this view.



Sample Analytical Output

The dashboard enables clear, regional-level insights such as:

1.  Profit Concentration: "Sub-Saharan Africa is the dominant profit hub, contributing over a quarter of total profit."

2.  Efficiency Benchmarking: "North America has the highest unit costs but also the highest unit revenues, indicating a premium market position."

3.  Trend Stability: "Overall regional profit margins have remained highly stable between 29.5% and 29.6% over seven years, with 2012 showing the greatest internal variance between margin level and growth rate."



Files in This Folder

- Regional_Performance.pdf: Static PDF export of the dashboard.

- screenshots/: Folder containing images that showcase the thermal map, regional rankings, and the interactive filtering between visuals.

