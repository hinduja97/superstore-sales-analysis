# superstore-sales-analysis
Power BI dashboard analyzing 4 years of retail sales data with Python EDA

Project Overview
Duration: October 2024 - December 2024
Tools: Power BI, Python (Pandas, Matplotlib, Seaborn), DAX, Power Query
Dataset: 9,994+ transactions across 4 years (2021-2024)
Comprehensive exploratory data analysis of retail sales data to identify customer behaviors, product performance trends, and seasonal patterns for strategic inventory optimization.

Business Problem
The organization needed data-driven insights to:

Optimize inventory levels across seasons
Identify high-performing products and categories
Understand customer purchasing behaviors
Improve profit margins through strategic planning


Key Findings & Business Impact
4-Year Performance Summary

Total Sales: $1.95M+ across all years
Total Profit: $250K+ with sustained profit margins
Peak Year: 2024 with $732.6K in sales (93.3K profit)
Growth Trajectory: Consistent year-over-year growth

Year-by-Year Breakdown
YearSalesProfitQuantityDiscountProfit Margin2021$128.7K$17.1K1,986$81.713.3%2022$180.7K$20.1K2,839$109.411.1%2023$187.5K$24.1K3,025$94.412.9%2024$732.6K$93.3K12,500$518.012.7%
Critical Seasonal Insights

Q4 drives 38-53% of annual revenue across all years
November & December are peak months - consistent pattern
Q1 weakest quarter (5-17% of sales) - promotional opportunity
Recommendation: Increase Q4 inventory by 30% based on historical patterns

Product Category Performance (2024 Data)
Technology - $271.5K (37.1%)

Highest revenue category
Profit contribution: $50.7K (54.3% of total profit)
Top performer: Canon imageCLASS 2200 ($35.7K)

Office Supplies - $245.8K (33.6%)

Consistent performer
Profit: $39.7K (42.5% of total)
Steady demand across all quarters

Furniture - $215.3K (29.4%)

Growing category
Profit: $3.0K (3.2% of total) - needs margin improvement
Opportunity for product mix optimization

Top 10 Products (All-Time Revenue Leaders)

Canon imageCLASS 2200 Advanced Copier - $85.5K
Fellowes PB500 Electric Binding Machine - $28.2K
GBC DocuBind TL300 Electric Binding System - $20.1K
Hewlett Packard LaserJet 3310 Copier - $21.4K
HON 5400 Series Task Chairs - $19.7K
Cubify CubeX 3D Printer - $12.8K
Canon PC1060 Personal Laser Copier - $11.6K
GBC DocuBind P400 Electric Binding System - $11.4K
Riverside Palais Royal Lawyers Bookcase - $11.7K
3D Systems Cube Printer - $14.2K

Customer Segmentation (2024)
Consumer Segment - $331.3K (45.2%)

Largest customer base
Most valuable segment by volume
Focus for loyalty programs

Corporate Segment - $241.9K (33.0%)

High-value B2B customers
Bulk order opportunities
Relationship management priority

Home Office Segment - $159.5K (21.8%)

Growing segment
Remote work trend driver
Targeted marketing opportunity

Geographic Distribution (2024)

West Region: Strongest performance
East Region: Second-highest sales
Central Region: Consistent growth
South Region: Expansion opportunity

Shipping Preferences (2024)

Standard Class: 53.9% (most popular)
Second Class: 20.3%
First Class: 19.1%
Same Day: 6.7%


Actionable Recommendations
1. Inventory Optimization
 Increase Q4 stock by 30% - Q4 consistently generates 38-53% of annual revenue
 Focus on Technology products - highest margins and demand
 Review Furniture pricing - profit margin only 3-7%, needs optimization
 Monitor Canon & Fellowes products - top revenue generators
2. Seasonal Strategy
 Pre-Q4 campaigns - Start promotional activities in September
 Q1 promotions - Combat slowest quarter with targeted discounts
 Mid-year engagement - Q2/Q3 steady-state maintenance
3. Customer Retention
 Consumer loyalty program - Largest segment at 45%
 Corporate account management - High-value B2B relationships
 Home Office targeting - Capitalize on remote work trends
4. Product Strategy
 Expand Technology category - 54% profit contribution
 Office Supplies bundling - Consistent demand driver
 Furniture margin improvement - Renegotiate supplier costs or adjust pricing

 Technical Implementation
Data Processing

Dataset: 9,994 transactions
Features: 21 columns (Order Date, Customer, Product, Sales, Profit, etc.)
Time Range: 2021-2024 (4 years)
Cleaning: Removed duplicates, handled missing values, standardized formats
