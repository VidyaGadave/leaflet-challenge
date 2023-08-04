# Leaflet Challenge

This repository contains Leaflet.js visualization for the USGS earthquake data. In order to run view this visaulisation execute index.html file.

Data source: USGS (https://earthquake.usgs.gov/earthquakes/feed/v1.0/geojson.php)

The javascript code does following things-

1. Fetch GeoJSON data from USGS Data Feed for the last 7 days.
2. Create a world map to plot all the earthquakes in the last 7 days.
3. Adds markers to reflect the magnitude for the earthquake by the size of the maker and depth of the earthquake by the color.
4. Popups that provide additional information about the earthquake like the location
5. Legend that provides context on the depth of the earthquakes.

![Earthquake viz](https://github.com/VidyaGadave/leaflet-challenge/blob/main/Images/map.png)