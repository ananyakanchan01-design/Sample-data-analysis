# End-to-End Data Analysis Case Study

## Project Overview

This project demonstrates a complete data analysis workflow using Python, Excel, and Tableau. The objective was to clean and analyze a business sales dataset, create interactive dashboards, and generate meaningful business insights that support data-driven decision-making.

---

## Dataset

**Dataset:** Financial Sample

The dataset contains sales transactions with information about:

* Segment
* Country
* Product
* Discount Band
* Units Sold
* Manufacturing Price
* Sale Price
* Gross Sales
* Discounts
* Sales
* COGS
* Profit
* Date
* Month Number
* Month Name
* Year

---

## Tools Used

* **Google Colab** – Data cleaning and exploratory data analysis using Python
* **Python Libraries**

  * Pandas
  * NumPy
  * Matplotlib
* **Microsoft Excel**

  * Pivot Tables
  * Pivot Charts
  * KPI Cards
  * Slicers
* **Tableau Public**

  * Interactive Dashboard
  * Filters
  * Calculated Fields
* **GitHub** – Project version control and submission

---

## Python (Google Colab)

The dataset was imported into Google Colab for preprocessing and exploratory data analysis.

### Data Cleaning

The following cleaning operations were performed:

* Imported the Excel dataset
* Examined dataset structure
* Checked column data types
* Identified and handled missing values
* Removed duplicate records
* Converted date columns into datetime format
* Generated descriptive statistics
* Detected outliers using boxplots
* Removed outliers using the IQR (Interquartile Range) method
* Exported the cleaned dataset as **Cleaned_Data.xlsx**

### Exploratory Data Analysis

The analysis included:

* Dataset overview
* Summary statistics
* Missing value analysis
* Duplicate record analysis
* Unique value analysis
* Sales distribution
* Profit distribution
* Outlier detection

Visualizations created in Python included:

* Boxplots
* Histograms
* Bar Charts
* Line Charts

---

## Microsoft Excel Dashboard

An interactive Excel dashboard was created using Pivot Tables and Pivot Charts.

### KPI Cards

The dashboard displays:

* Total Sales
* Total Profit
* Total Units Sold
* Total Gross Sales

### Pivot Tables

The following Pivot Tables were created:

1. Sales by Country
2. Profit by Product
3. Monthly Sales Trend
4. Sales by Segment

### Charts

The dashboard includes:

* Clustered Bar Chart
* Clustered Column Chart
* Line Chart
* Pie Chart

### Interactive Features

Slicers were added for:

* Country
* Product
* Segment
* Discount Band

These slicers allow users to filter all Pivot Tables and charts dynamically.

---

## Tableau Dashboard

An interactive Tableau dashboard was developed to visualize business performance.

### Dashboard Components

* Sales by Country
* Profit by Product
* Monthly Sales Trend
* Sales by Segment

### Interactive Features

Filters included:

* Country
* Product
* Segment
* Discount Band
* Year

### Calculated Fields

Calculated fields created include:

* Profit Margin
* Average Sales

These calculations provide additional business insights into profitability and sales performance.

---

## Key Business Insights

* Sales vary significantly across countries, indicating regional performance differences.
* Certain products generate substantially higher profits than others.
* Monthly sales exhibit seasonal trends.
* Customer segments contribute differently to total revenue.
* Discount strategies have a measurable impact on profitability.

---

## Recommendations

* Increase focus on high-performing countries through targeted marketing.
* Promote products with higher profit margins.
* Optimize discount strategies to maximize profitability.
* Prepare inventory ahead of peak sales periods.
* Develop customer-specific marketing campaigns based on segment performance.

---

## Project Files

```
End-to-End-Data-Analysis/
│
├── Cleaned_Data.xlsx
├── End_to_End_Data_Analysis.ipynb
├── project.twb
├── README.md
└── Final_Report.docx
```

---

## Outcome

This project demonstrates practical skills in:

* Data Cleaning
* Exploratory Data Analysis (EDA)
* Data Visualization
* Dashboard Development
* Business Intelligence
* Business Storytelling
* Data-Driven Decision Making

The combination of Python, Excel, and Tableau provides a complete end-to-end analytics solution that transforms raw business data into meaningful insights and actionable recommendations.
