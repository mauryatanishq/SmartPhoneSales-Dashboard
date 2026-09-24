# Mobile Sales Dashboard

An interactive Power BI dashboard built to analyze mobile phone sales performance across brands, regions, payment methods, and time — turning raw transaction data into a clear picture of where revenue is coming from and why.

## Situation
Raw mobile sales transaction data (brand, model, city, payment method, date, quantity, and sales value) had no structure for spotting trends — no way to quickly answer which brands were winning, which cities were driving revenue, or when demand peaked.

## Task
Build a single-view dashboard that lets a business stakeholder answer, at a glance:
- Which brands and models are generating the most revenue
- Which regions are contributing the most to sales
- How demand shifts across months and payment methods
- What the typical transaction looks like (volume, value, frequency)

## Action
- Cleaned and structured the raw dataset using Power Query, handling inconsistent city names and missing values
- Built DAX measures for total sales, quantity, transaction count, and average transaction value
- Designed a filterable dashboard with slicers for mobile model, payment method, brand, and day of week
- Added a geographic map visual to surface city-level performance, and trend visuals to track monthly and daily patterns
- Built brand and payment-method breakdowns to compare performance at a category level

## Result — key insights
- **Total sales reached 769M** across 19K units sold and 4K transactions, with an average transaction value of 40K.
- **Apple led all brands** with 162M in sales, ahead of Samsung (160M), OnePlus (154M), Vivo (150M), and Xiaomi (144M).
- **Delhi contributed the largest regional share**, accounting for 26% of total revenue — more than any other city.
- **UPI was the most-used payment method**, contributing roughly 26% of total revenue, narrowly ahead of Credit Card and Cash.
- **Demand fluctuated month to month** rather than following a flat trend, with visible peaks worth investigating further against promotions or seasonal demand.

## Tools used
- Power BI
- Power Query (data cleaning and transformation)
- DAX (calculated measures)

## Dashboard preview
![Dashboard](SmartPhone_Sales_Dashboard.png)
