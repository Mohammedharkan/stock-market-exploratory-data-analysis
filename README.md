# 📈 Stock Market Exploratory Data Analysis (1970–2018)

## Project Overview

This project performs a complete Exploratory Data Analysis (EDA) on historical stock market data from 1970 to 2018. The objective is to understand long-term stock price behavior, trading activity, and market trends by applying data cleaning, statistical analysis, and visualization techniques.

The analysis follows a structured EDA workflow beginning with data preparation and ending with business insights and future research hypotheses.

---

## Dataset

The project uses two datasets:

- **historical_stock_prices.csv**
  - Daily stock prices
  - Open
  - High
  - Low
  - Close
  - Adjusted Close
  - Volume
  - Date

- **historical_stocks.csv**
  - Company ticker
  - Company name
  - Exchange
  - Sector
  - Industry

---

## Project Workflow

1. Data Collection
2. Data Understanding
3. Data Cleaning
4. Data Segmentation by Decade
5. Dataset Merging
6. Exploratory Data Analysis (EDA)
7. Comparative Analysis
8. Final Conclusions
9. Future Hypotheses

---

## Data Cleaning

The following preprocessing steps were completed:

- Checked missing values
- Replaced missing Sector and Industry values with **"Unknown"**
- Removed duplicate records
- Converted the Date column to datetime format
- Set Date as the DataFrame index
- Prepared the dataset for time-series analysis

---

## Exploratory Data Analysis

The analysis includes:

### Summary Statistics

Calculated for:

- Open
- High
- Low
- Close
- Volume

Statistics include:

- Mean
- Median
- Standard Deviation

---

### Time Series Analysis

Monthly average closing prices were calculated and visualized for:

- 1970s
- 1980s
- 1990s
- 2000s
- 2010s

---

### Trading Volume Analysis

Histogram visualizations were created to analyze trading volume distributions across decades.

---

### Price Distribution Analysis

Box plots were created for High and Low prices to examine:

- Price spread
- Market variability
- Outliers

---

## Key Findings

- Historical stock prices changed considerably across different decades.
- Later decades generally exhibited higher market volatility.
- Trading volume increased substantially over time.
- Price distributions contained numerous outliers.
- Statistical summaries and visualizations consistently supported the same conclusions.

---

## Future Hypotheses

Possible future research includes:

- Comparing stock performance across sectors.
- Investigating the relationship between trading volume and volatility.
- Studying seasonal effects on stock prices.
- Developing machine learning models for stock price prediction.
- Comparing industry performance over time.

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook
- VS Code

---

## Repository Structure

```
stock-market-eda-1970-2018/

│
├── data/
│   ├── raw/
│   └── processed/
│
├── images/
│
├── notebooks/
│   └── Stock_Market_EDA_1970_2018.ipynb
│
├── reports/
│   └── Data Collection and Initial Analysis of Stock Market Data.pdf
│
├── README.md
│
└── requirements.txt
```

---

## Results

The project successfully demonstrates a complete exploratory data analysis workflow for historical financial data. The findings provide meaningful insights into stock market behavior across multiple decades and establish a strong foundation for future predictive analytics and machine learning applications.

---

## Author

**Mohammed Harkan**

Business Intelligence Analyst Student

GitHub:

https://github.com/Mohammedharkan