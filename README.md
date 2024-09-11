# Module Challenge 6: Python API

![Equator Image](https://github.com/SakinaJaffri/Module_Challenge6_Python_API-/assets/146900226/ae9b7af7-424c-418e-bb47-769a3ad232c6)

## Overview

This project involves using Python to interact with APIs and analyze weather data from various cities across the globe. The goal is to understand the relationship between weather variables and latitude, and to plan ideal vacation locations based on weather conditions.

## Deliverables

### Part 1: WeatherPy

1. **Visualizing Weather Data:**
   - Utilized the OpenWeatherMap API to gather weather data for over 500 cities.
   - Created scatter plots to visualize relationships between:
     - Latitude and Temperature
     - Latitude and Humidity
     - Latitude and Cloudiness
     - Latitude and Wind Speed

2. **Computing Linear Regression:**
   - Conducted linear regression analysis to understand the relationship between weather variables and latitude.
   - Created separate plots for:
     - Northern Hemisphere vs. Southern Hemisphere for each weather variable.

### Part 2: VacationPy

1. **Mapping Cities:**
   - Used the Geoapify API and geoViews Python library to create a map displaying cities with points sized by humidity.

2. **Finding Ideal Weather Conditions:**
   - Filtered cities based on desired weather conditions:
     - Maximum temperature between 21°C and 27°C
     - Wind speed less than 4.5 m/s
     - Zero cloudiness

3. **Finding Hotels:**
   - Created a DataFrame with city details and used the Geoapify API to locate hotels within 10,000 meters of the filtered cities.
   - Added hotel names and country information to the map for an enhanced visualization.

## Technologies Used

- **Python**
- **Jupyter Notebook**
- **OpenWeatherMap API**
- **Geoapify API**
- **geoViews Python Library**
- **Pandas**

## Instructions

1. Clone the repository to your local machine.
2. Install the necessary Python packages listed in `requirements.txt`.
3. Open `WeatherPy.ipynb` to analyze weather data and visualize the results.
4. Open `VacationPy.ipynb` to create maps, filter ideal vacation locations, and find hotels.

## Conclusion

This project demonstrates the power of Python APIs in weather data analysis and visualization. By examining how weather variables relate to latitude and finding ideal vacation spots based on weather conditions, this project showcases practical applications of data analysis and mapping.

## Contributors

- **Sakina Jaffri** - Project Developer
