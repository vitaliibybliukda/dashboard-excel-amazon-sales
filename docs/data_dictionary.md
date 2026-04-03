# Data Dictionary

## Dataset Overview
- **Source**: Amazon Sales Dataset (Kaggle)
- **Rows**: 10,000+ transactions
- **Date Range**: January 2023 - March 2026
- **Last Updated**: April 2026

## Column Descriptions

| Column Name | Data Type | Description | Example |
|-------------|-----------|-------------|---------|
| `Order_ID` | Text | Unique order identifier | ORD-10001 |
| `Order_Date` | Date | Transaction date | 2025-03-15 |
| `Product_Name` | Text | Product description | "Wireless Mouse" |
| `Category` | Text | Product category | Electronics |
| `Quantity` | Integer | Units sold | 3 |
| `Unit_Price` | Decimal | Price per unit | $29.99 |
| `Discount` | Integer | Discount percentage | 10 |
| `Revenue` | Decimal | Total sales (Qty × Price) | $89.97 |
| `Profit` | Decimal | Net profit after costs | $18.50 |
| `Region` | Text | Sales region | North, South, East, West |
| `Payment_Mode` | Text | Payment method | Credit Card, UPI, COD |

## Derived Metrics
- **Average Order Value (AOV)**: Total Revenue ÷ Total Orders
- **Profit Margin**: (Profit ÷ Revenue) × 100
- **YoY Growth**: [(Current Year - Previous Year) ÷ Previous Year] × 100

## Data Quality Notes
- Missing values in Discount column filled with 0
- Duplicate orders removed (based on Order_ID)
- Test orders filtered out
