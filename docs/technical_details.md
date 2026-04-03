# Technical Implementation Details

## Excel Version Requirements
- Microsoft Excel 2019 or Microsoft 365
- Power Query enabled
- Minimum screen resolution: 1366×768

## File Structure
- `analysis_master.xlsx`: Full version with all worksheets
  - Raw_Data (Power Query connection)
  - Pivot_SalesOverTime
  - Pivot_TopProducts
  - Pivot_ByRegion
  - Calculations
  - Dashboard
  
- `dashboard_view.xlsx`: Lightweight version
  - Dashboard only
  - File size: ~2 MB

## Power Query Steps
1. Source: CSV file import
2. Promote Headers: First row as column names
3. Change Type: Automatic type detection
4. Remove Duplicates: Order_ID column
5. Fill Down: Discount column
6. Custom Column: Revenue = [Quantity] * [Unit_Price]
7. Close & Load: To Data Model

## Known Limitations
- Maximum dataset size: 1 million rows (Excel limitation)
- Refresh time: ~15 seconds for 10K rows
- Slicers limited to 5 concurrent filters
