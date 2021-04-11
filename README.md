# api-challenge

This analysis uses the citipy library to create a random selection of 500+ cities from all around the world.

Using this selection of cities, WeatherMap open API is then used to grab weather data for each of the cities in the [WeatherPy](https://github.com/lmfao415/Python-API-Challenge/tree/main/WeatherPy) part of the analysis.

Plots in the [output_data](https://github.com/lmfao415/Python-API-Challenge/tree/main/WeatherPy/output_data) folder were then made to compare the latitude versus the different weather conditions at each location:
Latitude vs. Temperature,
Latitude vs. Humidity,
Latitude vs. Cloudiness,
Latitude vs. Wind Speed,

For example, here is the plot showing temperature versus latitude:
![sample](https://github.com/lmfao415/Python-API-Challenge/blob/main/WeatherPy/output_data/Lat_vs_Temp.png?raw=true) Jupyter Notebook
Linear regression was then ran for these same variables but with the data split between Northern and Southern hemispheres. 

A [heatmap](https://github.com/lmfao415/Python-API-Challenge/tree/main/VacationPy/heatmaps) is made in the [VactionPy](https://github.com/lmfao415/Python-API-Challenge/tree/main/VacationPy) section showing the humidities around the world.
A susbset is then made of cities with desirable conditions to visit, and these cities with hotels are plotted on the heatmap
