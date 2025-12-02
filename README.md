#  Groundwater Depth Analysis: Pabna District, Bangladesh

##  Project Overview
This project visualizes groundwater level variations in Pabna District, Bangladesh. Using monitoring well data and Python geospatial libraries, I created continuous depth models to identify areas of water depletion.

##  Key Map
![Groundwater Map](Pabna_Fixed_Layout.png)

##  Technical Methodology
- **Interpolation:** Used **Radial Basis Function (RBF)** to predict water levels in unmeasured locations, creating a smooth surface that covers the entire district.
- **Vector-Raster Integration:** Clipped the interpolated data using the official Pabna administrative shapefile for precise boundary masking.
- **Visualization:** Designed professional maps with **Matplotlib**, using custom diverging colormaps, contour lines, and automated labeling of Upazilas.

## How to Run
1. Install dependencies: `pip install geopandas matplotlib scipy numpy`
2. Run the notebook `Groundwater_Analysis.ipynb`.

---
*Author: [Md Sabbir Islam]*
*Data Source: Bangladesh Water Development Board (BWDB)*
