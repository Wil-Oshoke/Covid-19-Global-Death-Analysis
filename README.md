Global COVID-19 Death Data Analysis
This project analyzes the global COVID-19 death data to visualize trends and identify top countries by total deaths. The analysis provides insights into the progression of COVID-19 fatalities over time and highlights the countries most impacted by the pandemic.

Features
1. Time Series Analysis: Total Global Deaths Over Time
This section of the analysis visualizes the cumulative global COVID-19 death toll, enabling a clear view of the pandemic's trajectory. It includes:
Data preprocessing and formatting for time series analysis.
A line plot shows total global deaths from January 2020 onward, with dates on the x-axis and total deaths (formatted with commas for readability) on the y-axis.

2. Bar Chart: Top 10 Countries by Total Deaths
This part of the analysis identifies the top 10 countries with the highest total COVID-19 deaths, excluding global totals:
Data is filtered to remove the global total row, focusing solely on country-level data.
A horizontal bar chart displays the top 10 countries' death tolls and is annotated for clarity on each bar.

Setup
Libraries Used: pandas for data manipulation, and matplotlib for plotting.
Ensure the dataset, aggregated_data is pre-processed with relevant columns (e.g., 'Total Deaths') and indexed by 'Country/Region' for the code to function correctly.

Visualizations
Line Plot: Provides a temporal view of global deaths.
Bar Chart: Highlights countries with the highest death tolls.

Usage
You can just run the Python script to generate the visualizations. Each plot provides insights into the global impact of COVID-19 and allows for comparative analysis across countries.

This project is open for contributions. For any questions or suggestions, please raise an issue or contact the author, Wil Oshoke.
