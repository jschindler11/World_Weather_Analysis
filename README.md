# World_Weather_Analysis

* We generated a set of 2,000 random latitudes and 2,000 longitudes, used the citipy module to get the nearest city for each latitude and longitude combination, and retrieved the following information from OpenWeatherMap's API:
  1) Latitude and longitude
  2) Maximum temperature
  3) Percent humidity
  4) Percent cloudiness
  5) Wind speed
  6) Weather description (for example, clouds, fog, light rain, clear sky)
  
  We then added this new data to a DataFrame and exported the DataFrame as a CSV file.
  
* After importing this CSV file as a Pandas DataFrame, we wrote two input statements that prompt the user to enter their minimum and maximum temperature criteria for their vacation. We then used the loc Pandas method to filter the DataFrame for temperature criteria collected. After using the Pandas dropna function on the DataFrame to drop any empty rows, we created a new DataFrame with a new empty column named Hotel Names.





