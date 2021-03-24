---
# title: "Intro Page"
layout: splash
permalink: /
# date: 2021-01-23T11:48:41-04:00
header:
  overlay_color: "#000"
  overlay_filter: "0.5"
  overlay_image: /assets/images/TarfalaCrop.jpg
#   actions:
#     - label: "Download"
#       url: "https://github.com/mmistakes/minimal-mistakes/"
  caption: "Photo credit: Shuann Feng at Tarfala Research Station 2018"
excerpt: "Study the science of a changing world."
intro: 
  - excerpt: 'Selected Projects'
feature_row:
  - image_path: https://github.com/fsn1995/GIS-at-deep-purple/blob/main/output/02%20Arctic%20DEM%20Contour.gif?raw=true
    alt: "GIS at Deep Purple"
    title: "GIS at Deep Purple"
    excerpt: "GIS at Deep Purple"
    url: "https://www.glacier-hub.com/posts/2021-03-19-GIS-at-Deep-Purple/"
    btn_label: "Read More"
    btn_class: "btn--primary"
  - image_path: assets/gif/iSeeGlacier.gif
    alt: "GEE toolbox for glacier"
    title: "GEE toolbox for glacier"
    excerpt: "GEE toolbox for glaciers"
    url: "https://fsn1995.github.io/posts/GEE-toolbox-for-glacier/"
    btn_label: "Read More"
    btn_class: "btn--primary"
  - image_path: https://www.glacier-hub.com/fsn1995.github.io-OLD/picture/CTS.gif
    alt: "master thesis"
    title: "MSc Thesis"
    excerpt: "Cold Surface Layer Dynamics of Large Glaciers, Northern Sweden 2009-2019"
    url: "https://github.com/fsn1995/cold-surface-layer-dynamics-on-Storglaciaren"
    btn_label: "Read More"
    btn_class: "btn--primary"

feature_row2:
  - image_path: https://www.glacier-hub.com/fsn1995.github.io-OLD/picture/waterDateslider.png
    # image_caption: "Image courtesy of [Unsplash](https://github.com/fsn1995/cold-surface-layer-dynamics-on-Storglaciaren)"
    alt: "fun with GEE"
    title: "fun with GEE"
    excerpt: "Google Earth Engine practice and tools"
    url: "https://fsn1995.github.io/Fun-with-Google-Earth-Engine"
    btn_label: "Read More"
    btn_class: "btn--primary"
  - image_path: https://fsn1995.github.io/Fun-with-Python-for-Geodata/pic/airportconnection.png
    title: "fun with python"
    excerpt: "Personal practices in geodata analysis and interactive visualization with python."
    url: "https://fsn1995.github.io/Fun-with-Python-for-Geodata/"
    btn_label: "Read More"
    btn_class: "btn--primary"
# feature_row3:
#   - image_path: /assets/images/unsplash-gallery-image-2-th.jpg
#     alt: "placeholder image 2"
#     title: "Placeholder Image Right Aligned"
#     excerpt: 'This is some sample content that goes here with **Markdown** formatting. Right aligned with `type="right"`'
#     url: "#test-link"
#     btn_label: "Read More"
#     btn_class: "btn--primary"
# feature_row4:
#   - image_path: /assets/images/unsplash-gallery-image-2-th.jpg
#     alt: "placeholder image 2"
#     title: "Placeholder Image Center Aligned"
#     excerpt: 'This is some sample content that goes here with **Markdown** formatting. Centered with `type="center"`'
#     url: "#test-link"
#     btn_label: "Read More"
#     btn_class: "btn--primary"
---

{% include feature_row id="intro" type="center" %}

{% include feature_row %}

{% include feature_row id="feature_row2" type="center" %}

{% include feature_row id="feature_row3" type="right" %}

{% include feature_row id="feature_row4" type="center" %}