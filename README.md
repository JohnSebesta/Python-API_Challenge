# Python-API_Challenge
Overview

This project consists of two parts: WeatherPy and VacationPy. The goal of this project is to visualize and analyze weather data from over 500 cities across different latitudes and plan vacation destinations based on ideal weather conditions.

WeatherPy focuses on retrieving weather data using the OpenWeatherMap API, analyzing weather patterns, and creating scatter plots and linear regression models based on the relationship between weather variables and latitude. VacationPy uses weather data to create a map visualization of cities and determine vacation locations with ideal weather, combining it with the Geoapify API to locate nearby hotels.

Methodology

Part 1: WeatherPy
Data Collection:
We retrieve weather data from cities worldwide using the OpenWeatherMap API and the citipy Python library to find the nearest city for each set of random geographic coordinates.
Data Visualization:
We generate scatter plots to show the relationship between latitude and various weather variables, including temperature, humidity, cloudiness, and wind speed.
Each plot includes a linear regression line, with separate visualizations for the Northern and Southern Hemispheres.
Linear Regression Analysis:
For each weather variable (temperature, humidity, cloudiness, and wind speed), we compute the linear regression to identify trends and relationships between the weather data and latitude.
Each scatter plot is annotated with the regression formula and r-squared values to evaluate the strength of the linear relationship.
Part 2: VacationPy
Map Visualization:
We create a map displaying all cities in the dataset, with points sized according to the humidity level in each city.
Ideal Vacation Criteria:
We filter the cities based on desired weather conditions, such as a maximum temperature between 21-27°C, wind speed less than 4.5 m/s, and zero cloudiness.
Hotel Search:
Using the Geoapify API, we search for nearby hotels within 10,000 meters of each city's coordinates.
The resulting map highlights each city with additional hover information, including the hotel name and country.
Results

WeatherPy:
The scatter plots reveal interesting trends in how weather variables like temperature, humidity, cloudiness, and wind speed relate to latitude.
Linear regression lines help clarify these relationships, showing that temperature tends to decrease as latitude increases in the Northern Hemisphere, while the relationships for other variables, such as humidity and wind speed, are more variable.
A clear distinction between the Northern and Southern Hemispheres is apparent in the regression analysis for temperature and humidity.
VacationPy:
A map visualization was created with each city plotted according to its humidity level.
After filtering cities by ideal weather conditions, a map was generated that highlighted cities that met the criteria for a perfect vacation spot.
Nearby hotels were successfully identified and displayed as part of the map, providing useful vacation planning information.

References
The tutor Lucas
ChatGPT
XpertLearning Assistant
