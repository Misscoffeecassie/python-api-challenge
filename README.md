# python-api-challenge
Module 6
NOte: 4 Files in total, including "WeatherPy.ipynb" and "VacationPy.ipynb", plus "api_key.py" and a ".gitignore" File.

# Part 1: WeatherPy
Create a Python script to visualise the weather of over 500 cities of varying distances from the equator.By using the citipy Python libraryLinks to an external site., the OpenWeatherMap APILinks to an external site., and problem-solving skills to create a representative model of weather across cities.
First of all, the beginning codes required to generate random geographic coordinates and the nearest city to each latitude and longitude combination is provided.

> Requirement 1: Create Plots to Showcase the Relationship Between Weather Variables and Latitude
    1, Use the OpenWeatherMap API to retrieve weather data from the cities list generated in the starter code. 
    2, Next, to create a series of scatter plots to showcase the following relationships:
    .. Latitude vs. Temperature
    .. Latitude vs. Humidity
    .. Latitude vs. Cloudiness
    .. Latitude vs. Wind Speed

> Requirement 2: Compute Linear Regression for Each Relationship
    1, Compute the linear regression for each relationship. Separate the plots into Northern Hemisphere (greater than or equal to 0 degrees latitude) and Southern Hemisphere (less than 0 degrees latitude). (Hint: it's helpful to define a function in order to create the linear regression plots.)

    2, Next, create a series of scatter plots. Be sure to include the linear regression line, the model's formula, and the r values.

    3, create the following plots:

        .. Northern Hemisphere: Temperature (C) vs. Latitude

        .. Southern Hemisphere: Temperature (C) vs. Latitude

        .. Northern Hemisphere: Humidity (%) vs. Latitude

        ..  Southern Hemisphere: Humidity (%) vs. Latitude

        ..  Northern Hemisphere: Cloudiness (%) vs. Latitude

        .. Southern Hemisphere: Cloudiness (%) vs. Latitude

        ..  Northern Hemisphere: Wind Speed (m/s) vs. Latitude

        .. Southern Hemisphere: Wind Speed (m/s) vs. Latitude

> Requirement 3: After each pair of plots, explain what the linear regression is modelling. Describe any relationships that I notice and any other findings.      

# Part 2: VacationPy
use your weather data skills to plan future vacations. Also, the geoViews Python library, and the Geoapify API will be used. (Hint: Geoapify Website: https://apidocs.geoapify.com/docs/places/#categories).

The code needed to import the required libraries and load the CSV file with the weather and coordinates data for each city created in Part 1 is provided to help to get started.

Main tasks will be to use the Geoapify API and the geoViews Python library and employ your Python skills to create map visualisations.

> Requirement 1: Create a map that displays a point for every city in the city_data_df DataFrame as shown in the following image. The size of the point should be the humidity in each city.

> Requirement 2: Narrow down the city_data_df DataFrame to find your ideal weather condition. 
    For example: 
        A max temperature lower than 27 degrees but higher than 21
        Wind speed less than 4.5 m/s
        Zero cloudiness

> Requirment 3: Create a new DataFrame called hotel_df to store the city, country, coordinates, and humidity.

> Requirment 4: For each city, use the Geoapify API to find the first hotel located within 10,000 metres of your coordinates.

> Requirment 5: Add the hotel name and the country as additional information in the hover message for each city in the map.

# Part 3: api_key.py File
Storing my OpenWeatherMap API Key & Geoapify API Key.

# Part 4:  ".gitignore" File
 help to keep my API keys safe without exposing the api_keys.py file with my API key to the public.