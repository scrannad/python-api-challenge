# API Challenge
## Part 1-WeatherPy
This script helps us visualize weather from over 500 randomly selected cities of varying distances from the equator. Using the citipy Python library and the OpenWeatherMap API, I showcase the relationships between weather variables and latitude. I include scatter plots showing the following relationships:
  - Latitude vs. Temperature
  - Latitude vs. Humidity
  - Latitude vs. Cloudiness
  - Latitude vs. Wind Speed
  
I then compute and plot linear regression for each relationship in both the Northern and Southern hemispheres and analyze any relationships found. 

## Part 2-VacationPy
This script uses the weather data gathered in Part 1 to plan future vacation destinations. Using the geoViews Python library and Geoapify API, I create a Pandas DataFrame and map visualization to show the humidity level in each city. From there I narrow down the DataFrame to include ten cities with ideal weather between 17 and 27 degrees celsius, low wind speed, and zero cloudiness. Finally, I use geoapify to find and plot hotel names in each of the ten cities in another map visualization which can be viewed, along with Part 1 plots, in the output_data file. 
