# Python-API-Challenge

# Weather:
This challenge used the citypy library & OpenWeatherAPI to create a list of 500+ cities from their longitude & latitude coordinates.  The API calls returned several measures (max temp, humidity, cloudiness, wind speed) for each city.
I then used pandas & matplotlib to analyze this data and created scatter plots & linear regression to determine any correlation between the above categories vs. latitude (closer/further from equator).  Notes for each graph are listed within the Jupyter notebook.

# Vacation:
The second part of the challenge built upon the first and utlized Google Places API to create heatmaps & add markers.
An initial heatmap was created to illustrate different humidity percentages throughout the world, based on the data collected in the weather challenge.
The large dataset was then filtered down to include only cities with ideal temperature range (70-80) & cloudless skies.  Using geocities within the Google API, I located the closest hotel to each city's coordinates and added markers to the heatmap.

# NOTE: Unique API keys are required to call data from both OpenWeatherAPI & Google Maps API.  My config file containing both of my keys was not included for security purposes.