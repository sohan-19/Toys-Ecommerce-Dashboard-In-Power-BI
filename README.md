Toys Ecommerce Dashboard In Power BI

An end-to-end Power BI dashboard analyzing sales, marketing campaign performance, and website conversion funnel data for a toy store's ecommerce business (2012–2015).

Project Overview

This project transforms raw ecommerce transaction, session, and page-view data into an interactive Power BI dashboard that helps stakeholders understand revenue drivers, campaign ROI, seasonality, and funnel drop-off — enabling data-backed decisions on inventory, marketing spend, and website optimization.

Dataset

The dataset covers 4 toy products sold between 2012–2015 and includes:

Order-level transaction data (orders, quantity, revenue, refunds)
Website session and page-view data (landing pages, product pages, checkout funnel)
Marketing campaign data (brand, nonbrand, pilot, desktop_targeted)
Time dimensions (Year, Quarter, Month)

Tools & Techniques
Power BI Desktop — data modeling, DAX measures, interactive visuals
DAX — custom KPIs (Revenue Per Order, Revenue Per Session, Refund Quantity, Average Time to Order)
Data Modeling — star-schema relationships across orders, sessions, and page views
Slicers & Cross-filtering — Product, Year, Quarter, Month, Campaign, URL

Dashboard Pages
Sales Overview — Total Orders, Revenue, Quantity Sold, Refunds, and Product-wise sales trends
Campaign Performance — Revenue per Order/Session by campaign, Total Revenue by Campaign, Sessions vs. Orders comparison
Funnel & Page View Analysis — Landing page and product page conversion comparison, website session-to-order funnel

Key Insights
Revenue concentration: One product — The Original Mr. Fuzzy — drove 62% of total revenue (~$1.15M of $1.85M) across all four years, making it the clear hero SKU.
Campaign efficiency gap: Nonbrand campaigns generated the most raw revenue (~$0.8M) and traffic (337K sessions), but brand campaigns had a higher revenue-per-session (4.5 vs. 3.8) — indicating more efficient, higher-intent traffic.

Underperforming channel flagged: The pilot campaign had the highest revenue-per-order (65) but the lowest revenue-per-session (0.7), suggesting a targeting/reach problem rather than a conversion problem.
Funnel drop-off: Of ~394K total website sessions, only 31,696 resulted in an order — an ~8% overall site conversion rate, with underperforming landers (e.g., lander-3 at ~3.4%) identified as key optimization targets.
Product-level conversion outlier: Hudson River Mini Bear converted at ~22% (views to orders) — the highest of all products — despite having the lowest traffic, suggesting untapped demand.
Seasonality: User traffic dipped from February to June and climbed steadily to a December peak, consistent with holiday-driven toy sales.
