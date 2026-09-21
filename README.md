# Online Retail Data Cleaning & Visualization

## Project Overview

This project focuses on cleaning, analyzing, and visualizing an Online Retail transactional dataset using Python.

The project demonstrates a complete data analysis workflow, including data inspection, missing value handling, duplicate removal, invalid transaction filtering, outlier analysis, feature engineering, exploratory data analysis, and visualization.

## Objectives

- Understand the structure and characteristics of the raw dataset.
- Identify and handle missing values.
- Detect and remove duplicate records.
- Identify and handle invalid transactions.
- Detect potential outliers using the IQR method.
- Create useful features for analysis.
- Analyze sales trends and product performance.
- Create meaningful visualizations.
- Generate insights from the cleaned dataset.

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook / Google Colab

## Dataset

The project uses the **Online Retail Dataset**, which contains transactional information from a UK-based online retailer.

The dataset includes information such as:

- Invoice Number
- Stock Code
- Product Description
- Quantity
- Invoice Date
- Unit Price
- Customer ID
- Country

## Data Cleaning

The following data cleaning operations were performed:

1. Inspected the dataset structure and data types.
2. Identified missing values.
3. Removed records with missing product descriptions.
4. Checked and removed duplicate records.
5. Identified invalid transactions with non-positive quantities or prices.
6. Created a valid sales dataset by filtering invalid transactions.
7. Converted the invoice date into datetime format.
8. Created additional date-based features.
9. Calculated total sales for each transaction.
10. Identified potential outliers using the Interquartile Range (IQR) method.

## Exploratory Data Analysis

The analysis includes:

- Overall revenue analysis
- Transaction analysis
- Product performance analysis
- Country-wise revenue analysis
- Monthly revenue trends
- Monthly transaction trends
- Day-of-week purchasing patterns
- Quantity distribution
- Revenue distribution
- Correlation analysis

## Visualizations

The project contains visualizations such as:

- Monthly Revenue Trend
- Top 10 Products by Revenue
- Top 10 Countries by Revenue
- Revenue by Day of Week
- Quantity Distribution
- Unit Price Distribution
- Correlation Heatmap
- Top Products by Quantity

## Key Insights

The analysis provides insights into:

- Changes in revenue over time.
- Products contributing significantly to overall revenue.
- Countries generating the highest revenue.
- Differences in purchasing activity across days of the week.
- Distribution and extreme values of quantities and prices.
- Relationships between numerical variables.

## Project Structure

```text
Online-Retail-Data-Cleaning-Visualization/
│
├── Online_Retail_Data_Cleaning_Visualization.ipynb
├── README.md
└── visualizations/
