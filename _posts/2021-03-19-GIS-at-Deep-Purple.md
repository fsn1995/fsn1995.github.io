---
title: "GIS at Deep Purple"
permalink: /posts/2021-03-19-GIS-at-Deep-Purple/
# excerpt: "A GEE toolbox for remote sensing of glaciers"
last_modified_at: 2021-03-20
# classes: wide
categories:
  - coding
  - google earth engine
  - deep purple
  - glaciers
tags:
  - google earth engine
  - GIS
toc: true
---
Make some maps in a simple way. A practical guide for Deep Purple project. 

[Edit on GitHub <img src="https://github.githubassets.com/images/modules/logos_page/GitHub-Mark.png" alt="Edit on GitHub" width="20" height="20"/>](https://github.com/fsn1995/GIS-at-deep-purple)

# 01 Map Greenland

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/fsn1995/GIS-at-deep-purple/blob/main/01%20map%20greenland.ipynb)
[![nbviewer](https://raw.githubusercontent.com/jupyter/design/master/logos/Badges/nbviewer_badge.svg)](https://nbviewer.jupyter.org/github/fsn1995/GIS-at-deep-purple/blob/main/01%20map%20greenland.ipynb)

## scatter plot with open street layer as basemap

<iframe src="https://www.glacier-hub.com/GIS-at-deep-purple/output/01promiceOpenStreetMap.html" height="600px" width="100%" style="border:none;"></iframe>

## scatter plot with satellite data as basemap

<iframe src="https://www.glacier-hub.com/GIS-at-deep-purple/output/01promiceSatellite.html" height="600px" width="100%" style="border:none;"></iframe>

## change map projection

<iframe src="https://www.glacier-hub.com/GIS-at-deep-purple/output/01promiceChangeProjection.html" height="600px" width="100%" style="border:none;"></iframe>

## cartopy projection

<img src="https://github.com/fsn1995/GIS-at-deep-purple/blob/main/output/01%20cartopyProjection.png?raw=true" alt="cartopy projection" width="300" height="300"/>
<img src="https://github.com/fsn1995/GIS-at-deep-purple/blob/main/output/01%20cartopyTerrain.png?raw=true" alt="cartopy projection" width="300" height="300"/>

# 02 Map Greenland on GEE

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/fsn1995/GIS-at-deep-purple/blob/main/02%20gee%20map%20greenland.ipynb)
[![nbviewer](https://raw.githubusercontent.com/jupyter/design/master/logos/Badges/nbviewer_badge.svg)](https://nbviewer.jupyter.org/github/fsn1995/GIS-at-deep-purple/blob/main/02%20gee%20map%20greenland.ipynb)

The map tile generated on GEE will expire after 24h, therefore only screenshot is provided below. However a [webapp deployed on heroku](https://deep-purple-at-gee.herokuapp.com/) is also availble here:
<details>
  <summary>Click to expand!</summary>
  
<iframe src="https://deep-purple-at-gee.herokuapp.com/" height="600px" width="100%" style="border:none;"></iframe>
</details>

## Arctic DEM

<img src="https://github.com/fsn1995/GIS-at-deep-purple/blob/main/output/02%20Arctic%20DEM.png?raw=true" alt="arctic dem" width="300" height="300"/>
<!-- <iframe src="https://www.glacier-hub.com/GIS-at-deep-purple/output/02%20geemapGreenland.html" height="600px" width="100%" style="border:none;"></iframe> -->

## Arctic DEM Terrain palette

<img src="https://github.com/fsn1995/GIS-at-deep-purple/blob/main/output/02%20Arctic%20DEM%20Terrain%20palette.png?raw=true" alt="arctic dem terrain palette" width="300" height="300"/>
<!-- <iframe src="https://www.glacier-hub.com/GIS-at-deep-purple/output/02%20geemapTerrain.html" height="600px" width="100%" style="border:none;"></iframe> -->

## Arctic DEM Contour

<img src="https://github.com/fsn1995/GIS-at-deep-purple/blob/main/output/02%20Arctic%20DEM%20Contour.gif?raw=true" alt="arctic dem contour" width="300" height="300"/>
<!-- <iframe src="https://www.glacier-hub.com/GIS-at-deep-purple/output/02%20geemapContour.html" height="600px" width="100%" style="border:none;"></iframe> -->

This page is still under construction. Welcome to contribute on github.

