# 🗺️ Regional Sales Performance & Market Trend Dashboard

## Project Overview
This project looks at sales performance data for a U.S.-based retail store operating across 49 states, ~1,800 products, and 793 customers.

Using Tableau, the dashboard breaks down sales by state, city, and product sub-category, while also tracking how sales have changed over time and where they are likely headed. The goal is to give the business a clear picture of where sales are strongest, which products are driving the most revenue, and what to expect going forward.

## Business Problem
**The retail store** wants to better understand how sales are spread across different regions and product sub-categories, and how performance has been trending over time.

The challenge:
➡️ Identify which states, cities, and product sub-categories are leading in sales, and use historical trends to anticipate future performance.

## Dataset
- 9,994 transactions across 5,009 unique orders
- ~1,800 products, 793 customers, spanning 49 U.S. states
- Key fields include: `Sales`, `State`, `City`, `Sub-Category`, `Order Date`
- Store dataset covering sales performance across regions, products, and time periods

## Tools & Technologies
- **Tableau**

## Data Preparation / Methodology
Data was clean and required no pre-processing prior to import into Tableau. All calculations and aggregations were handled directly within Tableau using calculated fields and navigation actions.

## Dashboard Features
- **Back navigation button:** A calculated field powers a "Home Page" button that lets users return to the primary dashboard after drilling into a detailed view, keeping navigation smooth and user-friendly
- **State-level drill-down:** Clicking on a state (defaulting to New York) filters all relevant visuals to show performance specific to that state
- **Sub-category filter:** Allows users to focus on specific product sub-categories across all dashboard views
- **Sales forecast:** The trend chart extends beyond historical data to give a forward-looking view of expected sales performance

## Calculated Fields & Parameters

**Calculated Fields:**
```
// Back — powers the Home Page navigation button for returning to the primary dashboard
'Home Page'
```

## Visualizations Included
- 📌 **Map — Sales Across States:** Shows how total sales are distributed across the 49 states, making it easy to spot the strongest and weakest regions at a glance
- 📌 **Symbol Map — Sales Across Cities:** Breaks state-level sales down further to the city level, with bubble sizes reflecting sales volume
- 📌 **Pareto Chart — Sub-Category Sales:** Combines a bar chart and cumulative line chart to show which sub-categories drive the most sales and how many sub-categories account for the majority of revenue
- 📌 **Continuous Line Chart — Sales Trend & Forecast:** Tracks how sales have moved over time and projects future performance based on historical patterns

 [**Dashboard Overview**]
 <img width="1366" height="768" alt="Screenshot (583)" src="https://github.com/user-attachments/assets/7eb6f87e-8b70-40c5-807b-f279d4d5df6e" />

🔗 **[View Live Dashboard on Tableau Public](https://public.tableau.com/views/RegionalSalesPerformanceMarketTrendDashboard/PrimaryDashboard?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)**

## Key Insights
- **Regional sales concentration:** → A handful of states bring in the majority of total sales, while many others contribute relatively little — showing that sales performance is not evenly spread across the country
- **City-level variation:** → Even within top-performing states, sales can vary a lot from city to city, meaning state averages do not always tell the full story
- **Pareto effect in sub-categories:** → A small number of product sub-categories account for a large share of total sales, following the classic 80/20 pattern — most revenue comes from relatively few product lines
- **Low-contributing sub-categories:** → A good number of sub-categories bring in very little sales compared to the top performers, raising questions about whether they are worth the shelf and marketing space they occupy
- **Sales trend over time:** → Sales show a general upward direction over the period covered, with some dips along the way that may reflect seasonal slowdowns or external factors
- **Sales forecast:** → Based on historical patterns, sales are expected to continue growing, though the pace and consistency of that growth will depend on how well regional and product-level opportunities are acted on

## Recommendations
- **Double down on top-performing states:** States that are already bringing in strong sales are worth more targeted marketing, better stock availability, and faster delivery to keep momentum going
- **Look more closely at underperforming states:** States with low sales should be assessed to understand whether the issue is low demand, limited awareness, pricing, or poor service coverage — then act accordingly
- **Use city-level data to guide local decisions:** Since performance varies a lot at the city level, decisions around promotions, stock, and logistics should be made with city-level data in mind, not just state averages
- **Invest more in the top-selling sub-categories:** The few sub-categories driving the bulk of revenue deserve more inventory investment, promotional support, and product range expansion
- **Review the low-performing sub-categories:** Sub-categories that contribute very little to overall sales should be reviewed — the store should consider whether to reposition them, reduce their prominence, or phase them out
- **Plan ahead using the sales forecast:** The projected sales trend gives the business a useful basis for planning stock levels, staffing, and marketing spend in the coming months
- **Investigate the dips in the sales trend:** The periods where sales dropped should be looked into to understand what caused them, so the business can plan around or prevent similar slowdowns in the future

## Outcome / Impact
This dashboard enables:
- ✅ A clear view of where sales are coming from across states and cities
- ✅ Quick identification of the product sub-categories driving the most revenue
- ✅ Better planning and resource allocation using historical trends and forecasts
- ✅ Smarter regional and product strategies based on actual sales data

## Next Steps
- Layer in profitability data to understand not just where sales are high, but where the business is actually making money
- Add customer segmentation to see which types of customers are driving sales in each region
- Connect to a live data source so the dashboard updates automatically with new transactions
