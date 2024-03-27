# Forcasting Net Profit
## Find Unusual Patterns in Hourly Google Search Traffic
Read the search data into a DataFrame.

Sliced the data to include only the month of May 2020.

Calculated the total search traffic for the month and compared it to the monthly median across all months.

Analyzed whether the Google search traffic increased during the month when MercadoLibre released its financial results.

## Mine the Search Traffic Data for Seasonality
Grouped the hourly search data to plot the average traffic by the hour of the day.

Grouped the hourly search data to plot the average traffic by the day of the week (e.g., Monday vs. Friday).

Grouped the hourly search data to plot the average traffic by the week of the year.

Identified any time-based trends or seasonality in the data.

## Relate the Search Traffic to Stock Price Patterns
Read in and plotted the stock price data.

Concatenated the stock price data with the search data in a single DataFrame.

Sliced the data to include only the first half of 2020 (January to June) and plotted the combined data.

Created a new column named "Lagged Search Trends" to shift the search traffic by one hour.

Created additional columns for "Stock Volatility" and "Hourly Stock Return" to analyze relationships between search trends, stock volatility, and stock price returns.

Investigated if a predictable relationship exists between lagged search traffic and stock volatility or stock price returns.

## Create a Time Series Model with Prophet
Set up the Google search data for a Prophet forecasting model.

Estimated the model and plotted the forecast.

Plotted the individual time series components of the model.

Answered questions about the popularity of different times of the day, the day of the week with the most search traffic, and identified the lowest point for search traffic in the calendar year.

## Findings
Overall, the analysis covered examining unusual patterns, identifying seasonality, exploring relationships between search traffic and stock price patterns, and creating a time series forecasting model using Prophet to gain insights into hourly Google search traffic data.






