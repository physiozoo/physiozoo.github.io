---
title: "Welcome to PhysioZoo"
layout: splash
permalink: /

header:
  overlay_color: "#fff"
  overlay_filter: "0.3"
  overlay_image: "assets/images/splash2.jpg"
  caption: ""
  actions:
    - label: '<i class="fas fa-laptop-code"></i> Download Source'
      url: "https://github.com/physiozoo/physiozoo/archive/1.2.0.zip"
    - label: '<i class="fas fa-newspaper"></i> Download Examples'
      url: "https://github.com/physiozoo/physiozoo/releases/download/1.2.0/ExamplesTXT.zip"   
    - label: '<i class="fas fa-cogs"></i> Download Installer'
      url: "https://github.com/physiozoo/physiozoo/releases/download/1.2.0/PhysioZoo-1.2.0_Installer.exe"

excerpt: "Heart Rate Variability analysis of human and animal electrophysiological data"

intro: 
  - excerpt: 'PhysioZoo is a collaborative platform dedicated to the study of
        the heart rate variability (HRV) in mammals’ electrophysiological
        recordings.'

feature_row:
  - image_path: "assets/images/home_page_interface.png"
    alt: "placeholder image 1"
    title: "PhysioZoo user interface"
    excerpt: 'A user friendly interface to perform Heart Rate Variability analysis.'
    url: "https://docs.physiozoo.com/en/stable/index.html"
    btn_label: "Install"
    btn_class: "btn--primary"
    
feature_row2:
  - image_path: "assets/images/peak_detection.png"
    alt: "placeholder image 1"
    title: "Peak detection"
    excerpt: 'PhysioZoo provides algorithms and a user interface for R-peak detection of mammalian ECG data. In addition, it provides manual annotations tools (peak and data quality) to ensure the reliability of the analyzed data.'
    url: "https://docs.physiozoo.com/en/stable/sections/tutorials/peakdetection.html"
    btn_label: "Read More"
    btn_class: "btn--primary"

feature_row3:
  - image_path: "assets/images/Figure_S3.png"
    alt: "placeholder image 1"
    title: "Prefiltering"
    excerpt: 'PhysioZoo includes a number of prefiltering methods in order to remove sudden drop or increase in the beat to beat intervals due to transcient noise or ectopic beats.'
    url: "https://docs.physiozoo.com/en/stable/sections/tutorials/preprocessing.html"
    btn_label: "Read More"
    btn_class: "btn--primary"

feature_row4:
  - image_path: "assets/images/Dog_example_qrs_Poincare.png"
    alt: "placeholder image 1"
    title: "HRV measures and data visualization"
    excerpt: 'PhysioZoo includes state of the art HRV measures tailored to the type of mammal that is studied and data visualization features including Poincare plots, power spectrum, distribution of NN intervals and multi scale entropy plot.'
    url: "https://docs.physiozoo.com/en/stable/sections/tutorials/hrvanalysis.html"
    btn_label: "Read More"
    btn_class: "btn--primary"
---

{% include feature_row id="intro" type="center" %}

## News

* 2019-04-15: [PhysioZoo `v1.2.0`](https://github.com/physiozoo/physiozoo/releases/tag/1.2.0)
    released.
* 2018-12-04: [PhysioZoo `v1.1.3`](https://github.com/physiozoo/physiozoo/releases/tag/v1.1.3)
    released.
* 2018-10-25: [PhysioZoo `v1.0.2`](https://github.com/physiozoo/physiozoo/releases/tag/1.0.2)
    released.
* 2018-09-17: [PhysioZoo `v1.0.1`](https://github.com/physiozoo/physiozoo/releases/tag/v1.0.1)
    bugfix release.
* 2018-09-06: [PhysioZoo `v1.0.0`](https://github.com/physiozoo/physiozoo/releases/tag/v1.0.0)
    is now publicly available!

## PhysioZoo Features

{% include feature_row id="feature_row" type="center" %}

{% include feature_row id="feature_row2" type="left" %}

{% include feature_row id="feature_row3" type="right" %}

{% include feature_row id="feature_row4" type="center" %}
