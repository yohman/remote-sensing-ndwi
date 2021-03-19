# Google Earth Engine NDWI Maps

The Normalized Difference Water Index (NDWI) is used to detect water bodies or changes in water level, and is typically used to detect flooding.

<img src="images/ndwi.png">
Satellite imagery from Sentinel-2 taken before and after the 2020 Kyushu Floods in Japan. The top row show bands B4, B3, B2, and the bottom row shows NDWI normalized bands for B3, B5.


This Jupyter Notebook provides an approach that uses Python to import Sentinel-2 satellite imagery for a given region of interest and a given time span. It then produces an interactive web map using the Folium leaflet library.

## Example leaflet output

<a href="https://yohman.github.io/remote-sensing-ndwi/kumamoto.html"><img src="images/ndwi_leaflet.png"></a>

https://yohman.github.io/remote-sensing-ndwi/kumamoto.html

## Binder

You can launch this notebook using the binder link below.

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/yohman/remote-sensing-ndwi/HEAD?filepath=ndwi.ipynb)
