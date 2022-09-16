# World_Weather_Analysis
 This analysis gives different weather patterns with weather data which consists the weather description along with basic informations about the city around the world and offers insights to travelers who want to book a trip. There are three different analysis which helps customers are weather database, vacation search, and vacation itinerary.



## 1. Weather Data : Retrieve Weather Data
This section of analysis generates a set of 2,000 random latitudes and longitudes and retrieved the nearest city using an API call with the OpenWeatherMap. Achieved to get around 700 cities from 2000 lat-long pairs. Weather data for each city consists of,
*  Latitude and longitude
*  Maximum temperature
*  Percent humidity
*  Percent cloudiness
*  Wind speed
*  Weather description (for example, clouds, fog, light rain, clear sky)

## 2. Vacation Search : Create a Customer Travel Destinations Map
This section of analysis, uses input statements to retrieve customer weather preferences(preferred min and max temperature), and using weather database and google API, get the potential travel destinations and nearby hotels. Then, show those destinations on a marker layer map with pop-up markers with hotel names and other information of the city.
!["Vacation Search" ](../World_Weather_Analysis/Vacation_Search/WeatherPy_vacation_map.png?raw=true "Vacation Search")


## 3. Vacation Itinerary : Create a Travel Itinerary Map
This analysis uses the Google Directions API to create a travel itinerary that shows the route between four cities chosen from the customer’s possible travel destinations. This gives a marker layer map with a pop-up marker for each city on the itinerary as below,

The images below shows a 4 stop direction layer and a pop up marker layer for each city on the map.

!["Vacation Itinerary" ](../World_Weather_Analysis/Vacation_Itinerary/WeatherPy_travel_map.png?raw=true "Vacation Itinerary")


!["Vacation city marker" ](../World_Weather_Analysis/Vacation_Itinerary/WeatherPy_travel_map_markers.png?raw=true "Vacation city marker")








