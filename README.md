# CalEnviroScreen 4.0 Analysis

This is the project repository for my class project for CYPLAN 290: Climate Justice.

## Setting up the environment

You will need to have Python 3.7.x or newer installed to run these notebooks and to set up the conda environment. You will also need to install Anaconda or Miniconda to set up the virtual environment. 

Clone this repository to your local machine and activate conda. Run `conda create --name <env> --file cj-env.txt` (where `<env>` is what you want to name the environment) from within the repository folder to clone the conda environment for this project. If that doesn't work, you can manually install the packages either from the Anaconda program or on the command line. 

The packages used in this project are:
- `jupyter` for running Jupyter notebooks 
- `numpy` and `pandas` for data analysis
- `geopandas`, `esda`, and `libpysal` for spatial data analysis
- `matplotlib` and `seaborn` for data visualizations
- `contextily` for adding tiled basemaps to maps
- `matplotlib_scalebar` for adding scalebars to maps

## Project Setup

