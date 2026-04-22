# 🛒 Retail Sales Data Analysis

<p align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white" />
  <img src="https://img.shields.io/badge/Excel-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white" />
  <img src="https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black" />
  <img src="https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white" />
  <img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white" />
  <img src="https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white" />
  <img src="https://img.shields.io/badge/Matplotlib-11557C?style=for-the-badge&logo=plotly&logoColor=white" />
</p>

<h1 align="center">Retail Sales Data Analysis</h1>
<p align="center">
  End-to-end data analysis project using Excel, Python, SQL, and Power BI
</p>

---

## 📌 Project Overview
The **Retail Sales Data Analysis** project is designed to analyze retail transaction data and generate meaningful business insights.  
This project covers the complete workflow from data cleaning and preprocessing to SQL analysis and dashboard creation.  
The aim is to understand sales trends, customer behavior, product performance, and revenue patterns for better business decision-making.

---

## 📑 Table of Contents
- Project Overview
- Objectives
- Tools and Technologies
- Dataset
- Project Architecture
- Project Workflow
- Project Structure
- Installation
- Analysis Performed
- Key Insights
- Dashboard Preview
- Project Outcome
- Future Enhancements
- About Me
- Contact

---

## 🎯 Objectives
- Analyze retail sales performance across categories and locations
- Identify top-selling products and customer purchase behavior
- Track monthly and yearly sales trends
- Measure the effect of discounts on sales
- Perform SQL-based business analysis
- Build an interactive Power BI dashboard
- Present insights in a professional and structured format

---

## 🛠️ Tools and Technologies

### Languages and Libraries
- Python
- SQL
- Pandas
- NumPy
- Matplotlib

### Platforms and Tools
- Jupyter Notebook
- MySQL
- Microsoft Excel
- Power BI

### Tools and Technologies Icons
<p>
  <img src="https://skillicons.dev/icons?i=python,mysql" />
</p>
<p>
  <img src="https://img.shields.io/badge/Excel-217346?style=flat-square&logo=microsoft-excel&logoColor=white" />
  <img src="https://img.shields.io/badge/Power%20BI-F2C811?style=flat-square&logo=powerbi&logoColor=black" />
  <img src="https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white" />
  <img src="https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white" />
  <img src="https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white" />
  <img src="https://img.shields.io/badge/Matplotlib-11557C?style=flat-square&logo=plotly&logoColor=white" />
</p>

---

## 📂 Dataset
The dataset contains retail transaction records with fields such as:

- Transaction ID
- Customer ID
- Product ID
- Product Category
- Product Name
- Quantity
- Price Per Unit
- Discount
- Total Amount
- Payment Method
- Store Location
- Transaction Date

### Dataset Purpose
This dataset is used to:
- Analyze revenue and sales distribution
- Compare category and product performance
- Study customer buying patterns
- Create visual reports and dashboards

---

## 🏗️ Project Architecture

Retail Sales Data Analysis Architecture

Raw Retail Dataset  
        ↓  
Data Cleaning and Preprocessing  
(Python / Excel)  
        ↓  
Exploratory Data Analysis  
(Python)  
        ↓  
Business Query Analysis  
(MySQL / SQL)  
        ↓  
Dashboard and Visual Reporting  
(Power BI)  
        ↓  
Insights and Conclusions  

---

## 🔄 Project Workflow

### 1. Data Collection
- Collected retail sales dataset from available data source
- Checked columns, data types, and overall quality

### 2. Data Cleaning
- Removed duplicate records
- Handled missing values
- Standardized column names
- Converted date columns into proper format
- Created derived columns such as Month, Year, and Month-Year

### 3. Data Preprocessing
- Verified numeric columns
- Formatted transaction values
- Organized data for SQL and dashboard usage

### 4. Data Analysis
- Performed category-wise sales analysis
- Calculated total revenue and quantity sold
- Identified top-performing products
- Analyzed customer and location-based patterns
- Evaluated discount impact on sales

### 5. Data Visualization
- Built charts using Python
- Created dashboard visuals in Power BI
- Presented insights using graphs and KPI cards

---

## 📁 Project Structure

retail-sales-data-analysis/  
│  
├── README.md                              # Project documentation  
├── requirements.txt                       # Python dependencies  
├── main.py                                # Main execution file  
│  
├── data/                                  # Dataset folder  
│   ├── raw/  
│   │   └── retail_sales_data.xlsx         # Original dataset  
│   └── processed/  
│       └── cleaned_retail_data.xlsx       # Cleaned dataset  
│  
├── notebooks/                             # Jupyter notebooks  
│   └── retail_sales_analysis.ipynb        # Analysis notebook  
│  
├── sql/                                   # SQL scripts  
│   └── retail_sales_queries.sql           # SQL analysis queries  
│  
├── src/                                   # Python source files  
│   ├── __init__.py  
│   ├── data_cleaning.py                   # Data cleaning functions  
│   ├── preprocessing.py                   # Data preprocessing logic  
│   ├── analysis.py                        # Analysis functions  
│   └── visualization.py                   # Plot generation code  
│  
├── dashboard/                             # Power BI dashboard  
│   └── retail_sales_dashboard.pbix        # Power BI file  
│  
├── outputs/                               # Generated charts and outputs  
│   ├── monthly_sales_trend.png  
│   ├── category_sales_analysis.png  
│   ├── top_products.png  
│   └── payment_method_distribution.png  
│  
└── images/                                # Project screenshots  
    └── dashboard_preview.png              # Dashboard image  

---

## ⚙️ Installation

### Clone the repository
git clone https://github.com/yourusername/Retail-Sales-Data-Analysis.git

### Move into the project folder
cd Retail-Sales-Data-Analysis

### Install required Python libraries
pip install pandas numpy matplotlib openpyxl

### Launch Jupyter Notebook
jupyter notebook

---

## 📊 Analysis Performed
- Total sales and revenue calculation
- Category-wise sales comparison
- Top products identification
- Monthly sales trend analysis
- Payment method analysis
- Regional sales comparison
- Discount effect analysis
- Customer purchasing pattern analysis

---

## 💡 Key Insights
- Some product categories contributed more strongly to revenue than others
- Monthly trend analysis showed clear peak sales periods
- A small number of products generated a major share of revenue
- Discounts influenced purchase quantity in several cases
- Location-wise comparison helped identify stronger sales regions
- Customer transaction behavior showed repeat purchasing patterns

---



## 🚀 Project Outcome
This project helped in developing practical skills in:
- Data cleaning and preprocessing
- SQL query writing
- Exploratory data analysis using Python
- Dashboard design in Power BI
- Business insight generation from raw retail data

This project also demonstrates the ability to complete an end-to-end data analysis workflow using multiple tools in a professional manner.

---

## 🔮 Future Enhancements
- Add predictive analysis for future sales forecasting
- Build automated reporting pipeline
- Add advanced KPI calculations
- Perform customer segmentation analysis
- Publish dashboard online
- Integrate machine learning-based sales prediction

---



