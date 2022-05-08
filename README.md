# Wold Weather Analysis

## Overview
The objective of this analysis was to create a map of vacation data that let Jack and beta testers for the PlanMyTrip app filter the collected information to their weather preferences, which was then used to identify potential travel destinations and nearby hotels.

## Summary
I generated a set of 2000 random latitudes and longitudes, retrieving the nearest cities and performing an API call with the OpenWeatherMap. Current weather descriptions for each city were gathered and a DataFrame containing the data was created.

![City Data Dataframe](https://github.com/jstearns1988/Wold_Weather_Analysis/blob/main/City%20Data%20Dataframe.png)

Next input statements were used to collect customer weather preferences, then those preferences identified the above mentioned travel destinations and nearby hotels. A marker layer map with pop-up markers was created.

An intinerary travel map was created by using Google Directions API that showed the route between four cities in the Phillipines: Cavite, Morong, Talipan, Gigmoto, and Cavite. I started with a dataframe of all the cities and included the max temp, current weather description, latitude, longitude, and hotel name.

![Itinerary Travel Map](https://github.com/jstearns1988/Wold_Weather_Analysis/blob/main/Vacation_Itinerary/WeatherPy_travel_map.png)

Finally, this dataframe was used to create the marker layer map with a pop-up marker for each city. 

![Marker Layer Map](https://github.com/jstearns1988/Wold_Weather_Analysis/blob/main/Vacation_Itinerary/WeatherPy_travel_map_markers.png)

## Results
Due to the layout of the pop-up markers, some of the city data is obstructed by the other markers in the provided screenshot. The following lists out all of the information gathered for each city marker:

#### Cavite
Hotel Name - One Serenata Hotel
Country - PH
Current Weather - few clouds and 84.29 °F

#### Morong
Hotel Name - Clarita De Luisa
Country - PH
Current Weather: broken clouds and 84.22 °F

#### Talipan
Hotel Name - Silangang Nayon Park and Restaurant
Country - PH
Current Weather - scattered clouds and 82.15 °F

#### Gigmoto
Hotel Name - Cj's Travellers Inn
Country - PH
Current Weather - overcast clouds and 79.93 °F
