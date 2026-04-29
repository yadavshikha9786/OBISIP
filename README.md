# OBISIP
# 🛍️ Retail Sales - Exploratory Data Analysis (EDA)

## 📌 Project Overview
This project performs a complete Exploratory Data Analysis (EDA) 
on a Retail Sales Dataset containing 1000 transactions. 
The goal is to uncover patterns, trends, and insights 
from the data using Python.

## 📂 Dataset Information
- **File:** retail_sales_dataset.csv
- **Rows:** 1000
- **Columns:** 9

| Column | Description |
|---|---|
| Transaction ID | Unique ID for each sale |
| Date | Date of transaction |
| Customer ID | Unique customer identifier |
| Gender | Male / Female |
| Age | Customer age |
| Product Category | Beauty, Clothing, Electronics |
| Quantity | Number of items purchased |
| Price per Unit | Price of one item |
| Total Amount | Total sale value |

## 🛠️ Tools & Libraries Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## 📊 Analysis Performed

### 1. Data Cleaning
- Converted Date column to datetime format
- Cleaned Product Category column
- Checked for null values and duplicates

### 2. Univariate Analysis
- Product Category Distribution
- Gender Distribution
- Age Distribution
- Total Amount Distribution
- Quantity Distribution

### 3. Bivariate Analysis
- Age vs Total Amount
- Gender vs Total Amount
- Revenue by Product Category

### 4. Multivariate Analysis
- Pairplot of numeric variables
- Correlation Heatmap

### 5. Additional Analysis
- Outlier Detection using IQR Method
- Monthly Sales Trend (Time-based Analysis)
- Skewness Check

## 🔍 Key Findings
- All 3 product categories are equally distributed (~33% each)
- Dataset is gender balanced (51% Female, 49% Male)
- Total Amount is right-skewed — most transactions are low value
- Price per Unit has HIGH correlation with Total Amount
- No statistical outliers found in the dataset
- Sales fluctuate monthly with no strong seasonal pattern

## 👩‍💻 Author
**Shikha Yadav**
- GitHub: yadavshikha9786
- Internship: OIBSIP (Oasis Infobyte)
