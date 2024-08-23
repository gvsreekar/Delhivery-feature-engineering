# Delhivery-feature-engineering

## Business Statement:
The company wants to understand and process the data coming out of data engineering pipelines.Clean, sanitize and manipulate data to get useful features out of raw fields.Make sense out of the raw data and help the data science team to build forecasting models on it.

## Problem Statement:
* Indian states with source and destination delivery count
    * Destination state with delivery count
    * Source state with delivery count
* Analaysing through destination places in each state Which place have more delivery ?
* Analaysing through source places in each state Which place have more delivery?
* Analaysing through cities in each state Which city have more delivery ?
* Which month proceed more trip?
* Which route type use more time to reach destination?
* Which state has more source center?
* Which state has more destination center?
* Weekday with most delivery of the product
* Actual time v/s Time which computes the shortest path
* Feature engineering
    * Calculate the time taken between od_start_time and od_end_time as time_difference
* Hypothesis
    * Compare the difference between time_difference and start_scan_to_end_scan.
    * Actual_time aggregated value and OSRM time aggregated value
    * Actual_time aggregated value and segment actual time aggregated value
    * Osrm distance aggregated value and segment osrm distance aggregated value
    * Osrm time aggregated value and segment osrm time aggregated value
* Find outliers in the numerical variables and check it using visual analysis
* One-hot encoding of categorical variables
* Normalize/ Standardize the numerical features using MinMaxScaler or StandardScaler
