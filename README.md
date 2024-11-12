# Brightness Temperature Data Analysis and Visualization

This repository contains code and data for analyzing **Brightness Temperature** data from the NCEP dataset. The project includes preprocessing of the Brightness Temperature data, categorization of temperature levels, and visualization of the results.

## Project Description

This project involves the processing of NCEP Brightness Temperature data, followed by categorization of temperature values into different levels. The project also includes various data visualizations, such as contour plots, to analyze the spatial and temporal distribution of brightness temperature.

Key tasks covered by the project:
- Data preprocessing and cleaning of NCEP Brightness Temperature data.
- Categorization of Brightness Temperature into different levels based on temperature thresholds.
- Visualization of categorized data through contour plots and time series.

## Files in the Repository

- **`notebooks/`**: Contains Jupyter notebooks for Brightness Temperature data analysis and categorization.
- **`data/`**: Directory containing raw NCEP Brightness Temperature data files in `.nc` format (NetCDF) and other related data files.
- **`images/`**: Directory containing generated images from the analysis (contour plots, temperature visualizations, etc.).
- **`scripts/`**: Python scripts for processing, categorizing, and visualizing Brightness Temperature data.
- **`README.md`**: The file you are currently reading, explaining the project and its contents.

## Requirements

The following Python libraries are required to run the notebooks and scripts:

- numpy
- xarray
- pandas
- matplotlib
- Basemap
- cartopy

You can install the required libraries using `pip`:

```bash
pip install numpy xarray pandas matplotlib basemap cartopy
