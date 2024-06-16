# Shaft Diameter Estimation from Stereo Images

## Overview
This repository contains MATLAB scripts and utilities for estimating the diameter of cylindrical shafts from stereo images. The project applies advanced image processing techniques including depth mapping, circle fitting, and 3D reconstruction to accurately measure shaft dimensions.

## Features
- **Depth Map Analysis**: Generate and analyze depth maps from stereo images to locate the shaft within the images.
- **Circle Fitting**: Utilize nonlinear least squares optimization to fit circles to the projected 2D data points of the shaft.
- **3D Point Cloud Visualization**: Convert depth maps into 3D point clouds for detailed geometric analysis.
- **Measurement Uncertainty**: Calculate and report the measurement uncertainties using standard deviation of the residuals from circle fitting.

## Repository Structure
- `src/` - Contains all the MATLAB scripts and function files.
- `data/` - Directory for storing sample stereo images and output data files.
- `docs/` - Additional documentation and images for the project.
- `README.md` - Overview and usage instructions for the project.

## Getting Started
To run the scripts in this repository, you will need MATLAB installed on your computer. Clone the repository:
```bash
git clone https://github.com/Eins51/3D-Reconstruction.git
```
Open MATLAB and run the script to start the analysis:
```bash
run task3.mlx
```

## Visualizations
The project includes several visualizations to aid in understanding the process and results:
1. Depth histograms for selecting depth thresholds.
2. 2D projections with fitted circles.
3. 3D point cloud visualizations of the shaft.
