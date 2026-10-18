# ShopSmart Retail Data Analysis

## Analytics Lab Africa Internship Project

### Project Overview

This project focuses on Exploratory Data Analysis (EDA) of ShopSmart retail data to understand sales performance, customer behaviour, product performance, returns, and inventory management.

The goal is to transform raw retail data into meaningful insights that can support better business decisions, improve operational efficiency, and identify opportunities for growth.

The project was completed using Python and popular data analysis libraries as part of the Analytics Lab Africa internship.

## Objectives

The main objectives of this project are to:

- Inspect and understand the available retail datasets.
- Clean missing values, duplicate records, and inconsistent data.
- Explore sales trends across products, categories, stores, and locations.
- Analyze customer demographics and customer segments.
- Examine product pricing and revenue contribution.
- Investigate returns and inventory levels.
- Visualize important patterns and relationships.
- Provide practical business insights and recommendations.

## Datasets

The project contains nine main CSV datasets:

| Dataset | Description |
|---|---|
| Customers | Customer demographics, locations, and segments |
| Products | Product categories, brands, and pricing |
| Orders | Sales transactions, quantities, discounts, and payment methods |
| Stores | Store locations, regions, and opening dates |
| Returns | Return dates, reasons, and refund amounts |
| Employees | Employee roles, store assignments, and salaries |
| Suppliers | Supplier information and locations |
| Inventory | Stock levels, reorder points, and restocking dates |
| Order Items | Individual items within orders and line totals |

A separate data dictionary is also available to help explain the dataset fields.

## Tools and Technologies

The project uses the following tools and libraries:

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Missingno
- Jupyter Notebook

## Project Structure

```text
Week1_DataScience_Project/
├── Week1_EDA.ipynb
├── Cleaned_Data/
├── Visualizations/
├── cleaning_log.csv
├── data_quality_report.csv
├── EDA_Report.pdf
├── requirements.txt
└── README.md
```

Note: The report, notebook, and visualization files should be present in the project folder when the project is finalized. The PDF report and presentation may be added when available.

## Data Cleaning

The data preparation process includes:

1. Removing duplicate rows.
2. Standardizing column names.
3. Cleaning text values and missing-value markers.
4. Converting numeric columns to appropriate data types.
5. Converting date columns to datetime format.
6. Checking missing values and invalid dates.
7. Reviewing duplicate identifiers and negative numeric values.
8. Saving cleaned datasets and data quality reports.

Missing values and unusual records are reviewed carefully because not every missing or negative value necessarily represents an error.

## Exploratory Data Analysis

The analysis focuses on:

- Monthly sales trends.
- Revenue by product category and store.
- Top- and low-revenue products.
- Customer age distribution and segmentation.
- Product selling-price distribution.
- Return-rate analysis.
- Inventory levels and reorder requirements.
- Correlations between selected numerical variables.

## Key Findings

The available correlation analysis identified:

- A positive correlation of **0.73** between unit price and calculated revenue.
- A positive correlation of **0.60** between quantity and calculated revenue.

These relationships require careful interpretation because unit price and quantity are components of the revenue calculation. Correlation does not establish causation.

Exact sales totals, leading products, top-performing stores, and peak sales periods should be confirmed from the final cleaned datasets and notebook outputs.

## Business Recommendations

Based on the project's analytical scope, the following actions are recommended:

- Monitor monthly sales performance to identify changes in demand.
- Evaluate products using profit margins as well as revenue.
- Review stock levels against reorder points to reduce stockouts.
- Investigate common return reasons to identify opportunities for improvement.
- Use customer segmentation to support more targeted marketing.
- Maintain consistent data relationships across orders, products, stores, and inventory.

## Installation and Usage

### 1. Clone the repository

If the project has been uploaded to GitHub:

```bash
git clone YOUR_GITHUB_REPOSITORY_URL
```

Replace the placeholder with your actual repository URL.

### 2. Navigate to the project directory

```bash
cd Week1_DataScience_Project
```

### 3. Install the dependencies

```bash
pip install -r requirements.txt
```

### 4. Open the notebook

```bash
jupyter notebook
```

Open `Week1_EDA.ipynb` and run the cells in order.

Make sure the notebook's file paths match the location of the original and cleaned datasets.

## Limitations

- Supplier-level sales attribution requires a reliable product-to-supplier mapping.
- Product-level return analysis may be limited when return records identify orders rather than individual products.
- Revenue calculations depend on the correct interpretation of the discount field.
- Final business conclusions should be supported by verified metrics and visualizations.

## Conclusion

This project demonstrates how Python can be used to clean, explore, and interpret retail data. It provides a foundation for identifying business patterns, improving data quality, and making more informed decisions.

The project also strengthens practical skills in data preparation, exploratory analysis, visualization, and communicating findings to a business audience.

## Author

**Abdulhaq Ibrahim Abubakar**

Data Science and Machine Learning Learning Engineer(In Learning)

Analytics Lab Africa Internship Project

