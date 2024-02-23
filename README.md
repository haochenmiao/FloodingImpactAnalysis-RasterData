# Flooding Analysis Project

## Overview

This project focuses on analyzing the impact of a flood event using raster data. Through a series of Jupyter notebooks, we open, explore, and process raster data to understand changes in canopy height and terrain caused by the flooding. The analysis is performed using Python, leveraging libraries such as `numpy`, `matplotlib`, `seaborn`, `geopandas`, `rioxarray`, and `earthpy`.

## Objectives

- **Open and plot raster data**: Introduce techniques to handle and visualize raster datasets in Python.
- **Analyze canopy height model (CHM)**: Calculate and classify changes in the canopy height before and after the flood.
- **Terrain analysis**: Examine changes in the terrain extracted from Digital Terrain Models (DTMs) before and after the flood.
- **Visualize changes**: Create classified raster maps to clearly depict the impact of the flood on the landscape.

## Notebooks

### 1. Opening and Exploring Raster Data (`Part1_Opening_and_Exploring_Raster_Data.ipynb`)

This notebook covers the basics of working with raster data in Python, including how to open, plot, and explore raster files. Key operations include handling "no data" values and creating plotting extents for combined raster and vector data visualization.

### 2. Raster Data Calculation and Classification (`Part2_Raster_Data_Calculation_and_Classification.ipynb`)

Focuses on subtracting rasters to create new GeoTIFF files, calculating the CHM, and classifying raster data based on the canopy height before and after the flood. This notebook demonstrates how to manipulate and analyze raster data to extract meaningful insights.

### 3. Change Over Time Analysis (`Part3_Change_Over_Time_Analysis.ipynb`)

Analyzes changes over time in canopy height and terrain due to the flooding. This notebook provides a detailed look at how to quantify and visualize environmental changes using geospatial data, creating maps that clearly show areas of positive and negative change.

## Installation Requirements

Ensure the following Python libraries are installed to run the notebooks:

- numpy
- matplotlib
- seaborn
- geopandas
- rioxarray
- earthpy

## Usage

Each notebook includes detailed instructions and code for performing the analyses. To replicate the study, follow the steps outlined in each notebook within a Jupyter environment.

## Contributing

We welcome contributions and suggestions to improve the analysis. Please feel free to fork the project and submit pull requests.

## Authors

- Haochen Miao

## Acknowledgments

We thank the providers of the raster datasets used in this analysis, including the National Ecological Observatory Network (NEON) for the flood event data.
