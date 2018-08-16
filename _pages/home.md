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
  - excerpt: 'The PhysioZoo is a collaborative platform dedicated to the study of the heart rate variability (HRV) in mammals’ electrophysiological recordings.'


feature_row:
  - image_path: "_pages/home_page_interface.png"
    alt: "placeholder image 1"
    title: "PhysioZoo user interface"
    excerpt: 'PhysioZoo user interface'
    url: "https://physiozoo.readthedocs.io/en/latest/sections/tutorials/pz_installation.html"
    btn_label: "Install"
    btn_class: "btn--primary"

feature_row2:
  - image_path: "docs/_static/Figure_S3.png"
    alt: "placeholder image 1"
    title: "Peak detection"
    excerpt: 'PhysioZoo provides algorithms and an interface for R-peak detection from mammalian data'
    url: "https://physiozoo.readthedocs.io/en/latest/sections/tutorials/tutorial1.html"
    btn_label: "Read More"
    btn_class: "btn--primary"

feature_row3:
  - image_path: "docs/_static/Figure_S3.png"
    alt: "placeholder image 1"
    title: "Prefiltering"
    excerpt: 'PhysioZoo includes a number of prefiltering methods and manual annotations tools (peak and data quality) to ensure the reliability of the analyzed data.'
    url: "https://physiozoo.readthedocs.io/en/latest/sections/tutorials/tutorial3.html"
    btn_label: "Read More"
    btn_class: "btn--primary"

feature_row4:
  - image_path: "_pages/Dog_example_qrs_Poincare.png"
    alt: "placeholder image 1"
    title: "HRV and Data visualization"
    excerpt: 'PhysioZoo includes traditional HRV measures tailored to the mammal that is studied and data visualization features include Poincare plots, power spectrum, distribution of NN intervals, multi scale entropy and more.'
    url: "https://physiozoo.readthedocs.io/en/latest/sections/tutorials/tutorial4.html"
    btn_label: "Read More"
    btn_class: "btn--primary"
    

---

{% include feature_row id="intro" type="center" width="80%" height="80%" %}

{% include feature_row id="feature_row" type="center" %}

{% include feature_row id="feature_row2" type="left" %}

{% include feature_row id="feature_row3" type="right" %}

{% include feature_row id="feature_row4" type="center" %}
