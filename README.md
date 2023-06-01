[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/mhweber/ICRW8_Geospatial_Workshop/HEAD)

# ICRW8_Geospatial_Workshop
Material for the 'Working with Geospatial Hydrologic Data for Watershed Analyses in R and Python Using Web Services' ICRW8 Workshop

## Getting Started

For working with R, you can use [RStudio](https://www.rstudio.com/) and you will
need the following libraries installed:

```r
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
library(stars)
library(remotes)
library(elevatr)
remotes::install_github("mhweber/awra2020spatial")
library(awra2020spatial)
remotes::install_github("mhweber/Rspatialworkshop")
library(Rspatialworkshop)
# remotes::install_github("mikejohnson51/AOI")
library(AOI)
library(terrainr)
remotes::install_github("USEPA/StreamCatTools")
```
