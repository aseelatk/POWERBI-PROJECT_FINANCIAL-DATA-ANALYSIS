# Power BI Financial Analysis Project
# Project Overview
This project provides a comprehensive financial analysis using Power BI to visualize and evaluate key metrics for a sample financial dataset. The goal is to gain insights into sales, profitability, and business segments across various countries, helping stakeholders make informed business decisions.

# Dataset
The dataset used is the Financial Sample dataset, which includes:

Segment: Business segment (e.g., Government, Midmarket).
Country: Country where sales occurred.
Product: Product category.
Discount Band: Applied discount, if any.
Units Sold: Number of units sold.
Manufacturing Price, Sale Price, Gross Sales, Discounts, Sales, COGS (Cost of Goods Sold), Profit: Financial metrics for each sale.
Date, Month Number, Month Name, Year: Temporal information related to each sale.
# Key Performance Indicators (KPIs)
This report includes several KPIs to provide quick insights into financial performance:

Total Sales: Total revenue generated from all transactions (118.73M dollar)
Total Profit: Profit after accounting for COGS.(16.89M dollar)
Profit Margin: Percentage of profit over total sales.(14.23%)
Units Sold: Total quantity of units sold across all transactions.(1.13)

# Visualizations and Insights
The report includes a minimum of 7 visuals to deliver a comprehensive view of the data, along with insights from each.

# 1.Sales by Country:

Insight: The highest sales volumes are in USA, followed by Canada. This suggests strong market presence and demand in these regions, potentially due to regional pricing strategies or product preferences.The sales figures across all five countries are relatively balanced, with no extreme outliers. This indicates a well-distributed sales network across these regions.Given Mexico’s lower sales compared to other countries, it may offer an opportunity for increased marketing or sales efforts.

# 2.Sales by Segment:

Insight: Government and Small Business segments are your strongest revenue drivers, with Government leading in both sales and profitability.
The Enterprise segment is showing concerning negative profits, despite ranking third in sales, suggesting an issue with costs or pricing.
Midmarket has potential for growth in sales while maintaining strong profitability.
Channel Partners offer excellent efficiency, with high profit margins relative to their sales volume.

Recommendations:Investigate the Enterprise segment’s losses to identify the root cause and resolve profitability issues.
Consider strategies to increase sales in Midmarket and Channel Partners, as they are highly profitable relative to their current sales

# 3.Sales vs. Profit:

Insight: There’s a positive correlation between sales and profit; however, some regions with high sales volumes show lower profit margins, highlighting potential areas for cost optimization.

# 4.Profit Trend Over Time:

Insight: Overall Upward Trend:

From early 2014 to the end of 2014, there is an upward trend, culminating in the highest profit in December 2014. This indicates growth momentum and improving profitability over the year.
# 5.Product Performance:

Insight: Paseo,VTT and Velo products contribute the most to overall sales, suggesting these products are top sellers and may be core to the product line strategy.

# 6.Discount Impact on Sales:

Insight: Sales volumes are significantly higher for transactions with discounts, showing that customers respond well to price reductions and promotions. This could inform future discount strategies to boost sales.
# 7.Top 5 Countries by Profit:

Insight: France leads in profitability, indicating high demand and effective cost management. 

# Overall Conclusion from Financial Analysis:
The financial analysis reveals that the United States, Canada, and France are the top-performing countries, with Government and Small Business segments driving the most sales. Paseo is the leading product, while medium and high discounts prove most effective in boosting sales. December shows the highest profit peak, indicating a seasonal trend. To enhance revenue, focus on high-performing regions and products, prioritize government and small business segments, and prepare for seasonal peaks with targeted promotions. Utilizing medium discounts strategically can further maximize sales across various customer segments.

# Strategic Recommendations:
Focus Marketing Efforts on High-Performing Countries and Products: Prioritize resources towards the U.S., Canada, and top-selling products (Paseo, VTT, Velo) to maximize revenue.
Capitalize on High-Growth Segments: Emphasize government and small business sales efforts while identifying potential opportunities within midmarket and enterprise segments.
Optimize Seasonal Sales Strategies: Plan promotions and inventory for December to leverage peak profit opportunities.
Apply Targeted Discounts: Utilize medium and high discounts selectively to boost sales, especially in lower-performing regions or product lines.
This comprehensive analysis provides actionable insights for strengthening sales strategies, optimizing discounts, and prioritizing profitable markets and products.

## Power BI Features and Techniques Used:
1.DAX Measures: Custom measures for KPIs, including Sales Growth Percentage and Profit Margin.
2.Data Transformation: Cleaned and structured data in Power Query Editor.
3.Formatting: Gradient backgrounds, custom color schemes, and data labels for visual clarity.
4.Interactive Elements: Drill-down options, filter options, and slicers for dynamic analysis.
