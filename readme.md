# Weather Data Visualizer

Mini project for **Programming for Problem Solving using Python**.  
This project analyzes real-world weather data from a CSV file and visualizes temperature, rainfall, and humidity using Python, Pandas, NumPy, and Matplotlib.

## Dataset

- Source: Open weather dataset (e.g., Delhi daily climate time series from Kaggle or similar open data portal).
- Format: CSV file with columns such as date, temperature, rainfall, humidity.
- Files:
  - data/raw_weather.csv – original downloaded data.
  - data/cleaned_weather.csv – cleaned data after processing in Python.

## Tools and Libraries

- Python 3
- Pandas – data loading and cleaning.
- NumPy – numerical statistics (mean, min, max, standard deviation).
- Matplotlib – plotting line, bar, scatter, and combined charts.

## Features / Tasks

- Load weather CSV into a Pandas DataFrame.
- Clean data (handle missing values, convert date column to datetime, select key columns).
- Calculate daily, monthly, and yearly statistics using NumPy and groupby.
- Create:
  - Line chart for daily temperature trends.
  - Bar chart for monthly rainfall totals.
  - Scatter plot of humidity vs temperature.
  - Combined figure with multiple subplots.
- Group data by month/season and export summary CSV.
- Save all plots as PNG images in the images/ folder.
- Generate a short report with insights in report.md.

1. Install dependencies:
