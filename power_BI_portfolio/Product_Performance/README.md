Product Performance and Profile - Power BI Dashboard

Overview
This single page dashboard is an interactive diagnostic tool for analyzing product portfolios. It connects high level profit rankings with detailed trends, key market performance, and strategic unit economics for any product, enabling comprehensive strategic and operational insights.

Business Questions Answered
The dashboard is engineered to answer three critical business questions:

    Which Items Are Producing The Most Profit?

    Which Products Are The Most Efficient?

    In Which Markets Are The Most Units Sold?


Dashboard Features and Insights
The dashboard integrates a coordinated set of visuals, controlled by master slicers for Year, Top 5 Highest Demand Markets (Countries), and Item Type.

1. Product Profit & Unit Economics (Clustered Column & Scatter Plot)

    Question Answered: "Which Items Are Producing The Most Profit?"

    Visuals:

        Clustered Column Chart: Displays Total Profit by Item Type.

        Supporting Scatter Plot: Analyzes unit economics by plotting Cost per Unit vs. Revenue per Unit. Bubble size represents Total Revenue.

    Insight: Combines high level profit comparison with a detailed view of underlying unit economics for each product.

2. Unit Efficiency & Profile (Scatter Plot & Matrix)

    Question Answered: "Which Products Are The Most Efficient?"

    Visuals:

        Strategic Efficiency Plot: Visually classifies products by comparing their cost burden to their profit generation, with an indicator of sales velocity. 
	This reveals which products achieve high profits through superior margins versus lower costs.

        Supporting Matrix: Provides Profit Efficiency Score of items.

    Insight: Diagnoses the fundamental efficiency and strategic profile of each product by visualizing its cost structure and profitability.

3. Key Market Volume Analysis (Line Chart)

    Question Answered: "In Which Countries Are The Most Units Sold?"

    Visual: Line Chart displays high demand markets.

    Insight: Identifies the top geographic markets driving sales volume for the selected product.

Interactive Workflow
Master slicers for Year, Country (Top 5 by Units Sold), and Item Type control the page. Visual interactions are engineered with specific constraints:

    The Item Type slicer:

	- Filters the Key Market Analysis and Unit Efficiency sections.

	- Button Grid Slicer: Improves visual scan speed and selection clarity. selection color coding by item adds an immediate, intuitive layer 
	  of categorical information that a standard slicer lacks.

	- Integrating Scores on Buttons: This is a data-driven design choice. It surfaces a key metric (Item Efficiency Score) directly in the navigation, 
	  eliminating the need for the user's eye to jump to a separate matrix. It turns the filter mechanism into an information display.

    The Country slicer, populated by the Top 5 markets from the line chart, provides focused geographic filtering.

    The Year slicer provides temporal control.

    Selecting a product column or bubble will cross-filter other visuals to provide a coordinated, in depth diagnostic profile.

Key Insights:

    Meat operates on the thinnest margins, with a Cost to Revenue Ratio of 86.44%.

    Clothes is the most profit efficient category, with a Profit to Revenue Ratio of 67.20%.

    Cosmetics generates the highest total profit (63.4B), while the lowest producing is Fruits (880M).

    Cosmetics contributes to 18.46% of total profit.

    Total profit across the 12 product categories spans from 880M to 63.4B, indicating extreme variance in portfolio performance.

Technical Implementation

    Data Model: 

	Built on a robust, star schema data model, this dashboard utilizes advanced DAX calculations to deliver dynamic metrics for profitability, efficiency, and market analysis. 
	The interactivity layer is engineered to ensure fast performance and intuitive drill down from strategic overviews to operational diagnostics.
    
    Interactivity: 
	
	Utilizes slicer based filtering and carefully managed visual interactions to ensure a cohesive analytical flow.

Sample Insight: Analyzing a Top Performer
Selecting "Cosmetics" from the Item Type slicer reveals:

    Profit Scale: Its bar in the column chart shows it generates the highest Total Profit (~63.4B).

    Key Markets: The line chart highlights its top volume countries.

    Efficiency Profile: The efficiency scatter plot positions it based on its Cost-to-Revenue and Profit-to-Revenue ratios.

    Country Contribution: The country summary card displays a selected country's percentage contribution to Cosmetics' total profit and its efficiency rank within the Cosmetics market.

This workflow moves from identifying top profit generators to diagnosing their market presence, unit economics, and operational efficiency.

Files in This Folder

    Product_Performance.pdf: Static PDF export of the dashboard.

    screenshots/: Folder containing images demonstrating the interactive layout and the filtered views of specific products.
