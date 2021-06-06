# Vacation Planner

## Overview of Project

This analysis uses consumer input on weather preferences to provide possible vacation destinations. Using some of these possible locations, hotel information, weather information, and driving directions will be displayed on a map.


## Results
In the example script, the weather preferences were narrowed to show possible vacation destinations with temperatures between 75 and 85. After choosing a starting and ending destination of Progreso, Mexico, directions were planned on a map for 3 nearby destination cities in Mexico (shown below)
![Alt Text](https://github.com/lyanneagger/World_Weather_Analysis/blob/main/Vacation_Itinerary/WeatherPy_travel_map.png)</br>

Another map was also given with informational markers giving the city, hotel name, and current weather description of each stop on the trip (shown below).
![Alt Text](https://github.com/lyanneagger/World_Weather_Analysis/blob/main/Vacation_Itinerary/WeatherPy_travel_map_markers.png)</br>

## Summary
The script generated 2000 random latitudes and longitudes, which returned 762 cities. Filtering out missing weather data, missing hotel information, and weather preferences narrowed that down to 167 cities, so finding 4 cities in the same country proved to be difficult, only offering a few options through the US, Mexico, Australia, and China. While it would take a bit longer to run, expanding the original city list would produce more options for a trip with multiple stops within the same area.
