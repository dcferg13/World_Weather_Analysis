# World_Weather_Analysis
World weather analysis for vacation destinations. That include hotel names and current weather descriptions.
## Overview of Analysis
The purpose of this technical analysis is to update the PlanMyTrip app to incorporate a weather description to the weather data. Next was to create a list of potential vacation destinations and choose four destinations and create a vacation itinerary.
### Retrieve Weather Data
In the first technical analysis I generated a set of 2,000-random latitudes and longitudes, find the nearest city, and use API to gather information from the OpenWeatherMap. We needed to find the name of the city, the country it is in, the maximum temperature, humidity, cloudiness, wind speed and the current weather description of the city. Then take all this information and put it into a new dataframe and create a csv file.
![cities_weather_list](https://user-images.githubusercontent.com/107289345/181651915-57f527ae-f5ae-42de-8941-38cb8a9e7e10.png)

### Create a Customer Travel Destinations Map
The second technical analysis was to create a customer travel destination map. We created a map that shows the destinations with pop-up markers, which include the name of the hotel, city, and current weather. To find these travel destinations, the customers were asked weather preferences. The next step was to find cities with the customers preference that had hotels. We took the list of cities from the dataframe created in the first technical analysis and searched for hotels. If there was no hotel found, we skipped to the next city. The list of cities that have compatible weather and hotels was made into new dataframe.

##### WeatherPy_vacation_map
![WeatherPy_vacation_map](https://user-images.githubusercontent.com/107289345/181651968-c16e1bf3-0da0-4020-98f8-fd909c56624e.png)

### Create a Travel Itinerary Map
Finally, in the third technical analysis was to create a travel itinerary map. I created the map from the list of cities that was compiled in the second technical analysis. I chose four cities in Mexico that a customer might want to visit. The first map, WeatherPy_travel_map has directions layer for driving. The map shows Ixtapa as the start and end of the trip, with stops in El Colomo, Lazaro Cardenas, and Acapulco. The second map WeatherPy_travel_map_markers have the four cities with markers that show the hotel name, city, country, and current weather.

##### WeatherPy_travel_map
![WeatherPy_travel_map](https://user-images.githubusercontent.com/107289345/181652060-69f05aa3-5e67-4428-a5d2-44cd06370588.png)

##### WeatherPy_travel_map_markers
![WeatherPy_travel_map_markers](https://user-images.githubusercontent.com/107289345/181652074-eaf1f667-008c-47ac-9df3-892a122dde40.png)

