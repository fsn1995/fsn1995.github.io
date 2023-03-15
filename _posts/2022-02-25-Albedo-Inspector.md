---
title: "Albedo Inspector"
permalink: /posts/AlbedoInspector
# excerpt: "A GEE toolbox for remote sensing of glaciers"
last_modified_at: 2023-03-15
classes: wide
categories:
  - coding
  - google earth engine
  - deep purple
  - glaciers
tags:
  - google earth engine
  - GIS
# toc: true
header:
  teaser: "https://github.com/fsn1995/Remote-Sensing-of-Albedo/blob/main/media/geeapp.png?raw=true"
---
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.6257894.svg)](https://doi.org/10.5281/zenodo.6257894)

References:
- <div class="csl-entry">Feng, S., Cook, J. M., Anesio, A. M., Benning, L. G., &#38; Tranter, M. (2023). Long time series (1984–2020) of albedo variations on the Greenland ice sheet from harmonized Landsat and Sentinel 2 imagery. <i>Journal of Glaciology</i>, 1–16. https://doi.org/10.1017/jog.2023.11</div>
- <div class="csl-entry">Feng, S., &#38; Cook, J. M. (2023). <i>Remote-Sensing-of-Albedo: Development of harmonized satellite albedo</i>. Zenodo. https://doi.org/10.5281/zenodo.7642574</div>

# Albedo Inspector
This is a tutorial for the web application - [Albedo Inspector](https://fsn1995.users.earthengine.app/view/albedoinspector). 
It allows users to extract time series of albedo and load the albedo maps freely in browser.
Please note that the manuscript is currently under review.

## 1. Load Data
The time series of albedo can be extracted at any point of interest (poi) by clicking on the map. 
An interactive chart will be displayed in the top left panel and will be updated everytime clicking on a new poi.
The map of both RGB true color composite and albedo can be loaded by selecting time of interest (yyyy-mm-dd). 
A week number is also required to compute the image mosaic. 
This may take a while if the week number is too large. 
A week number of 1 is a good starting point for albedo in July 2014. 
Note that the image is restricted to the current map window. 

<img src="https://github.com/fsn1995/fsn1995.github.io/blob/master/assets/gif/albedoinspectorLoad.gif?raw=true" alt="load map" height="600px" width="100%"/>

## 2. Compare Map
By draging the box under the layers, user may compare the albedo map and the RGB true color composite. 

<img src="https://github.com/fsn1995/fsn1995.github.io/blob/master/assets/gif/albedoinspectorMap.gif?raw=true" alt="compare map" height="600px" width="100%"/>

Large areas in the central Greenland Ice Sheet is blank. This is mainly due to cloud/cloud shaodows mask, L7 ETM+ Scan Line error, data saturation and computational artifacts in the surface reflectance data.

## 3. Export Data
### Export Time Series Data
The time series of albedo is displayed as an interactive chart. 
It can be exported as csv as shown in the gif:

<img src="https://github.com/fsn1995/fsn1995.github.io/blob/master/assets/gif/albedoinspectorData.gif?raw=true" alt="export time series" height="600px" width="100%"/>

### Export Albedo Map
We also support exporting a clip of albedo. 
If the size of current map view window is less than 32MB and grid dimension is smaller than 10000, a button will appear for downloading the albedo map as geotiff format. 
The limitation is due to the [limitation of Google Earth Engine](https://developers.google.com/earth-engine/apidocs/ee-image-getdownloadurl).

<img src="https://github.com/fsn1995/Remote-Sensing-of-Albedo/blob/main/media/geeappdownload.png?raw=true" alt="export time series" height="600px" width="100%"/>


Hope this is helpful to you. Questions and suggesstions are welcomed! 

