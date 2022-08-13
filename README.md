# A Vacation Spot Finder

### python-api-challenge
Repository for HW6
by: Arnold Schultz



## PART 1:  WeatherPy

This is a Python script to visualize the weather of 500+ completely random cities.  Once collected I obtain the weather data for these cities and create scatter plots to look at the following relationships:

    - Temperature (F) vs. Latitude
    - Humidity (%) vs. Latitude
    - Cloudiness (%) vs. Latitude
    - Wind Speed (mph) vs. Latitude

With that information one can then do a linear regression to see the behavior of the weather parameters based on distance from the equator.

We can split the linear regressions into each hemisphere:

    - Northern Hemisphere - Temperature (F) vs. Latitude
    - Southern Hemisphere - Temperature (F) vs. Latitude
    - Northern Hemisphere - Humidity (%) vs. Latitude
    - Southern Hemisphere - Humidity (%) vs. Latitude
    - Northern Hemisphere - Cloudiness (%) vs. Latitude
    - Southern Hemisphere - Cloudiness (%) vs. Latitude
    - Northern Hemisphere - Wind Speed (mph) vs. Latitude
    - Southern Hemisphere - Wind Speed (mph) vs. Latitude

A log of each city that is processed is printed to the screen and the results are saved to a csv file.
The plots are saved as png image files.

## PART 2:  VacationPy

In this notebook I create a heat map for every city in part 1 over humidity. I then norrow my selection of cities to only those that meet the following conditions:

    - Maximum Temperature between 80 and 90 degrees fahrenheit
    - Both humidity and cloudiness less than 50%
    - Wind speed less than 10 mph
    
All cities that don't meet them are dropped

Then I use google API to find first hotel within 5 km of coordinates and plot the hotels on top of heatmap and have a PIN Label with Hotel Name, City and Country
