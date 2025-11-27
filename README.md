Trader behavior changes across fear and greed periods.

Project Overview
This project analyzes the relationship between Bitcoin market sentiment (Fear and Greed Index) and trader performance using historical transaction data from HyperLiquid. The goal is to study how market sentiment affects trading activity, trade size, and trader behavior.

ds_harshada/
│
├── sentiment_trader_analysis.ipynb       # Main analysis notebook
├── linear_regression.ipynb               # Optional model notebook
│
├── data/
│   ├── fear_greed_index.csv
│   └── trader_data.csv
│
├── outputs/
│   ├── plot1
│   ├── plot2
│   
└── README.md

Objective

Clean and prepare the sentiment and trader datasets.
Merge both datasets based on timestamp.
Analyze trader performance under different sentiment conditions.
Build simple prediction models to explore patterns.

Datasets Used

1. Bitcoin Market Sentiment Dataset
2. HyperLiquid Trader Data

Technologies Used

Python
Pandas
NumPy
Matplotlib
Seaborn
Scikit-learn
Google Colab

Key Steps

Data Cleaning
Removed missing values, standardized dates, and formatted numerical fields.

Data Merging
Combined trader data with sentiment data based on matching dates.

Exploratory Data Analysis
Analyzed sentiment distribution, trade volume patterns, correlations, and trends.

Modeling
Used Linear Regression to study how sentiment influences trade size or trade count.

Visualization
Created time-series plots, bar charts, histograms, and volume comparison graphs.

Results Summary

Trader behavior changes across fear and greed periods.

Trade size and total volume vary with sentiment.

Author

Harshada Bidaye

Data Science intern and  Student
