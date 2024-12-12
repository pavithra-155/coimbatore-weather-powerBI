# Coimbatore Weather Forecast - 33 Years Data
 # Project Overview
This project visualizes and analyzes weather data for Coimbatore, India, over the past 33 years. The primary goal is to explore weather patterns, including wind speed, wind gusts, temperature, humidity, and rainfall to understand the trends and make predictions.

The project uses Power BI for creating interactive dashboards that allow users to explore weather data, focusing on wind dynamics, temperature variations, and rainfall patterns in Coimbatore.

# Data Source
The data used in this project is sourced from an Excel file and OpenWeather API (for recent data), containing weather information for Coimbatore for the last 33 years. The dataset includes the following key parameters:

Date (Year and Month)
Max Temperature (°C)
Min Temperature (°C)
Average Temperature (°C)
Wind Speed (m/s or km/h)
Wind Gusts (m/s or km/h)
Rainfall (mm)
Humidity (%)

# Excel File Structure:
The Excel file consists of the following columns:

Year: The year of the weather data entry.
Month: The month of the weather data entry.
Max Temperature (°C): The maximum temperature recorded in the given month.
Min Temperature (°C): The minimum temperature recorded in the given month.
Wind Speed (km/h): The average wind speed for the month.
Wind Gusts (km/h): The highest recorded wind gusts for the month.
Rainfall (mm): The total rainfall for the month.
Humidity (%): The average humidity for the month.
# Key Features
Wind Speed & Gusts Analysis: Provides a detailed view of wind speed and gusts over the past 33 years and identifies seasonal trends.
Temperature Trends: Visualizes changes in max, min, and average temperatures across the years.
Seasonal Impact: Understands how seasonal changes (monsoon, summer, winter) affect wind speeds, gusts, and rainfall.
Rainfall & Wind Correlation: Compares wind gusts and rainfall to analyze the impact of storms and rain events.
# Key Visualizations
Line Graphs: Display wind speed and gusts trends over the years.
Bar Charts: Compare monthly averages for temperature, wind speed, and rainfall.
Heatmap: Shows seasonal variations in wind speed and gusts.
Scatter Plots: Analyzes the relationship between wind speed and rainfall for different seasons.
# Insights
Wind Speed & Gusts: Wind speeds and gusts show distinct seasonal variations, with higher gusts occurring during the monsoon and pre-monsoon periods.
Temperature Patterns: A steady rise in average temperatures is observed over the years, especially during the dry season.
Rainfall Patterns: Rainfall intensity increases during the monsoon, affecting both wind speed and temperature fluctuations.
How to Use
Download and open the Coimbatore_Weather_33_Years.pbix file in Power BI Desktop.
Use the slicers to filter data by year, month, or weather condition (e.g., high wind speed).
Hover over any chart or graph for detailed tooltips and insights.
Interact with the visualizations to explore trends in temperature, wind speed, and rainfall for Coimbatore.
# Dependencies
Power BI Desktop: Version 2.87.1711.1081 or later.
Weather Data Excel File: Ensure the Coimbatore_Weather_33_Years.xlsx file is available for use.
API Integration: For real-time data, ensure the OpenWeather API integration is working for current weather conditions.
Challenges Faced
Missing Data: Some entries in the dataset lacked wind speed and gust information, requiring data cleaning and interpolation.
Data Consistency: Ensuring consistency in wind speed units (m/s vs km/h) across different datasets and years.
Historical Data Gaps: Some years had incomplete data, which required estimation and data aggregation to maintain accuracy.
# Future Enhancements
Predictive Analysis: Incorporate time-series forecasting to predict future weather patterns based on historical data.
Geospatial Data: Use maps to visualize wind patterns and other weather-related data across different regions of Coimbatore.
Real-Time Integration: Include real-time weather data (e.g., from OpenWeather API) to compare it with historical trends.
# License
This project is open-source and available under the MIT License.
