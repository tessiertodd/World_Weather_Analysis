# World_Weather_Analysis

## Project Overview
Jack who we are working with really like an app we worked on, but thinks if we add a few features it will be even better.

We are tasked with working on 3 deliverables that will lead to improvements on the app that it is felt users will really appreciate.

## Resources
- Data Source: www.openweathermap.com
- Data Source: gmaps being leveraged to build maps via API
- Sofware: Jupyter Notebook 6.3.0
- Library: matplotlib.pyplot
- Library: pandas
- Library: numpy
- Library: citypy
- Library: requests
- Library: datetime
- Library: gmaps
- Language: Python 3.6.7

# Deliverable 1: Retrieve Weather Data
The first step we need to do to build on this app that users can use to try to choose where they would like to go on vacation based on a temperature range they select, is that we need to get all the information about many cities in the world - we have randomized lattitude and longitute to come up with 2000 random coordinates and where they were close to cities, the information on those cities were collected in a DataFrame, we had just over 700 cities from this excercise.  The information on each city was received via an API from a website call "open weather map" that has information on cities across the world.  This information was required for Deliverable 2.


# Deliverable 2: Create a Customer Travel Destination Map
Create an input we get from a customer for their minimum and maximum temperature range of places they would like to vacation. Before asking for the guidelines, we made sure all the cities we within 5,000 meters of a hotel so that cities we showed would at a minimum have accomodations for travellers. Using the limits that users chose on temperature, we choose cities that fall within the chosen guidelines and build a map with destination markers on the map so users can see their options visually.

![Table_for_Map_with_Markers](https://github.com/tessiertodd/World_Weather_Analysis/blob/main/Vacation_Search/WeatherPy_vacation_map.png)


# Deliverable 3: Create a Travel Itinerary Map
We are to create a travel itinerary map with the help of Google Directions API to create a driving route for users and a map showing the city markers for their itinerary.

![Table_for_Travel_Directions_Itinerary](https://github.com/tessiertodd/World_Weather_Analysis/blob/main/Vacation_Itinerary/WeatherPy_travel_map.png)
![Table_with_markers_for_itinerary](https://github.com/tessiertodd/World_Weather_Analysis/blob/main/Vacation_Itinerary/WeatherPy_travel_map_markers.png)

# Conclusion
With these additions to to app, users can now use to help them plan a trip, with a little more information on where they may go and some details about each location.

