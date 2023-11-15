# Module_challenge_11
## Step 1: Data Exploration and Visualization

The search data was read into a DataFrame, and the data for the month of May 2020 was sliced and visualized using hvPlot. No unusual patterns were observed at this stage.
The total search traffic for May 2020 was calculated, and it was compared to the monthly median across all months. The analysis indicated whether Google Search traffic increased during the month MercadoLibre released its financial results.

## Step 2: Mining Search Traffic Data for Seasonality
The hourly search data was grouped to plot the average traffic by the day of the week, helping identify any day-of-week effects. A heatmap was created using hvPlot to visualize the traffic patterns by hour and day of the week.
Additionally, the search data was grouped by the week of the year to determine if search traffic tends to increase during the winter holiday period (Weeks 40 through 52).

## Step 3: Analyzing Stock Price Data
The stock price data was read in and plotted. Both the search and stock price data were concatenated into a single DataFrame. The data for the first half of 2020 (January to June) was sliced and visualized using hvPlot to identify common trends.

## Step 4: Time Series Analysis
Several new columns were created in the DataFrame, including "Lagged Search Trends," which shifted the search traffic by one hour, "Stock Volatility," which held a four-hour rolling average of stock volatility, and "Hourly Stock Return," which calculated the percentage change in stock price on an hourly basis.
Time series correlations were reviewed to identify relationships between lagged search traffic and stock volatility or stock price returns.

## Step 5 (Optional): Forecasting Sales Revenue
Daily historical sales (revenue) figures were read in, and a Prophet model was applied to the data. Seasonal patterns in the company's revenue were identified, including peak revenue days.
A sales forecast for the finance group was produced, providing expected total sales for the next quarter. Best-case, worst-case, and most likely scenarios were included to assist in planning and decision-making.
These steps represent the past activities conducted to analyze search traffic, stock prices, and revenue data, providing valuable insights and forecasts for MercadoLibre.
