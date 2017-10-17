# AirQualityDI
Air quality project to visualize current and past air quality and predict air quality based on atmospheric conditions

### AirQualityData.ipynb
Accesses AirNow API (EPA site) based on time and geograpic location and maps the returned data.  Also plots a time series for for the 12 running average PM25 (pollutant) for Seattle, WA and New York, NY.

### AirQualityAna.ipynb
Generates a linear regression model and a gradient boosted regression model to predict air quality (PM25) from current atmospheric conditions.

### fancy_map.html
Interactive map produced by the folium map package. (http://python-visualization.github.io/folium/)
