# 🌦️ Weather Data Analysis Using Python

## 📌 Project Overview

This project analyzes historical weather data using Python, Pandas, NumPy, and Matplotlib.

The analysis focuses on understanding temperature, humidity, and precipitation patterns through data cleaning, statistical analysis, monthly and seasonal analysis, and visualization.

## 🎯 Objectives

- Load and inspect weather data using Pandas
- Handle missing values and convert date data
- Calculate descriptive statistics using NumPy
- Analyze monthly and seasonal weather patterns
- Create visualizations using Matplotlib
- Identify extreme temperature and precipitation days

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Google Colab
- Jupyter Notebook

## 📊 Analysis Performed

### Data Cleaning
- Checked for missing values
- Filled missing numerical values using column means
- Converted the Date column to datetime format

### Descriptive Statistics
Calculated:
- Mean
- Median
- Standard deviation

for:
- Temperature
- Humidity
- Precipitation

### Monthly and Seasonal Analysis
- Grouped weather data by month
- Calculated monthly average temperature, humidity, and precipitation
- Created seasonal categories: Winter, Spring, Summer, and Autumn
- Compared average weather metrics across seasons

### Visualizations
Created:
- 📈 Line plot — Average Temperature by Month
- 📊 Bar plot — Average Precipitation by Month
- 📉 Histogram — Temperature Distribution

### Extreme Weather Analysis
Used NumPy-based filtering to identify:
- Extreme temperature days
- Extreme precipitation days

## 📁 Project Files

| File | Description |
|---|---|
| [Weather_Data_Analysis.ipynb](./Weather_Data_Analysis.ipynb) | Complete analysis notebook |
| [weather_data_analysis.csv](./weather_data_analysis.csv) | Weather dataset used for analysis |

## 📈 Dataset

The dataset contains daily weather observations for 2025 with the following columns:

- `Date`
- `Temperature`
- `Humidity`
- `Precipitation`

The dataset contains 365 daily records.

## 🔍 Key Results

- Average Temperature: **25.07**
- Average Humidity: **64.80**
- Average Precipitation: **4.79**
- Extreme Temperature Days: **5**
- Extreme Precipitation Days: **13**

## 👨‍💻 Author

**Chandan Kumar Chauhan**
