# python-api-challenge

WeatherPy and VacationPy Overview

WeatherPy and VacationPy are Python scripts designed to analyze weather data for over 500 cities and assist in planning future vacations based on weather preferences. WeatherPy utilizes the citipy Python library along with the OpenWeatherMap API to gather and visualize weather data. On the other hand, VacationPy employs Jupyter notebooks, the geoViews Python library, and the Geoapify API to create map visualizations for vacation planning.

Part 1: WeatherPy
In WeatherPy, random geographic coordinates are generated, and the closest city to each latitude and longitude pair is determined using the citipy library. Subsequently, weather data for each city is retrieved from the OpenWeatherMap API. The collected data is then visualized to create weather models across various cities.

Part 2: VacationPy
VacationPy utilizes the weather data obtained in Part 1 to facilitate vacation planning. It integrates the Geoapify API and geoViews Python library to generate map visualizations. Users can input their weather preferences (such as temperature, humidity, cloudiness, and wind speed) to identify optimal vacation destinations.
