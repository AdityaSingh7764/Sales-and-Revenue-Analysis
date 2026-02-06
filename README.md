# Sales and Revenue Analysis

A comprehensive data analysis project focused on analyzing sales and revenue patterns for a computer hardware business facing challenges in a dynamically changing market. This project demonstrates end-to-end data analysis capabilities, from data cleaning to interactive dashboard creation.

## 📊 Project Overview

This project provides real-time sales insights through Power BI dashboards, enabling data-driven decision-making for business stakeholders. The analysis covers customer behavior, market trends, product performance, and revenue patterns across multiple dimensions.

## 🎯 Objectives

- Build interactive Power BI dashboards for real-time sales insights
- Analyze sales trends across different markets, customers, and products
- Identify revenue patterns and growth opportunities
- Enable data-driven decision-making for business stakeholders
- Clean and transform raw data into actionable insights

## 📁 Project Structure

```
Sales-and-Revenue-Analysis/
├── Cleaned_Dataset.xlsx          # Processed and cleaned data ready for analysis
├── Uncleaned_Dataset.xlsx        # Raw data before cleaning
├── Sales_Dash.pbit               # Power BI dashboard template
├── Sales_and_Revenue_Analysis_Report.docx  # Detailed analysis report
└── README.md                     # Project documentation
```

## 📈 Dataset Description

The project uses a multi-dimensional dataset containing 150,000+ transaction records with the following components:

### Data Tables

1. **Customers Table** (39 records)
   - `customer_code` - Unique customer identifier
   - `customer_name` - Customer business name
   - `customer_type` - Classification (Brick & Mortar, E-Commerce)

2. **Dates Table** (1,127 records)
   - `date` - Transaction date
   - `cy_date` - Calendar year date
   - `year` - Year value
   - `month_name` - Month name
   - `yy_mmm` - Year-Month format

3. **Markets Table** (16 records)
   - `markets_code` - Market identifier
   - `markets_name` - Market/City name
   - `zone` - Geographic zone classification

4. **Products Table** (280 records)
   - `product_code` - Product identifier
   - `product_type` - Product category/type

5. **Transactions Table** (150,284 records)
   - `product_code` - Product identifier
   - `customer_code` - Customer identifier
   - `market_code` - Market identifier
   - `order_date` - Transaction date
   - `sales_qty` - Quantity sold
   - `sales_amount` - Revenue generated
   - `currency` - Transaction currency

## 🔧 Data Cleaning Process

The data cleaning process involved:

- **Header Standardization**: Fixed spelling and formatting inconsistencies
- **Data Type Validation**: Ensured appropriate data types for each column
- **Duplicate Removal**: Identified and removed duplicate market entries (reduced from 18 to 16 records)
- **Missing Value Handling**: Addressed null values and incomplete records
- **Data Consistency**: Standardized formats across all tables
- **Relationship Validation**: Verified foreign key relationships between tables

## 📊 Key Features

- **Multi-dimensional Analysis**: Customer, Product, Market, and Time-based insights
- **Interactive Dashboards**: Dynamic Power BI visualizations
- **Trend Analysis**: Historical sales patterns and forecasting
- **Performance Metrics**: Revenue, quantity, and growth indicators
- **Geographic Insights**: Zone-wise and market-wise performance analysis

## 🛠️ Tools & Technologies

- **Microsoft Excel**: Initial data cleaning and transformation
- **Power BI**: Dashboard creation and visualization
- **SQL**: Original data source (imported to Excel)
- **Power Query**: Advanced data transformation

## 📌 Key Insights

The analysis enables stakeholders to:
- Identify top-performing customers, products, and markets
- Track sales trends over time
- Compare performance across different zones
- Analyze customer type preferences (Brick & Mortar vs E-Commerce)
- Make informed inventory and marketing decisions

## 🚀 Getting Started

### Prerequisites
- Microsoft Excel (2016 or later)
- Power BI Desktop (latest version)

### Usage

1. **View Cleaned Data**:
   - Open `Cleaned_Dataset.xlsx` to explore the processed data
   - Review individual sheets for different data dimensions

2. **Explore Dashboard**:
   - Open `Sales_Dash.pbit` in Power BI Desktop
   - Connect to the cleaned dataset when prompted
   - Interact with visualizations to gain insights

3. **Review Analysis**:
   - Open `Sales_and_Revenue_Analysis_Report.docx` for detailed findings
   - Understand the data cleaning methodology and business insights

## 📝 Analysis Report

The comprehensive analysis report includes:
- Data cleaning methodology
- Detailed table descriptions
- Business insights and recommendations
- Visualization strategies
- Performance metrics

## 🤝 Contributing

Contributions, issues, and feature requests are welcome! Feel free to check the issues page or submit a pull request.

## 📧 Contact

**Aditya Singh**
- GitHub: [@AdityaSingh7764](https://github.com/AdityaSingh7764)

## 📄 License

This project is available for educational and analytical purposes.

---

⭐ If you found this project helpful, please consider giving it a star!
