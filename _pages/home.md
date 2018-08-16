---
title: "Welcome to PhysioZoo"
layout: splash
permalink: /

header:
  overlay_color: "#f33"
  overlay_filter: "0.5"
  overlay_image: ""
  cta_label: "Download"
  cta_url: "https://github.com/physiozoo/physiozoo/archive/master.zip"
  caption: ""

excerpt: "Heart Rate Variability analysis of human and animal electrophysiological data"

intro: 
  - excerpt: 'PhysioZoo is a collaborative platform dedicated to the study of the heart rate variability (HRV) in mammals’ electrophysiological recordings.'


feature_row:
  - image_path: "_pages/home_page_interface.png"
    alt: "placeholder image 1"
    title: "PhysioZoo user interface"
    excerpt: 'A user friendly interface to perform Heart Rate Variability analysis.'
    url: "https://physiozoo.readthedocs.io/en/latest/sections/tutorials/pz_installation.html"
    btn_label: "Install"
    btn_class: "btn--primary"

feature_row2:
  - image_path: "_pages/peak_detection.png"
    alt: "placeholder image 1"
    title: "Peak detection"
    excerpt: 'PhysioZoo provides algorithms and a user interface for R-peak detection of mammalian ECG data. In addition, it provides manual annotations tools (peak and data quality) to ensure the reliability of the analyzed data.'
    url: "https://physiozoo.readthedocs.io/en/latest/sections/tutorials/tutorial1.html"
    btn_label: "Read More"
    btn_class: "btn--primary"

feature_row3:
  - image_path: "_pages/Figure_S3.png"
    alt: "placeholder image 1"
    title: "Prefiltering"
    excerpt: 'PhysioZoo includes a number of prefiltering methods in order to remove sudden drop or increase in the beat to beat intervals due to transcient noise or ectopic beats.'
    url: "https://physiozoo.readthedocs.io/en/latest/sections/tutorials/tutorial3.html"
    btn_label: "Read More"
    btn_class: "btn--primary"

feature_row4:
  - image_path: "_pages/Dog_example_qrs_Poincare.png"
    alt: "placeholder image 1"
    title: "HRV measures and data visualization"
    excerpt: 'PhysioZoo includes state of the art HRV measures tailored to the type of mammal that is studied and data visualization features including Poincare plots, power spectrum, distribution of NN intervals, multi scale entropy.'
    url: "https://physiozoo.readthedocs.io/en/latest/sections/tutorials/tutorial4.html"
    btn_label: "Read More"
    btn_class: "btn--primary"
    

---

{% include feature_row id="intro" type="center" %}

{% include feature_row id="feature_row" type="center" width="48" height="48" %}

{% include feature_row id="feature_row2" type="left" width="48" height="48" %}

{% include feature_row id="feature_row3" type="right" %}

{% include feature_row id="feature_row4" type="center" %}
