# World_Weather_Analysis

## Overview
Using the Multiple API Keys (open weather API, Google Map API) to create the best travel plan to travel plan app that base on weather preference and the distance bewteen travel destinations and nearby hotels.

## Process
### Weather Database
Using the open weather API to retrieve the weather data to build on the travel plan app.Therefore, users can make their plan base on the location, weather temperature range etc. We need to collection all the information from many cities in the world.Create the random list of 2000 latitudes and longtitudes coordinates and use citpy to locate the nearby cities, then use those data to build up the DataFrame. Also we save the weather data as CSV file that can as city DataFrame
Please see the picture for loop throught the data from open weather API from each city.
![weather_Data](https://github.com/JoJofia/World_Weather_Analysis/blob/2c50dcd1e6e646cf4c7535a9a2331bd3d5a8b7a3/Weather_Database/Weather_Database.png)

### Vacation Search
Try to create a customer travel destination map, we retrieve the date from weather database csv file and set up the minimum and maximum temperature criteria for customers to choose the weather range that they want.
![WeatherPy vacation map](https://github.com/JoJofia/World_Weather_Analysis/blob/2c50dcd1e6e646cf4c7535a9a2331bd3d5a8b7a3/Vacation_Search/WeatherPy_vacation_map.png)

**juypter widget error not show up the map


### Vacation ltinerary
Create the driving route map for user base on using Google Directions API. In the map will showing the city markers for user ltinerary. And also the city marker for each city will show the weather description, maxmium temperture for each location.
![weather travel map](https://github.com/JoJofia/World_Weather_Analysis/blob/2c50dcd1e6e646cf4c7535a9a2331bd3d5a8b7a3/Vacation_Itinerary/WeatherPy_travel_map.png)
1[weather travel map markers](https://github.com/JoJofia/World_Weather_Analysis/blob/2c50dcd1e6e646cf4c7535a9a2331bd3d5a8b7a3/Vacation_Itinerary/WeatherPy_travel_map_markers.png)

**juypter widget error not show up the map
