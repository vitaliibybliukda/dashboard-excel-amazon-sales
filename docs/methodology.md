# Data Analysis Methodology

## Data Cleaning Steps (Power Query)
1. Removed duplicates based on Order_ID
2. Filled missing values in Discount column with 0
3. Converted Date column to proper date format
4. Created calculated column: Revenue = Quantity × Unit Price
5. Filtered out test orders (Order_ID starting with "TEST")

## Analysis Approach
- Time series analysis: Monthly revenue trends
- Segmentation: By Region, Category, Year
- KPI calculation: Profit Margin, AOV, YoY Growth

## Tools Used
- Power Query for ETL (Extract, Transform, Load)
- Pivot Tables for aggregation
- Excel Charts for visualization
