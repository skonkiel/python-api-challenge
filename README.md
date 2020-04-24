# python-api-challenge

## Project background

This project analyzes world weather data to find the ideal places to vacation.

This project is comprised of two parts. In the first part, `WeatherPy`, I've analyzed and visualized current cloud cover, wind speed, humidity, and temperature observations for 500+ random cities worldwide. I've used linear regressions to determine correlations between location and various weather variables.

In the second part, `VacationPy`, I've set desirable enviornmental variables and then mapped locations that meet these criteria, bringing in data on nearby lodging.
 
This project uses:

* [OpenWeatherMap API](https://openweathermap.org/api) 
* [Google Maps API](https://developers.google.com/maps/documentation) 
* [Gmaps](https://pypi.org/project/gmaps/), a Python library for using Google Maps in Jupyter Notebooks
* [citipy](https://pypi.org/project/citipy/), a Python library for looking up cities given lat/lng coordinates
* pandas
* matplotlib

## Installation

1. Clone this repository
2. Launch a Jupyter Notebook from Git Bash/Terminal (by running `jupyter notebook`). You will likely need to install some of the Python packages listed above.
3. Open and run `WeatherPy.ipynb`, then `VacationPy.ipynb` (in that order).
