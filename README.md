Online Shoe & Product Sales Performance Dashboard (Power BI)
An interactive, dark-themed Power BI dashboard engineered to track, analyze, and optimize online sales performance across multiple product categories, with a primary focus on shoe and apparel sales trends. This project transforms raw e-commerce transaction data into actionable business intelligence by utilizing DAX-driven time intelligence metrics (YTD and QTD), custom categorical breakdowns, and clean UI/UX reporting.

Project Overview
Understanding time-relative revenue growth is critical for online retail operations. This dashboard delivers comprehensive visibility into Year-to-Date (YTD) and Quarter-to-Date (QTD) financial health, volume movement, customer engagement, and seasonality trends across product lines.

Domain: E-Commerce / Retail Analytics

Tool Used: Microsoft Power BI Desktop, DAX, Power Query

Data Sources: Transactional sales records, product dimension tables, and dedicated Date tables

Key Features & Metrics
Executive KPI Cards:

YTD Sales: Cumulative year-to-date gross revenue.

QTD Sales: Current quarter financial progress against baseline targets.

YTD Products Sold: Total unit volume delivered across categories.

YTD Customer Reviews: Volume indicator reflecting customer engagement and post-purchase feedback.

Monthly & Weekly Sales Trends: Visualizes historical performance and demand spikes across the calendar year (from January through December) to isolate promotional seasonality.

Category Contribution Matrix: Deep-dive breakdown comparing category metrics (such as Men Shoes, Men Clothes, Cameras, and Electronics) with custom indicators like % Grand Total (%GT) YTD Sales.

Top Product & Customer Review Analytics: Ranked horizontal bar charts displaying revenue by individual product brand/model alongside average review volumes.

Interactive Slicers: Dynamic filtering by Product Category and Quarter to isolate shoe-specific performance versus broader catalog performance.

Technical Implementation
Data Modeling: Star schema linking transaction tables with a dedicated calendar Date Table to support robust DAX time-intelligence functions.

DAX Formulas: Custom measures written for:

Dynamic YTD / QTD revenue aggregations (TOTALYTD, TOTALQTD, DATESYTD).

Relative percentage contribution (DIVIDE, ALLSELECTED).

Design & UI Architecture: Custom dark neon interface built with high visual hierarchy, styled containers, consistent typography, custom-aligned matrix padding, and custom branding.
