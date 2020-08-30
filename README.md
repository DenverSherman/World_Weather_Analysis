# World_Weather_Analysis
Trend research on lattitude and weather for travel planning

## Background
In pretend employ to a travel site, I am tasked with creating vacation suggestions based on client's weather preferences.

## Sampling and Data Assembly
To start, a random sample of 2000 geocooridnates is generated. From this, the citipy module is used to find the nearest city. Duplicate cities are then removed from the list. City names are leveraged by the OpenWeatherData API to generate a dataframe of weather information, error-causing null values are removed. The user is then prompted to provide a range of preferrable temperatures which further filters the list.

## Analysis
The Google Maps API and the gmaps module work together to produce maps detailing weather information and geographic detail on all cities with preferable weather.

<p align="center">
  <img src="https://github.com/DenverSherman/World_Weather_Analysis/blob/master/Vacation_Search/WeatherPy_vacation_map.png">
</p>

From these vacation spots, I suggest and plan a travel itinerary between 4 cities in close proximity. These happen to be in the beautiful Sunshine State. Map overlay provided by the google maps directions API.

<p align="center">
  <img src="https://github.com/DenverSherman/World_Weather_Analysis/blob/master/Vacation_Itinerary/Vacation_Itinerary.png">
</p>

