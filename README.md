The purpose of this project is to examine the effect on certain weather measurements by latitude and longitude.

It begins by using the numpy library to randomly generate an array of latitudes and longitudes. Then citipy was used to match those locations with city names. An API call is performed to pull weather data (humidity, wind speed, cloudiness, and max temperature) from Open Weather Map. Next we use Pandas and Matplotlib to analyze and plot the data, using the graphs to formulate the following conclusions:

1) As expected, there is a clear correlation between max temperature and city latitude.
2) There is no clear correlation between wind speed and either latitude or longitude.
3) There is no clear correlation between cloudiness and city latitude; however, the shape of the scatter plot does seem to indicate that this is based more on an estimation or possibly a range. The plots are grouped at certain points on the scale: 0, 20, 40, 75, and 100.
