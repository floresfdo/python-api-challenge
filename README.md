# python-api-challenge

Data Bootcamp Python APIs Homework - Observations for WeatherPy included at initial part of WeatherPy notebook.

This includes a Python script that pulls the weather of 500+ cities with varying distances from the equator using a Python library, the OpenWeatherMap API, and some logic to create this model. 
Once data is pulled using the API, we showcase the relationship that exists between the factors listed below and a city's latitude:
Temperature (F) vs. Latitude
Humidity (%) vs. Latitude
Cloudiness (%) vs. Latitude
Wind Speed (mph) vs. Latitude

We also analyze these factors by grouping cities on Northern & Southern Hemisphere.

The second script in this challenge includes the use of Google APIs to reflect the hotel in the cities that match our "vacation weather threshold".
Using the list of 500+ cities from the first part we filter them out based on weather conditions we look for on cities we would like to vacation.
Once that list is set, we search for the nearest hotel based on the city's coordinates.
At the end our script reflects all these cities on a map with the name of the hotel we found.
