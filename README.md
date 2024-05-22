# Surface-Water-Extent-Time-Series-Analysis
A Python script that computes the total surface water area within an inland water body for a specified time range using the Google Earth Engine Python API. The script creates a time series of the surface water extent values and plots the data using Seaborn.
Requirements

    Python 3.7 or higher
    Google Earth Engine Python API
    Pandas
    Matplotlib
    Seaborn
Script Overview

The script performs the following steps:

    Initializes the Google Earth Engine API.
    Defines a function to extract water extent time series for a given geometry and time range.
    Loads the Sentinel-2 Surface Reflectance image collection and filters it based on the provided dates and geometry.
    Calculates the water area for each image using the Normalized Difference Water Index (NDWI).
    Converts the water area data into a list of dictionaries for easy plotting.
    Uses Seaborn to plot the time series data and saves the plot as an image file.
Notes

    Ensure to have a valid Google Earth Engine account and the necessary permissions to access the data.
    The script uses the NDWI threshold of 0.25 to identify water pixels. Adjust this threshold if needed based on your specific requirements.

Deliverables

    Python scripts used to complete the task.
    README file showing the steps to run the script on your systems.
