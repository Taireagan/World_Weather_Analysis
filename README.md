# World Weather Analysis

## Project Overview
In this analysis, we will utilize API calls to examine weather patterns across various cities worldwide, spanning different distances from the equator. The project is structured into two primary deliverables.

First, we aim to analyze how weather conditions change as one approaches the equator. This will involve gathering and analyzing data on temperature, humidity, wind speed, and other relevant weather metrics to identify trends and correlations with geographical latitude.

Second, based on our findings, we will apply the insights gained to plan future vacations, optimizing for favorable weather conditions. This data-driven approach will allow us to make informed decisions regarding the best times and locations for travel, enhancing our vacation planning with precise and reliable weather forecasts.

By leveraging comprehensive data collection and rigorous analysis, we aim to provide valuable insights into global weather patterns and their practical applications for travel planning.   

## Deliverable #1
Leverage the OpenWeatherMap API to retrieve weather data for a predefined list of cities and perform a comprehensive analysis of weather patterns relative to geographic latitude and create a series of scatter plots showcasing the following relationships:
- Latitude vs. Temperature
- Latitude vs. Humidity
- Latitude vs. Cloudiness 
- Latitude vs. Wind Speed

Then conduct linear regression analysis separately for cities in the Northern and Southern Hemispheres to identify trends and correlations. The analysis will be represented through the following scatter plots:

**Northern Hemishpere**
- Temperature vs. Latitude
- Humidity vs. Latitude
- Cloudiness vs. Latitude
- Wind Speed vs. Latitude

  **Southern Hemishpere**
- Temperature vs. Latitude
- Humidity vs. Latitude
- Cloudiness vs. Latitude
- Wind Speed vs. Latitude


## Deliverable #2
In this section, we will utilize the Geoapify API along with the GeoViews Python library to create detailed map visualizations. The visualizations will feature the following:

- Each city from the city_data_df DataFrame will be represented as a point on the map.
- The size of each point will correspond to the humidity percentage in each city, providing a clear visual representation of humidity distribution across different geographic locations.

## Map 1
These maps will offer an intuitive way to understand the spatial patterns of humidity and will serve as a valuable tool for further analysis and presentation of our findings.

![cityhumidityheatmap](https://github.com/Taireagan/World_Weather_Analysis/assets/170124537/09c651b1-e7bd-4f4f-8602-02fa6d3dc253)


## Map 2
The following section highlights several cities with optimal weather conditions for potential travel destinations.


![hotellocation](https://github.com/Taireagan/World_Weather_Analysis/assets/170124537/6ea30228-8d7e-461e-8b96-417e92efbd41)
