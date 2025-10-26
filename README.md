# Amazon Sales Data Analysis

![Python](https://img.shields.io/badge/Python-3.12-blue.svg)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-orange.svg)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-green.svg)

A comprehensive statistical analysis of Amazon sales data exploring pricing strategies, discount patterns, and customer ratings. This project demonstrates data cleaning, exploratory data analysis, and statistical modeling techniques.

## 📊 Project Overview

This project analyzes 1,464 Amazon products to uncover relationships between pricing, discounts, and customer satisfaction. The analysis provides data-driven insights for e-commerce businesses to optimize their pricing and promotion strategies.

### Key Findings
- **Budget products** (<₹500) achieve higher customer satisfaction
- **Optimal discount range** is 30-50% for maximum rating impact
- **Weak correlation** (0.120) between price and rating
- **Electronics category** dominates product offerings (526 products)
- **423 high-value products** identified with ratings ≥4.0 and prices ≤₹500

## 🛠️ Technologies Used

- **Python 3.12**
- **Data Analysis:** pandas, numpy
- **Visualization:** matplotlib, seaborn, plotly
- **Statistical Analysis:** scipy, scikit-learn
- **Version Control:** Git

## 📁 Project Structure
amazon-analysis/
├── Amazon_Sales_Data_Analysis.py # Main analysis script
├── amazon.csv # Raw dataset
└── README.md # Project documentation
📈 Analysis Features
Data Cleaning & Preprocessing
Currency symbol removal and data type conversion

Missing value handling and outlier detection

Feature engineering for price categories and rating segments

Exploratory Data Analysis
Price distribution analysis

Rating pattern visualization

Discount effectiveness studies

Category performance comparison

Statistical Analysis
Correlation matrix and heatmap visualization

Four statistical moments calculation (mean, variance, skewness, kurtosis)

Hypothesis testing and significance analysis

Visualization Types
Relational Plots: Scatter plots (Price vs Rating)

Categorical Plots: Histograms, bar charts, box plots

Statistical Plots: Correlation heatmaps, distribution charts

📋 Key Results
Statistical Insights
Metric	Value	Insight
Avg Price	₹3,126.01	Right-skewed distribution
Avg Rating	4.10/5.00	Positive customer sentiment
Avg Discount	47.71%	High promotional activity
Price-Rating Correlation	0.120	Weak positive relationship
Business Recommendations
Focus on Budget Segment (₹300-600 range)

Maintain 30-50% Discounts for optimal performance

Expand Electronics & Office Products categories

Emphasize Quality over price positioning
