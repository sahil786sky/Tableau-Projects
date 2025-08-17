Amazon Product & Brand Analysis Dashboard

Overview:
This Tableau project analyzes Amazon product data to uncover insights about brands, categories, pricing, ratings, and discount patterns. The dashboard provides an interactive way to explore KPIs and detailed product performance.

Key Features:
Top 10 Brands by Rating – Highlights the brands with the best customer ratings.
Top 10 Categories by Rating Count – Shows product categories with the most customer engagement.
Price vs. Rating Scatter Plot – Visualizes the relationship between product pricing and average customer rating, with bubble size representing rating count.
Dynamic Filters – Interact with data by filtering brands or categories.
KPI Card – Displays overall dataset insights (total products, average rating, etc.).

Data Transformations:
Converted price fields (Actual Price and Discounted Price) from text to numeric.
Standardized discount percentage as a numeric field.
Added brand-level aggregations for rating and rating count.
Cleaned missing and invalid rating values.

Visualizations Included:
Bar Chart: Top 10 brands ranked by average rating (green gradient color scale).
Bar Chart: Top 10 categories ranked by rating count (red-to-green color scale).
Scatter Plot: Average rating vs. average price with bubble size for rating count, colored by rating scale.
KPI Card: Key summary metrics for the dataset.

Tools Used

Tableau Desktop – For creating dashboards and visualizations.

Oracle SQL – For cleaning, transforming, and preparing the dataset.

Insights Delivered:
Identified high-rated brands and high-engagement categories.
Analyzed how price affects ratings.
Provided a foundation for business decisions on product positioning and discounts.
