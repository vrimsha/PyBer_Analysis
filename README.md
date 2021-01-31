# PyBer_Analysis
## Overview of the analysis: Explain the purpose of the new analysis.

The main task is to prepare a summary DataFrame of the ride-sharing data by city type. There are 3 city types: urban, suburban and rural. Then, create a multiple-line graph that shows the total weekly fares for each city type. 

## Results:  
### 1. Loading and Reading CSV files. 
There were two csv files loaded in Resources folder: city_data and ride_data.

### 2. Merge the DataFrames.

Combine the data into a single dataset. Merge ride_data_df and city_data_df into pyber_data_df.

![Combine_the_data](Combine_the_data.png)

### 3. Get a Summary DataFrame.

I found the total number of rides, total number of drivers, and the total fares for each city type. 

Please see below:

Total number of rides:

![total_rides](total_rides.png)

Total number of drivers:

![total_drivers](total_drivers.png)

Total amount of fares for each city type:

![total_amount_fares](total_amount_fares.png)

Then, I calculated the average fare per ride and per driver for each city type. 

The average fare per ride:

![average_fare_per_ride](average_fare_per_ride.png)

The average fare per driver:

![average_fare_per_driver](average_fare_per_driver.png)

PyBer summary DataFrame:

![pyber_sum_fares_week](pyber_sum_fares_week.png)

![summary01](summary01.png)

The differences in ride-sharing data among the different city types:

Rural city type had the highest average per ride $34.62 and the highest average fare per driver $55.49 compare with other city types. It had only 78 drivers with 125 rides. That is why this city type had the lowest total fares amount $4,327.93. These fares amount 4.5 times less than in Suburban city type and 9.2 times less than in Urban city type. The most successful week was in April.

Suburban city type had more drivers and rides than in Rural, 490 drivers with 625 rides. Average fare per ride was $30.97, which is less by $3.65 compare to Rural city type and more by $6.44 than in Urban city type. The average fare per driver was $39.50. The most successful month was February.

Urban had the most successful data results. It had the largest number of drivers 2,405 with total rides 1,625. It is the largest market with the lowest average fare per ride $24.53 and average per driver $16.57. It had high peak season in February and March.

![analysis/PyBer_fare_summary](PyBer_fare_summary.png)


## Summary: Based on the results, provide three business recommendations to the CEO for addressing any disparities among the city types.

There is a statement summarizing three business recommendations to the CEO for addressing any disparities among the city types. (4 pt)