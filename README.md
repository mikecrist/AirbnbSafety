# Airbnb Safety
Interactive map of Airbnb property listings overlayed with heat map of neighborhood-specific crime risk; Model to estimate Airbnb listing price based upon accommodations and local crime.

## Credits
This project was created for the Georgia Tech Master of Analytics program.<br>
**Course:** Data and Visual Analytics (CSE6242)<br>
**Team:** Michael Crist, Albert Hsueh, Sergio Roca

## Table of Contents

## Environment
The below instructions are provided to set up your environment within Anaconda.

In Anaconda create a new environment and then run these commands in the Anaconda Prompt:
conda install -c conda-forge fiona=1.8.19
 
conda install -c conda-forge shapely rasterio pyproj pandas jupyterlab geopandas flask

pip install statsmodels

These packages are needed to work with Geopandas and using Flask as the framework for the website.


