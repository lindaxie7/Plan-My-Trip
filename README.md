# WeatherPy

## Overview of Project

We have the PlanMyTrip app, there are a few recommendeded changes to take the app to the next level. We want to adding the weather description to the weather data frame, then use input statements to filter the data for the user's weather preferences, which will be used to identify potential travel destinations and nearby hotels. From the list of potential travel destinations, we want to choose four cities to create a travel itinerary, and then using the Google Maps Directions API, create a travel route between the four cities as well as a marker layer map.


## Results

First, I generated a set of 2,000 random latitudes and longitudes, retrieve the nearest city, and perform an API call with the OpenWeatherMap. In addition to the city weather data Frame, I use API to retrieve the current weather description for each city and then create a new DataFrame containing the updated weather data. 

![Untitled](https://user-images.githubusercontent.com/38533045/129505378-1310b384-c4b9-4bae-ab9f-be1bea70a27b.png)


Then, I use input statements to retrieve customer weather preferences, then use those preferences to identify potential travel destinations and nearby hotels. Then, show those destinations on a marker layer map with pop-up markers. The WeatherPy_vacation_map look like below: 
![WeatherPy_vacation_map](https://user-images.githubusercontent.com/38533045/129505449-3a389e9d-4ade-402e-acf7-345038a59020.png)


At the end, I use the Google Directions API to create a travel itinerary that shows the route between four cities chosen from the customer’s possible travel destinations. Then, create a marker layer map with a pop-up marker for each city on the itinerary. The WeatherPy_travel_map and the WeatherPy_travel_map_markers look like below:

![WeatherPy_travel_map](https://user-images.githubusercontent.com/38533045/129505489-6326d566-3572-4dc0-9b08-657c4c344cb5.png)


![WeatherPy_travel_map_markers](https://user-images.githubusercontent.com/38533045/129505560-330b0342-9811-4084-b7c4-efd824ff44f3.png)






