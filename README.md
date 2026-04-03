# 📊 Amazon Sales Performance Dashboard

> **Interactive Excel-based dashboard for sales analytics and business intelligence**  
> *Capstone Project for Correlation One × Amazon Data Analytics Program (Cohort 21)*

![Dashboard Preview](images/dashboard_preview.png)

[![Excel](https://img.shields.io/badge/Excel-217346?style=flat&logo=microsoft-excel&logoColor=white)](https://www.microsoft.com/excel)
[![Power Query](https://img.shields.io/badge/Power_Query-217346?style=flat)](https://support.microsoft.com/power-query)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat&logo=github)](https://github.com)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)

---

## 🎯 Business Problem

> *"How can Amazon optimize product assortment, pricing strategy, and marketing spend based on historical sales data?"*

This project demonstrates an end-to-end data analytics workflow: from raw data cleaning to actionable business insights and interactive visualization — all built in Microsoft Excel.

---

## 🔍 What I Built

✅ **Data Cleaning**: Processed 10,000+ rows using **Power Query** for automated, repeatable ETL  
✅ **Analysis**: Created dynamic Pivot Tables for segmentation by time, product, and region  
✅ **Visualization**: Built an interactive dashboard with **Slicers** for real-time filtering  
✅ **Insights**: Identified 3 data-driven recommendations to improve profitability  

---

## 🛠️ Tools & Skills Demonstrated

| Category                   | Tools & Skills |
|--------------------------- |---------------|
| 📊 **Data Analysis**       | Excel, Power Query, Pivot Tables, Basic DAX, GETPIVOTDATA |
| 🎨 **Data Visualization**  | Excel Charts, Conditional Formatting, Slicers, Sparklines, KPI Cards |
| 🧹 **Data Cleaning**       | Remove Duplicates, Fill Down, Merge Queries, Custom Columns, Type Conversion |
| 📈 **Business Analytics**   | KPI Calculation, Trend Analysis, Profit Margin, YoY Growth, Segmentation |
| 🔧 **Project Management**   | Git, GitHub, .gitignore, Structured Repository, Documentation |

---

## 📁 Project Structure
```
📁 dashboard-excel-amazon-sales/
│
├── 📄 README.md ← Project documentation (this file)
├── 📄 .gitignore ← Ignores Excel temporary files
├── 📄 LICENSE ← MIT License
│
├── 📁 data/
│ └── 📁 raw/
│ └── 📄 amazon_sales_raw.csv ← Original dataset (DO NOT EDIT)
│
├── 📁 excel_files/
│ ├── 📄 analysis_master.xlsx ← Full version with Power Query & all worksheets
│ └── 📄 dashboard_view.xlsx ← Lightweight version: dashboard only (for quick review)
│
├── 📁 docs/
│ ├── 📄 methodology.md ← Data cleaning & transformation steps
│ └── 📄 business_insights.md ← Detailed findings & recommendations
│
└── 📁 images/
├── 🖼️ dashboard_preview.png ← Main dashboard screenshot
└── 🖼️ data_model.png ← Table relationships diagram
```

## 🚀 How to Use

### Requirements:
- ✅ Microsoft Excel 2019 or newer / Microsoft 365
- ✅ Enable content when prompted (for full functionality)

### Quick Start:
1.  **Clone or download** the repository:
    ```bash
    git clone [https://github.com/your-username/amazon-sales-excel-dashboard.git
    ```](https://github.com/vitaliibybliukda/dashboard-excel-amazon-sales.git)

2.  **Open the file** `excel_files/dashboard_view.xlsx` in Excel

3.  **Enable data refresh**:
    - Click `Enable Editing` (if yellow bar appears)
    - Go to `Data` → `Refresh All` to update Pivot Tables

4.  **Use the Slicers** on the left to filter interactively:
    - 🗺️ **Region**: East, North, South, West
    - 📁 **Category**: Books, Electronics, Furniture, etc.
    - 📅 **Year**: 2023, 2024, 2025

5.  **Explore the dashboard**:
    - 📈 Line chart: Revenue trend over time
    - 📊 Bar charts: Top products & regional analysis
    - 💰 KPI cards: Key business metrics at a glance

---

## 💡 Key Insights

### 🔹 Insight #1: Highest-Revenue Category
      📊 Electronics generates 42% of total revenue ($1.03M)
      but has a lower profit margin (15%) compared to Books (22%)
      ✅ Recommendation: Optimize pricing strategy in Electronics
      or increase mix of high-margin products

### 🔹 Insight #2: Seasonal Sales Patterns
      📈 Peak season: Q4 (Nov-Dec) — +35% above average
      📉 Low season: Q2 (Apr-Jun) — -18% below average
      ✅ Recommendation: Launch targeted promotions in Q2
      to smooth seasonal fluctuations and improve cash flow
      
### 🔹 Insight #3: Regional Growth Opportunities
      🌍 West region shows highest YoY growth (+24%)
      but lowest repeat purchase rate (12%)


---

## 🔄 How to Refresh Data

This project uses **Power Query** for automated, repeatable data transformation.

### To connect a new dataset:
1.  Replace `data/raw/amazon_sales_raw.csv` with a new file (same column structure)
2.  Open `analysis_master.xlsx`
3.  Go to `Data` → Click `Refresh All`
4.  ✅ All Pivot Tables, charts, and the dashboard update automatically!

### To modify the cleaning logic:
1.  `Data` → `Queries & Connections`
2.  Double-click the query `Amazon_sales_raw`
3.  Edit steps in the Power Query Editor
4.  `Home` → `Close & Load`

---

## 🔮 Future Enhancements

- [ ] Add forecasting models (Excel Forecast Sheet or Python integration) for inventory planning
- [ ] Migrate to Power BI for cloud publishing and advanced interactivity
- [ ] Implement ABC analysis for product portfolio optimization
- [ ] Add dynamic pricing recommendations based on demand elasticity
- [ ] Integrate SQL queries for handling larger datasets

---

## 📚 Data Sources

- 🗂️ **Dataset**: [Kaggle: Amazon Sales Dataset](https://www.kaggle.com/datasets/your-dataset-link)
- 🔐 **Privacy**: All data is anonymized and adapted for educational purposes
- 📄 **Data License**: Public Domain / CC0

---

## 👨‍💻 About the Author

** Vitalii Bybliuk **  
🎓 Student, Correlation One × Amazon Data Analytics Program (Cohort 21)  
📧 vitaliibybliuk.da@gmail.com  
🔗 [LinkedIn](https://linkedin.com/in/vitalii-bybliuk) | [GitHub](https://github.com/vitaliibybliukda) |

> 💬 *Open to data analyst roles, internships, and collaborative projects!*

---

## 📄 License

This project is distributed under the **MIT License**.  
See the [LICENSE](LICENSE) file for details.

---

> 🚀 **Thank you for checking out my project!**  
> If you found this useful, feel free to ⭐ star the repository or reach out with feedback.  
> Let's connect and build something amazing together!   
