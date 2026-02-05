Executive Metrics Overview - Power BI Dashboard



Overview

This dashboard serves as the central command center for executive leadership, providing a holistic, high-level view of the company's financial health, profitability drivers, and key operational trends. It consolidates critical metrics into a single, interactive page for strategic decision-making.



Business Question Answered

The dashboard is built to answer the core executive question: What's driving our profits?



Dashboard Features and Insights

The page, labeled "Profit \& Trends Executive View," is structured to answer this question through multiple analytical layers:



Headline Performance (KPI Cards)

- Metrics Displayed: Total Revenue, Total Cost, Total Profit, Total Units Sold, Total Order Count.

- Purpose: Provides an immediate, at-a-glance snapshot of absolute scale and overall business health for any selected time period.



Profit Trend Analysis (Area Chart)

- Purpose: Visualizes the trajectory of Total Profit over the 7-year period, highlighting peaks, troughs, and overall growth.

- Key Insight: At 51.54B, 2016 had the highest Total Profit and was 10.18% higher than 2010.



Profit Bridge Analysis (Waterfall Chart)

- Visualization: Shows the decomposition of profit into its core drivers: Starting Point > + Total Revenue > - Total Cost > Gross Profit.

- Purpose: Directly answers "What's driving profits?" by isolating the financial impact of revenue generation versus cost management in a given period.



Unit Economics Trends (Three Area Charts)

- Metrics Tracked: Revenue per Unit, Cost per Unit, and Margin per Unit over time.

- Purpose: Monitors the fundamental efficiency and pricing power of the business at a per-unit level, independent of sales volume.

- Key Insight: Reveals stability or shifts in core economics, e.g., "Across all 7 Years, Revenue per Unit ranged from 265.65 to 266.30."



Profit Margin and YoY Driver Analysis (Combined Area Chart)

- Metrics Combined: Profit Margin Year-over-Year % Change, Profit Impact from Revenue, and Profit Impact from Cost.

- Purpose: Analyzes the quality and drivers of profitability changes year-to-year, distinguishing between growth fueled by revenue versus cost control.



Revenue s& Volume Growth Correlation (Area Chart)

- Metrics Compared: Revenue YoY % Change and Units Sold YoY % Change.

- Purpose: Examines whether top-line growth is driven by selling more units (volume) or achieving higher prices per unit (price/mix).

- Key Insight: Identifies periods of divergence, e.g., "Revenue YoY Change and Units Sold YoY Change diverged the most in 2013."



Technical Implementation

- Data Model: Built on a unified star schema. A key technical accomplishment was establishing a reliable relationship between the main sales fact table and a separate order counts table on the Year field, ensuring all headline KPI cards (like Total Order Count) filter correctly with the Year slicer.

- Key DAX Measures: The dashboard is powered by a suite of advanced time-intelligence and decomposition measures, including:

- Profit YoY % Change

-`Profit Impact from Revenue and Profit Impact from Cost

- Revenue per Unit, Cost per Unit, Margin per Unit

- Interactivity: Utilizes slicers (notably Year) to allow dynamic exploration of trends and driver analysis across different time periods.



Sample Narrative Insight

The dashboard's analytical depth is demonstrated by its ability to generate coherent narratives from complex metrics, such as:

"At 51.54B, 2016 had the highest Total Profit and was 10.18% higher than 2010, which had the lowest. 2016 accounted for 15.02% of Total Profit. Across all 7 Years, Revenue per Unit ranged from 265.65 to 266.30. Revenue YoY Change and Units Sold YoY Change diverged the most in 2013."

This synthesis allows executives to quickly grasp scale (2016's peak), stability (tight range of Revenue per Unit), and anomalous periods for investigation (2013's growth divergence).



Files in This Folder

- Executive_overview.pdf: Static PDF export of the dashboard.

- screenshots/: Folder containing images that showcase the layout and the interactive filtering of key visuals.

