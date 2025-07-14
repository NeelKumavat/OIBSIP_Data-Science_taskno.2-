# OIBSIP_Data-Science_taskno.2
 Unemployment Analysis with Python

Objective
The objective of this project is to analyze the unemployment trends in India, particularly during and after the COVID-19 pandemic, using available data.
This includes:

Region-wise and time-wise unemployment rate trends.

Urban vs rural comparisons.

Forecasting future unemployment rates using machine learning.

Datasets Used
Unemployment in India.csv

Contains unemployment statistics by state, date, area (urban/rural), etc.

Unemployment_Rate_upto_11_2020.csv

Monthly unemployment data across Indian states up to November 2020.

Tools and Technologies Used
Python

Pandas – Data loading and cleaning

Matplotlib & Seaborn – Data visualization

Prophet (by Facebook) – Time series forecasting

Google Colab – Cloud-based Jupyter notebook environment

Steps Performed
Data Loading & Preprocessing
Loaded both CSV files using pandas.

Cleaned column names and converted date columns to datetime objects.

Checked for and handled missing values.

Exploratory Data Analysis (EDA)
Line plots to show unemployment trends over time (national and state level).

Bar plots showing unemployment rate by state for the latest available month.

Boxplots comparing unemployment in urban vs rural areas.

Correlation heatmap for employment-related metrics.

Forecasting (Predictive Analysis)
Aggregated India-level average unemployment rate over time.

Used Facebook Prophet to predict unemployment for the next 6 months.

Visualized the predicted unemployment trend with confidence intervals.

Visualizations Included
Unemployment rate over time (line graph)

Unemployment rate by state (bar graph)

Urban vs Rural unemployment (boxplot)

Unemployment forecast using Prophet (time series plot)

Correlation heatmap

Outcome
Observed a sharp rise in unemployment during COVID-19 lockdown months (April–June 2020).

Identified regional differences in unemployment (some states significantly worse).

Urban areas showed higher variation in unemployment rates than rural.

Prophet-based forecasting gave a reasonable estimate of future unemployment trends.

File Structure

Unemployment in India.csv                 # Dataset 1
Unemployment_Rate_upto_11_2020.csv       # Dataset 2
unemployment_analysis_forecast.ipynb     # Main analysis and forecasting notebook



