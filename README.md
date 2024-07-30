# prophet-challenge
## Overview
This project aims to analyze the financial and user data of Mercado Libre, the most popular e-commerce site in Latin America, to understand if predicting search traffic can translate into successful stock trading strategies. The analysis is divided into four steps: identifying unusual patterns in search traffic, mining search traffic data for seasonality, relating search traffic to stock price patterns, and creating a time series model using Prophet.

## Instructions
### Step 1: Find Unusual Patterns in Hourly Google Search Traffic
Objective: Identify any unusual patterns in the Google search traffic data for Mercado Libre and connect them to corporate financial events.

Read the search data into a DataFrame and slice the data to the month of May 2020.
Visualize the results to detect unusual patterns.
Calculate the total search traffic for May 2020 and compare it to the monthly median across all months.
Determine if the Google search traffic increased during the release of Mercado Libre's quarterly financial results.
Output: A visualization and analysis of search traffic for May 2020.

### Step 2: Mine the Search Traffic Data for Seasonality
Objective: Mine the search traffic data to find predictable seasonal patterns that can help in focusing marketing efforts for better ROI.

Group the hourly search data to plot the average traffic by the hour of the day.
Group the hourly search data to plot the average traffic by the day of the week.
Group the hourly search data to plot the average traffic by the week of the year.
Analyze any time-based trends in the data.
Output: Visualizations showing the average search traffic by hour, day, and week.

### Step 3: Relate the Search Traffic to Stock Price Patterns
Objective: Investigate the relationship between search traffic data and Mercado Libre's stock price.

Read in and plot the stock price data, then concatenate it with the search data.
Slice the data to the first half of 2020 and plot the combined data to identify common trends.
Create new columns for “Lagged Search Trends”, “Stock Volatility”, and “Hourly Stock Return”.
Analyze the relationship between lagged search traffic and stock volatility/returns.
Output: Visualizations and analysis showing the relationship between search traffic and stock price.

### Step 4: Create a Time Series Model with Prophet
Objective: Produce a time series model to analyze and forecast patterns in the hourly search data.

Prepare the Google search data for a Prophet forecasting model.
Estimate the model and plot the forecast.
Plot the individual time series components to analyze the popularity trends by time of day, day of the week, and the lowest point of search traffic in the year.
Output: Forecast plots and analysis of time series components.