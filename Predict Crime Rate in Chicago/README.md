# 📊 Predict Crime Rate in Chicago
This project analyzes and forecasts crime rates in Chicago using historical crime data from 2005 to 2017. The goal is to explore patterns in crime trends and apply time series forecasting techniques to predict future crime rates.

# 📁 Project Overview
The notebook performs the following steps:

- Loads crime data from three separate CSV files covering different time ranges.

- Merges the datasets into a single DataFrame for unified analysis.

- Performs data cleaning by removing irrelevant columns and converting date columns into proper datetime objects.

- Visualizes missing data using a heatmap to assess data completeness.

- Prepares the data for time series forecasting.

- Applies the Prophet library for crime trend forecasting (time series modeling).

# 📦 Libraries Used
- pandas — Data manipulation and analysis

- numpy — Numerical operations

- matplotlib — Data visualization

- seaborn — Statistical data visualization

- random — Random number generation (for sampling or auxiliary tasks)

- fbprophet — Time series forecasting

# 📂 Data Sources
- Chicago_Crimes_2005_to_2007.csv

- Chicago_Crimes_2008_to_2011.csv

- Chicago_Crimes_2012_to_2017.csv

Each CSV contains detailed records of crimes reported in Chicago, including dates, types, locations, and arrest records.

📈 Purpose
- To build a simple, end-to-end time series forecasting workflow:

- Understand crime trends over time.

- Clean and prepare multi-year data.

- Forecast future crime activity to inform safety strategies and urban planning.
