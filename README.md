# AnalysisOfWeather
Python code for weather analysis

# The first file: Weather Analysis

The script will create a series of scatter plots to showcase the following relationships:

  * Temperature (F) vs. Latitude
  * Humidity (%) vs. Latitude
  * Cloudiness (%) vs. Latitude
  * Wind Speed (mph) vs. Latitude
  
# Analysis Of Weather Relationships

1. There is a high correlation between temperature and latitude. This makes sense since the temparature is based on how close the location is with the equator (measured as latitude).
2. It seems that there are no correlation between cloudiness and latitude.
3. It seems that there are no correlation between humidity and latitude.
4. It seems that there are no correlation between wind speed and latitude. Wind speed tends to generally be betweeen 0 and 20 mph regardless of latitude


Next, it will compute the following linear regression for each relationship. 

  * Northern Hemisphere - Temperature (F) vs. Latitude
  * Southern Hemisphere - Temperature (F) vs. Latitude
  * Northern Hemisphere - Humidity (%) vs. Latitude
  * Southern Hemisphere - Humidity (%) vs. Latitude
  * Northern Hemisphere - Cloudiness (%) vs. Latitude
  * Southern Hemisphere - Cloudiness (%) vs. Latitude
  * Northern Hemisphere - Wind Speed (mph) vs. Latitude
  * Southern Hemisphere - Wind Speed (mph) vs. Latitude

# Analysis Of Weather Linear Regression

1. The Southern Hemisphere weather seems to be warmer than Northern since closer to the equator (around 0 latitude). For the northern hemisphere, there is a significant negative correlation between latitude and maximum temperature while there is a positive correlation in the southern hemisphere.

2. There is a weak correlation for Humidity and Latitude in Northern Hemisphere and there is no significant correlation between latitudes and humidity in the southern hemisphere.

3. There is no relationship between latitude and cloudiness in the Northern hemisphere while there is a weak correlation in the southern hemisphere. 

4. In the northern hemisphere, the relationship between latitude and wind speed is not significant and in the southern hemisphere, there is no correlation between the latitude and wind speed.

The output data (csv file) and graphs saved are uploaded in output_data folder.

# The second file: Vacation Analysis

The script is used to create a heatmap and identify the hotels within the 5000 radius of the preferred weather condition.
The heatmap and hotel markers are uploaded as screenshots in images folder.




