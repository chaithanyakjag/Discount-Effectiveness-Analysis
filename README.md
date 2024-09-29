# Discount Effectiveness Analysis: Optimizing Sales and Profitability

## Project Overview

This project aims to analyze how discounts affect sales, profitability, and customer behavior. Using data-driven insights, we assess the impact of discount ranges on different product categories and customer segments to propose optimized discount strategies that maximize profitability without compromising sales volume.

## Key Objectives
1. Understand the relationship between discounts, sales, and profitability:
    - Analyze how different discount levels impact overall sales and profit margins.
    - Identify the optimal discount range to boost sales without leading to significant profit loss.
2. Segment customers by discount sensitivity:
    - Group customers based on their purchase frequency in various discount ranges.
    - Identify which segments respond best to discount strategies and suggest targeted marketing approaches.
3. Assess the impact of discounts on different product categories:
    - Explore how discounts affect different categories (e.g., Furniture, Technology, Office Supplies) in terms of sales and profit.
    - Recommend category-specific discount thresholds for future promotions.

## Data Used
The dataset contains the following relevant columns:
Order ID: Unique identifier for each order.
Customer ID: To track repeat purchases and customer behavior.
Sales: The total sales value of each order.
Profit: The profit margin for each order.
Discount: The discount percentage applied to each order.
Quantity: The number of items sold in each order.
Order Date: To track sales over time and observe seasonal trends.
Product Category: Categories such as Furniture, Technology, and Office Supplies.

## Project Workflow

1. Data Preprocessing
  - Handled missing values and ensured that all columns, especially Order Date, were in the correct format for time-based analysis.
  - Created new columns for Discount Range to simplify analysis across different discount levels (e.g., 0–10%, 10–20%, etc.).

2. Exploratory Data Analysis (EDA)
  - Correlation Analysis: Analyzed the correlation between Sales, Profit, and Discount to understand relationships between these variables.
  - Discount vs. Sales and Profit: Created visualizations to explore how discounts impact sales and profitability at different discount levels.
  - Customer Segmentation by Discount Sensitivity: Grouped customers based on their purchase frequency in different discount ranges.

3. Key Visualizations
  - Correlation Heatmap: Displayed the relationships between sales, profit, and discounts.
  - Sales and Profit by Discount Range: Visualized the effect of discount levels on sales and profit.
  - Customer Purchase Frequency: Analyzed how frequently customers purchase based on discounts.
  - Unique Customers by Discount Range: Explored how different discount levels attract unique customers.
  - Sales and Profit by Product Category: Showed the impact of discounts on various product categories.

4. Recommendations
Based on the analysis, the following key recommendations are proposed:
1. Optimal Discount Range:
   - The 10–20% discount range is the most effective in boosting sales and maintaining profitability across most categories.
2. Category-Specific Discounts:
  - Limit discounts on high-margin products like Furniture and Technology to below 20% to avoid profit losses.
  - For Office Supplies, discounts up to 20% may be used as higher discounts lead to losses.
3. Targeted Promotions:
  - Target high-frequency buyers with loyalty programs to increase retention and purchase frequency.
  - Use deep discounts (40%+) selectively for deal-seeking customers or for clearance sales to offload excess inventory.

## Results

The project successfully identified:
  - The optimal discount range to balance between maximizing sales and protecting profits.
  - Unique customer segments that respond differently to discount strategies, providing opportunities for targeted marketing.
  - Category-specific recommendations for discount caps, ensuring that discounts do not erode profitability.

## Conclusion
This analysis provides a comprehensive understanding of how discounts affect sales and profitability. By using these insights, businesses can tailor discount strategies to customer segments and product categories, ensuring discounts are applied optimally to increase sales while preserving profitability.
