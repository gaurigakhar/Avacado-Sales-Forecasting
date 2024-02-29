## Dataset
The dataset contains information about the number of bags of Avocados sold on a daily basis, broken down by bag size and type (conventional or organic). The data is collected from different locations across the United States. The variable of interest is the number of bags sold. The length of the data is more than 30K, and it covers a period of 6 years.

Specifically, the dataset contains the following columns:
- date: The date on which the bags were sol average_price: The average price of a bag sold on that date.
- total_volume: The total volume of bags sold on that date.
- total_bags: The total number of bags sold on that date.
- small_bag: The percentage of bags sold that were small.
- large_bags: The percentage of bags sold that were large.
- xlarge_baş: The percentage of bags sold that were extra large.
- type: The type of bag sold (conventional or organic).
- year: The year in which the bags were sold.
- geography: The geographic location where the bags were sold.

The dataset is useful for understanding the trends in bag sales over time, and for comparing sales across different locations and types of bags

## Optimal Model
Holt-Winters method, also known as triple exponential smoothing (TES), was used as the optimal model to forecast the values for the next 2 weeks based on several factors:

First, Data characteristics:
- Trend: The dataset exhibits a clear trend of increasing sales over time.
- Seasonality: The data also shows evidence of seasonality, with fluctuations in sales volume likely related to specific periods or events

Second, Model capabilities:
- TES is specifically designed for time series data with both trend and seasonality.
- TES is flexible and can be adapted to handle different types of seasonality (additive or multiplicative).
- TES has been shown to be effective in forecasting a wide range of time series data, including sales data. 
