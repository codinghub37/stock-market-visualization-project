# Finance Data Analysis Using Python

## Overview

This project performs Exploratory Data Analysis (EDA) on historical stock market data of major U.S. banking institutions. The objective is to analyze stock performance, identify trends, measure risk, and visualize relationships between different banking stocks using Python.

The project utilizes financial data from Yahoo Finance and applies various data analysis and visualization techniques to gain insights into stock market behavior over time.

---

## Dataset

Historical stock data was collected from Yahoo Finance for the following banks:

* Bank of America (BAC)
* Citigroup (C)
* Goldman Sachs (GS)
* JPMorgan Chase (JPM)
* Morgan Stanley (MS)
* Wells Fargo (WFC)

### Data Features

Each stock dataset contains:

* Open Price
* High Price
* Low Price
* Close Price
* Adjusted Close Price
* Trading Volume

### Time Period

2006 – 2016

---

## Technologies Used

* Python
* Jupyter Notebook
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Yahoo Finance (yfinance)

---

## Code Implementation

The project follows a structured data analysis workflow:

### 1. Data Collection

Financial data for multiple bank stocks was imported using Yahoo Finance and combined into a single dataset for analysis.

### 2. Data Preprocessing

* Organized stock data using Pandas DataFrames
* Created multi-level column structures
* Inspected and prepared data for analysis

### 3. Exploratory Data Analysis

Performed several analytical operations including:

* Maximum closing price analysis
* Daily return calculations
* Risk and volatility assessment
* Correlation analysis
* Performance comparison between banks

### 4. Data Visualization

Created visual representations of financial data using Matplotlib and Seaborn.

---

## Analysis Performed

### Maximum Closing Price Analysis

Identified the highest closing price achieved by each bank stock during the selected time period.

### Daily Return Analysis

Calculated daily percentage changes in stock prices to evaluate stock performance and volatility.

### Stock Performance Comparison

Compared the overall performance of different banking stocks over time.

### Correlation Analysis

Analyzed relationships between stocks to determine how closely their movements were related.

### Financial Crisis Analysis

Examined stock behavior during the 2008 financial crisis and observed the impact on banking institutions.

### Moving Average Analysis

Applied moving averages to smooth short-term fluctuations and highlight long-term market trends.

### Risk Analysis

Evaluated stock risk by analyzing daily returns and volatility measurements.

---

## Visualizations Generated

The project includes multiple visualizations such as:

* Closing Price Trend Charts
* Daily Return Histograms
* Distribution Plots
* Pair Plots
* Correlation Heatmaps
* Cluster Maps
* Moving Average Graphs

These visualizations help identify patterns, trends, and relationships within financial data.

---

## Key Insights

* Banking stocks experienced significant volatility during the 2008 financial crisis.
* Different banks showed varying levels of risk and return.
* Several banking stocks demonstrated strong positive correlations.
* Long-term trends became more visible through moving average analysis.
* Data visualization provided valuable insights into stock market behavior.

---

## Skills Demonstrated

* Data Analysis
* Exploratory Data Analysis (EDA)
* Financial Data Analysis
* Data Cleaning
* Statistical Analysis
* Data Visualization
* Python Programming
* Pandas & NumPy
* Matplotlib & Seaborn

## Requirements

```text
pandas
numpy
matplotlib
seaborn
yfinance
jupyter
```

