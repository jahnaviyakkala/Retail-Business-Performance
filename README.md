# Retail Business Performance & Profitability Analysis

##  Project Overview
This project analyzes retail transactional sales data to evaluate business performance, identify profit-draining categories, analyze inventory efficiency, and understand seasonal profitability trends.  
The goal is to demonstrate how data-driven analysis can support better inventory planning and profitability optimization in retail businesses.

---

##  Objectives
- Analyze sales and profit performance across product categories
- Identify low-margin and profit-draining categories
- Study the relationship between inventory quantity and profit
- Analyze seasonal trends in profitability
- Build an interactive dashboard for business decision-making

---

##  Dataset
- **Source:** Sample Superstore retail dataset
- **Granularity:** Order-level transactional data
- **Key Columns:**
  - Order Date  
  - Category  
  - Sub-Category  
  - Sales  
  - Profit  
  - Quantity  
  - Region  

Raw data was cleaned and transformed before analysis.

---

##  Tools & Technologies
- **SQL (SQLite):** Data cleaning, transformation, and aggregation  
- **Python (Pandas):** Inventory vs profit analysis and trend analysis  
- **Power BI:** Interactive dashboard and KPI visualization  

---

## Data Processing Pipeline
1. Imported raw CSV data into SQLite
2. Cleaned data by removing null and invalid records
3. Created a structured analytical dataset
4. Performed profitability and inventory analysis
5. Visualized insights using Power BI dashboard

---

##  Key Analyses Performed

### Sales & Profit Analysis
- Compared total sales and profit across categories
- Identified categories with high sales but low profitability

### Profit Margin Analysis
- Calculated profit margin to measure efficiency
- Identified Furniture as a low-margin category
- Office Supplies showed highest profit efficiency

### Inventory Analysis
- Analyzed relationship between inventory quantity and profit
- Found weak correlation, indicating overstocking risk

### Seasonal Analysis
- Analyzed monthly profit trends
- Observed seasonal fluctuations affecting profitability

---

##  Power BI Dashboard
The Power BI dashboard includes:
- Total Sales, Total Profit, and Profit Margin KPIs
- Category-wise sales and profit comparison
- Profit margin analysis
- Inventory Quantity vs Profit analysis
- Monthly profit trend (seasonality)
- Interactive filters for region, category, and time

---

##  Key Insights
- High sales do not always result in high profit
- Furniture category underperforms in profit margin
- Office Supplies is the most efficient category
- Increasing inventory quantity does not guarantee higher profit
- Seasonal trends significantly impact profitability

---

##  Business Recommendations
- Optimize inventory levels for low-margin categories
- Focus on high-margin and efficient product categories
- Implement seasonal inventory planning strategies
- Track profit efficiency instead of sales volume alone

---

##  Repository Structure
├── Sample - Superstore.csv # Raw dataset
├── retail_clean.csv # Cleaned dataset
├── retail_final.csv # Final dataset for analysis
├── retail.sql # SQL queries
├── retailsales.py # Python analysis script
├── retail.pbix # Power BI dashboard
├── RETAIL BUSINESS PERFORMANCE.pdf # Final project report
└── README.md # Project documentation
