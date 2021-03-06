# Webinar_SpatialVectorProcessing_20201202
This repository provides the presentation and demonstration files for the "Spatial Vector Processing with R" webinar, delivered on December 2, 2020 (https://cshs.cwra.org/cshs-hydrology-spatialprocessing/).

## Installation of packages
Prior to the webinar, please run the following script in R to install the required packages for the webinar.

``` r
install.packages('bcmapsdata', repos='https://bcgov.github.io/drat/')
package_list <- c("dplyr","sf","magrittr","tidyr","ggplot2","knitr",
                  "ggspatial","here","raster","bcmaps","rnaturalearth",
                  "rgeos")
install.packages(package_list)
```

## Register for the webinar
Please register for this webinar may be found here. https://cshs.cwra.org/cshs-hydrology-spatialprocessing/

## Rewatch the webianr
Webinar recordings and upcoming webinars from CSHS may be found on the [CSHS Webinars page](https://cshs.cwra.org/webinars/).
