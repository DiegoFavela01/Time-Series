# Time-Series
## Challenge 11 - University of Berkeley Financial Technology Boot Camp 


### Step 1: Find Unusual Patterns in Hourly Google Search Traffic
- Read the search data into a DataFrame and extract the data for the month of May 2020.
- Visualize the search traffic using hvPlot and identify any unusual patterns.
- Calculate the total search traffic for the month and compare it to the monthly median across all months.
### Step 2: Mine the Search Traffic Data for Seasonality
- Group the hourly search data by the day of the week and plot the average traffic.
- Visualize the traffic patterns as a heatmap to identify any concentration of traffic during specific hours of certain days.
- Group the search data by the week of the year and check if the search traffic tends to increase during the winter holiday period.
### Step 3: Relate the Search Traffic to Stock Price Patterns
- Read and plot the stock price data.
- Concatenate the stock price data with the search data in a single DataFrame.
- Analyze both time series data for common trends in the first half of 2020.
- Create additional columns to compare lagged search traffic with stock volatility and hourly stock returns.
- Review the time series correlation to identify any predictable relationships.
### Step 4: Create a Time Series Model with Prophet
- Prepare the Google search data for a Prophet forecasting model.
- Estimate the model and plot the forecast for near-term popularity.
- Analyze the individual time series components of the model to determine the most popular time of day, the day with the highest search traffic, and the lowest point of search traffic in the calendar year.
## Libraries and Dependencies
This code uses the following libraries:
- Pandas
- hvPlot
- Prophet

## Files
- The necessary files for this "google_hourly_search_trends.csv"  "mercado_daily_revenue.csv" "mercado_stock_price.csv" in the Resources
