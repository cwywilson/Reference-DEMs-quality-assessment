# Glacier Elevation Change Analysis in Auyuittuq National Park (1959–2023)

This repository contains a Jupyter Notebook for quantifying glacier elevation change over time using geospatial data in Auyuittuq National Park, Canadian Arctic. The analysis compares glacier outlines and ArcticDEM elevation models from 1959 and 2023 to compute surface elevation changes and visualize glacier retreat or thinning.

## 🧊 Project Objective

- Compare historical and recent glacier outlines
- Load and clip ArcticDEM to glacier extents
- Compute elevation difference over glacierized areas
- Visualize the spatial pattern of glacier surface change
- Calculate summary statistics of glacier elevation change

## 📂 Files

- `ANPDEMdifff.ipynb`: Main analysis notebook
- `Fountain1959.shp`: Historical glacier outline (1959)
- `Fountain2023.shp`: Modern glacier outline (2023)
- `SNPArcticDEM.tif`: ArcticDEM raster used for elevation analysis

## 📦 Dependencies

Make sure you have the following Python libraries installed:

- `geopandas`
- `rasterio` and `rioxarray`
- `matplotlib`
- `numpy`
- `xarray`

You can install them via pip:

```bash
pip install geopandas rasterio rioxarray matplotlib numpy xarray
