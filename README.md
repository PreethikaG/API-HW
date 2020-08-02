The aim of the project was to play around with matplotlib visualizations using the weather data returned from an API called OpenWeatherMap API.
Used the citipy module to get nearest city name for randomly generated latitude and longitude and created a list of 500+ cities. 

API Process -
 
Performed a weather check on each of the cities using a series of successive API calls to OpenWeatherMap API.
Stored the data in a dataframe for further processing.

Visualizations - 

Using Matplotlib, I created scatter plots to find out the relation between the following:

* Temperature (F) vs. Latitude
* Humidity (%) vs. Latitude
* Cloudiness (%) vs. Latitude
* Wind Speed (mph) vs. Latitude

I created a custom function to plot a series of scatter plots and linear regression relationship on each of the above mentioned relationship,only this time separating them into Northern Hemisphere and Southern Hemisphere.

* Northern Hemisphere - Temperature (F) vs. Latitude
* Southern Hemisphere - Temperature (F) vs. Latitude
* Northern Hemisphere - Humidity (%) vs. Latitude
* Southern Hemisphere - Humidity (%) vs. Latitude
* Northern Hemisphere - Cloudiness (%) vs. Latitude
* Southern Hemisphere - Cloudiness (%) vs. Latitude
* Northern Hemisphere - Wind Speed (mph) vs. Latitude
* Southern Hemisphere - Wind Speed (mph) vs. Latitude

Analysis - 

I was able to find out some important relationships based on visualizations and linear regression.
As the latitude increases the maximum temperature decreases and it becomes more humid. However,there seems to be no big relation between latitude and cloudiness of a
city or between wind speed and the latitude.






