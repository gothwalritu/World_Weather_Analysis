# World_Weather_Analysis

# Overview

In this challenge we are collecting and analyzing weather data for cities all over the world. THe purpose of this exercise is to recommend hotels to travellers based on their preference of weather and temperature conditions. We have performed this analysis in three levels which is stored in thre folder namely, Weather database, Vacation search and Vacation itinerary, described in the following sections of the write ups.

## 1. Weather database

In this section we created a set of random set of latitudes and longitudes to search for the nearest city using the Citypy module. We retrivied the weather data for those ciities by performing as API call with "OpenWeatherMap". The following weather parameters were obtained and stored in a DataFrame and exported to a CSV file.
a. Latitude and longitude
b. Maximum temperature
c. Percent humidity
d. Percent cloudiness
e. Wind speed
f. Weather description 

## 2. Vacation search

Based on the inputs from customers for minimum and maximum temperature preferences, cities were selected to find the information on hotels using loc method. A new DataFrame was created for hotels information and exported as CSV file which was stored in the Vacation_Search folder. The screenshot of the hotel DataFrame is shown below.

![Screenshot for hotel_df](https://github.com/gothwalritu/World_Weather_Analysis/blob/main/Vacation_Search/hotel_df_screenshot.png)

In this section we also created a map with pop-up markers for the cities by performing an API call with Google Maps. Differnt travel destination were plotted with a hotel at each location. The marker contained the following information.
a. Hotel name
b. City
c. Country
d. Current weather with maximum temperature
Below is the image of the maps with pop-up marker.

![Figure2](https://github.com/gothwalritu/World_Weather_Analysis/blob/main/Vacation_Search/weatherPy_vacation_map.png))



## 3. vacation itinerary
In this section we created a itinerary of four cities in the same country with similar temperature preference of 75-90 degrees. We performed an API call with gmaps to create directions layer map for the four chosen cities whose screenshots is saved in the following figure:

![Figure_3](https://github.com/gothwalritu/World_Weather_Analysis/blob/main/Vacation_Itinerary/weatherPy_travel_map.png)

Four cities of India were chosen: Narnaul, Veraval, Ranchi and Kattivakkam and shown in the following screenshot with pop-up markers.

![Figure_4](https://github.com/gothwalritu/World_Weather_Analysis/blob/main/Vacation_Itinerary/weatherPy_travel_map_markers.png)








