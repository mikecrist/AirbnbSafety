# Airbnb Safety
This project provides an interactive map of Airbnb property listings overlayed with a heat map of neighborhood-specific crime risk.  Additionally, it provides a model to estimate Airbnb listing price based upon accommodations and local crime.

**Project Report:** [Report](https://github.com/mikecrist/AirbnbSafety/blob/main/Report/Report_AirbnbSafety.pdf)

## Credits
This project was created for the Georgia Tech Master of Analytics program.<br>
**Course:** Data and Visual Analytics (CSE6242)<br>
**Team:** Michael Crist, Albert Hsueh, Sergio Roca

## Table of Contents
- [Environment Setup](#Environment-Setup)
- [Running the Project](#Running-the-Project)

## Environment Setup
The below instructions are provided to set up your environment within Anaconda.

In Anaconda, create a new environment and then run these commands in the Anaconda Prompt:
```
conda install -c conda-forge fiona=1.8.19
 
conda install -c conda-forge shapely rasterio pyproj pandas jupyterlab geopandas flask

pip install statsmodels
```
These packages are needed to work with Geopandas and using Flask as the framework for the website.

## Running the Project
In the Anaconda prompt, navigate to the folder with this repository and run the below command:
```
python app.py
```
Then navigate to http://127.0.0.1:5000/ on your browser, and the application will appear.


