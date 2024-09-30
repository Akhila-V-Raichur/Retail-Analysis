
# Retail Analysis 

## Overview
This project focuses on performing exploratory data analysis (EDA) on a retail dataset to understand customer purchasing behavior, sales trends, and product performance. The analysis involves data cleaning, exploration, and visualization of key statistics like total sales, customer purchase patterns, and product varieties. By leveraging the Pandas library for data manipulation and Matplotlib/Seaborn for visualization, this project provides insights into sales performance across various dimensions.

## Dataset
The dataset used in this project is sourced from publicly available retail data repositories. It includes various features such as:

- **Customer ID**
- **Invoice Date**
- **Stock Code**
- **Description**
- **Quantity**
- **Price**
- **Country**

The dataset can be downloaded from https://www.kaggle.com/datasets/lakshmi25npathi/online-retail-dataset
## Usage
1. Download the dataset and place it in the project folder.
2. Open and run the Jupyter Notebook `Retail Analysis.ipynb`.
3. The notebook will perform data cleaning, analysis, and visualization.

## Data Cleaning
The data cleaning steps involve:
- Handling missing or NaN values in the dataset.
- Dropping irrelevant or redundant columns.
- Converting date formats to ensure compatibility with time-series analysis.
- Aggregating data at customer or product levels for comprehensive analysis.

## Data Analysis
Key analyses performed include:
- Customer purchase behavior analysis.
- Sales trend analysis over different time periods.
- Identification of top-selling products based on quantity and revenue.
- Investigation of price vs. quantity relationship.
- Country-wise sales distribution analysis.
- Invoice-level analysis to understand average transaction sizes.
- Product category analysis based on descriptions.

## Data Visualization
Visualizations are created using Matplotlib and Seaborn to present the data insights:
- Bar charts and histograms to show total quantity or total sales per customer.
- Line plots to display sales trends over time.
- Scatter plots for price vs. quantity analysis.
- Pie charts or bar charts for sales distribution by country.
- Box plots for transaction sizes per invoice.

## Results
The analysis highlights the following key findings:
- Identification of customer purchasing patterns and preferences.
- Trends in sales over time, revealing peak purchasing periods.
- Insights into top-performing products and their sales figures.
- Understanding of country-wise performance in sales and customer engagement.
