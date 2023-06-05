[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/mhweber/ICRW8_Geospatial_Workshop/HEAD)

# ICRW8_Geospatial_Workshop
Material for the 'Working with Geospatial Hydrologic Data for Watershed Analyses in R and Python Using Web Services' ICRW8 Workshop

## Getting Started

### R
For working with R, you can use [RStudio](https://www.rstudio.com/) and you will need the following libraries installed:

```r
library(remotes)
library(sf)
library(lwgeom)
library(ggplot2)
library(jsonlite)
library(httr)
library(data.table)
library(dplyr)
library(readr)
library(knitr)
library(rnaturalearth)
library(stringr)
library(osmdata)
library(mapview)
library(dataRetrieval)
library(terra)
library(raster)
library(stars)
library(remotes)
library(elevatr)
remotes::install_github("mhweber/awra2020spatial")
library(awra2020spatial)
remotes::install_github("mhweber/Rspatialworkshop")
library(Rspatialworkshop)
remotes::install_github("mikejohnson51/AOI")
#hydroloom
remotes::install_github("DOI-USGS/nhdplusTools@2cb81da"
library(hydroloom)
library(AOI)
library(terrainr)
#StreamCatTools
remotes::install_github("USEPA/StreamCatTools")
library(StreamCatTools)
#nwmTools
remotes::install_github("mikejohnson51/nwmTools")
library(nwmTools)
library(cowplot)
# zonal
# remotes::install_github("NOAA-OWP/zonal")
library(zonal)

```

### Python
For running Python notebooks you can use a combination of
[Miniforge](https://github.com/conda-forge/miniforge) or [Mambaforge](https://github.com/conda-forge/miniforge) and [Jupyter Lab](https://jupyter.org/) or other IDE. 


After installing`miniforge` or `mambaforge` you can create a Python environment as follows:

```bash
git clone https://github.com/mhweber/ICRW8_Geospatial_Workshop && \
cd ICRW8_Geospatial_Workshop && \
conda env create -f environment.yml
```
or

```bash
git clone https://github.com/mhweber/ICRW8_Geospatial_Workshop && \
cd ICRW8_Geospatial_Workshop && \
mamba env create -f environment.yml
```

Now a new environment called `icrw8` is created that can be loaded from your IDE.
You can also use the Binder service by clicking on the Binder badge above to launch a Jupyter Lab instance with all the required Python libraries installed.

## Resources

Here is a list of some useful geospatial tools and resources:

### General
 * [Awesome Geospatial](https://github.com/sacridini/Awesome-Geospatial)

### R
* [Hydroinformatics in R](https://vt-hydroinformatics.github.io/):
    Extensive Notes and exercises for a course on data analysis techniques in hydrology using the programming language R
* [Spatial Data Science by Edzar Pebesma and Roger Bivand](https://r-spatial.org/book/)
* [Geocomputation with R](https://r.geocompx.org/)
* [r-spatial](https://github.com/r-spatial): Suite of fundamental packages for working with spatial data in R
* [Working with Geospatial Hydrologic Data Using Web Services (R)](https://mikejohnson51.github.io/IOW2022_R/slides.html)
* [Accessing REST API (JSON data) using httr and jsonlite](https://rstudio-pubs-static.s3.amazonaws.com/480665_ba2655419209496dbb799f1c7d050673.html)

### Python
* [Datashader](https://datashader.org/):
    Accurately render even the largest data
* [GeoPandas](https://geopandas.org/en/stable/index.html)
* [HyRiver](https://docs.hyriver.io/index.html): a suite of Python packages that provides a unified API for retrieving geospatial/temporal data from various web services
* [leafmap](https://leafmap.org/): A Python package for geospatial analysis and interactive mapping in a Jupyter environment
* [Python Foundation for Spatial Analysis](https://courses.spatialthoughts.com/python-foundation.html)
* [Python for Geographic Data Analysis](https://pythongis.org/index.html)
* [gdptools](https://gdptools.readthedocs.io/en/latest/) A Python package for grid- or polygon-polygon area-weighted interpolation statistics
* [Intro to Python GIS](https://automating-gis-processes.github.io/CSC18/lessons/L2/geopandas-basics.html)
* [xarray](https://xarray.pydata.org/en/stable/): An open-source project and Python package that makes working with labeled multi-dimensional
    arrays simple, efficient, and fun!
* [rioxarray](https://corteva.github.io/rioxarray/stable/index.html): Rasterio xarray extension.
* [GeoPandas](https://geopandas.org/en/stable/):
    An open-source project to make working with geospatial data in python easier.
* [OSMnx](https://github.com/gboeing/osmnx): A Python package that lets you download and analyze geospatial data from OpenStreetMap.
* [Xarray Spatial](https://xarray-spatial.org/master/index.html): Implements common raster analysis functions using `numba` and provides an easy-to-install, easy-to-extend codebase for raster analysis.
