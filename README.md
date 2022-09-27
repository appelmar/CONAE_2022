# Analyzing satellite image collections on public cloud platforms with R

*Workshop materials for CONAE spring school 2022*

Workshop website (including slides and hands-on notebooks): [https://appelmar.github.io/CONAE_2022](https://appelmar.github.io/CONAE_2022).

## Overview

This tutorial demonstrates how to access and process satellite image collections on cloud computing platforms using R and modern cloud-native tools including SpatioTemporal Asset Catalogs, cloud optimized GeoTIFFs, and on-demand data cubes. After a quick introduction and overview of corresponding R packages, practical examples on image compositing, time series analysis, and the extraction of training data for machine learning models will be presented in a live demonstration. The tutorial will end with a discussion of limitations and future developments in R. Materials and further information will be published at https://github.com/appelmar/CONAE_2022.

## Contents

1.  Introduction
    1.  *The* cloud
    2.  Satellite imagery on cloud platforms
    3.  Cloud-native technologies: STAC, COGs, data cubes
    4.  R ecosystem for analyzing satellite imagery
    5.  The gdalcubes R package
2.  Hands-on examples
    1. Computing cloud-free mosaic images from Sentinel-2 images
    2. Time series analysis (trend, changes) using MODIS image time series
    3. Extraction of training data for ML applications from Sentinel-2 images
3.  Discussion
