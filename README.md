# python-api-challenge
Repository for HW6

A two part challenge to "create a Python script to visualize the weather of 500+ cities of varying distance from the equator."  Tasks include creating scatter plots of the following relationships:

PART 1:  WeatherPy

* Temperature (F) vs. Latitude
* Humidity (%) vs. Latitude
* Cloudiness (%) vs. Latitude
* Wind Speed (mph) vs. Latitude

The next task:

Compute a linear regression for each of the following:

* Northern Hemisphere - Temperature (F) vs. Latitude
* Southern Hemisphere - Temperature (F) vs. Latitude
* Northern Hemisphere - Humidity (%) vs. Latitude
* Southern Hemisphere - Humidity (%) vs. Latitude
* Northern Hemisphere - Cloudiness (%) vs. Latitude
* Southern Hemisphere - Cloudiness (%) vs. Latitude
* Northern Hemisphere - Wind Speed (mph) vs. Latitude
* Southern Hemisphere - Wind Speed (mph) vs. Latitude

Must have 500 RANDOM unique cities
print a log of each city that is processed
Save results to a csv file and plots to png images

PART 2:  VacationPy

Create a heat map for every city in part 1 over humidity
Narrow a city search based off of three weather conditions dropping cities that don't meet them

Use google API to find first hotel within 5 km of coordinates
Plot hotels on top of heatmap and have a PIN Label with Hotel Name, City and Country
