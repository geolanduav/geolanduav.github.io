---
Title: "GIS with R"
Author: "JFC"
date: "26 November 2019"
output:
  html_document:
    toc: TRUE
    toc_depth: 3
---



# GIS & Spatial Analysis with R #
## ...A Glimpse of what is possible ##
&nbsp;


### PACKAGES ###

[`shapefiles`: Read and Write ESRI Shapefiles](https://cran.r-project.org/package=shapefiles) **_Outdated 2013-01-26 !!_**

``` 
library(sp) # vector data

library(raster) # raster data

library(rgdal) # input/output, conversions, projections & more!

library(gdalUtils)

library(rgeos) # geometry operations
```

[`getSpatialData`](https://github.com/16EAGLE/getSpatialData)

`getSpatialData` is an R package in an **early development stage** as for November 2019, that ultimately aims to provide homogeneous function bundles to query, download, prepare and transform various kinds of spatial datasets from open sources, e.g. Satellite sensor data, higher-level environmental data products etc


[`leafpop`](https://rdrr.io/github/r-spatial/leafpop/man/leafpop-package.html)

+ [`leafpop` Documentation Reference (PDF)](https://cran.r-project.org/web/packages/leafpop/leafpop.pdf)


[`RgoogleMaps`](https://www.rdocumentation.org/packages/RgoogleMaps/versions/1.4.3)

+ [`GetMap` download a static map from the Google server](https://www.rdocumentation.org/packages/RgoogleMaps/versions/1.4.3/topics/GetMap)

+ [`MapBackground` get static Map from the Google server](https://www.rdocumentation.org/packages/RgoogleMaps/versions/1.4.3/topics/MapBackground)


`Maptools`

+ [`Maptools` Package Documentation (PDF)](https://cran.r-project.org/web/packages/maptools/maptools.pdf)

+ [`Maptools` HTML Documentation](https://www.rdocumentation.org/packages/maptools/versions/0.9-8)


`leaflet`

+ [Base maps](https://rstudio.github.io/leaflet/basemaps.html)
  
  - [leaflet providers preview](http://leaflet-extras.github.io/leaflet-providers/preview/index.html)

+ [markers](https://rstudio.github.io/leaflet/markers.html)

+ [popups & labels](https://rstudio.github.io/leaflet/popups.html)


[`mapview` Interactive viewing of spatial data in R](https://r-spatial.github.io/mapview/)

**mapview** provides functions to very quickly and conveniently create interactive visualisations of spatial data. It was created to fill the gap of quick (not presentation grade) interactive plotting to examine and visually investigate both aspects of spatial data, the geometries and their attributes.

  1. [mapview basics](https://r-spatial.github.io/mapview/articles/articles/mapview_01-basics.html)

  2. [mapview advanced controls](https://r-spatial.github.io/mapview/articles/articles/mapview_02-advanced.html)

  3. [mapview options](https://r-spatial.github.io/mapview/articles/articles/mapview_03-options.html)

  4. [mapview popups](https://r-spatial.github.io/mapview/articles/articles/mapview_04-popups.html)
      
      + [popupImage](https://www.rdocumentation.org/packages/mapview/versions/1.2.0/topics/popupImage)

Other Resources for `mapview`: <https://www.rdocumentation.org/packages/mapview/versions/2.7.0>


&nbsp;

##### **_R Base Functions for Analysis of Spatial Data_** #####

+ [***CRAN Task View:*** Analysis of Spatial Data](https://cran.r-project.org/web/views/Spatial.html)

+ [***CRAN Task View:*** Handling and Analyzing Spatio-Temporal Data](https://cran.r-project.org/web/views/SpatioTemporal.html)


&nbsp;

#### Tutoriales & Courses ####

+ [Spatial Cheatsheet](https://www.maths.lancs.ac.uk/~rowlings/Teaching/UseR2012/cheatsheet.html)

+ [r-spatial](https://www.r-spatial.org/)

+ [Introduction to Geospatial Raster and Vector Data with R](https://datacarpentry.org/r-raster-vector-geospatial/01-raster-structure/index.html)

+ [An Introduction GIS with R](https://www.jessesadler.com/post/gis-with-r-intro/)

+ [GIS MApping in R](http://remi-daigle.github.io/GIS_mapping_in_R/)

+ [R GIS Tutorial](http://pakillo.github.io/R-GIS-tutorial/)

+ [stilt-footprint-map-example.r](https://gist.github.com/benfasoli)

+ [Mapping street art in Athens with leaflet and R](https://peerchristensen.netlify.com/post/mapping-street-art-with-leaflet-and-r/)

+ [Handling Spatial Data in R - #1. Getting started](http://www.ecologi.st/post/2017-04-01-primerspatialdata/)

+ [Handling Spatial Data in R - #2. A practical example](http://www.ecologi.st/post/spatial-data-in-r-2-a-practical-example/)

+ [Handling Spatial Data in R - #3. Big Data and Memory Management](http://www.ecologi.st/post/big-spatial-data/)

+ Modis and Landsat primer from [**Google Earth Egine (GEE)**](https://earthengine.google.com/) [here](http://www.ecologi.st/post/modis-primer-for-hannah/)

&nbsp;

#### Books ####

+ [**Spatial Data Science**](https://keen-swartz-3146c4.netlify.com/)

+ [**Geocomputation with R**](https://geocompr.robinlovelace.net/)

&nbsp;

#### HOW TO's & Recipes ####

+ [Convert a spatialpolygon to a SpatialPolygonsDataFrame and add a column to the attribute table](https://gis.stackexchange.com/questions/141469/how-to-convert-a-spatialpolygon-to-a-spatialpolygonsdataframe-and-add-a-column-t)

+ [Explore Shapefile Attributes & Plot Shapefile Objects by Attribute Value in R](https://www.neonscience.org/dc-shapefile-attributes-r)

+ [Plotting Data points on a Map](http://www.milanor.net/blog/maps-in-r-plotting-data-points-on-a-map/)

+ [Image in R Leaflet marker popups](https://stackoverflow.com/questions/36433899/image-in-r-leaflet-marker-popups)

+ [Add a pop-up with an image to a leaflet map in R](http://gabrielamathieu.info/post/2015-07-23-r-rmarkdown/)

&nbsp;

#### MAPS QUICK START ####

[A quick Start to Maps in R](https://medium.com/fastah-project/a-quick-start-to-maps-in-r-b9f221f44ff3)

[Calculate Distance between two addresses using Bing Maps API](https://www.reddit.com/r/Rlanguage/comments/9whzv2/is_there_an_r_package_that_would_calculate_the/)

[Bubble Maps](https://www.rdocumentation.org/packages/RgoogleMaps/versions/1.4.3/topics/bubbleMap)

