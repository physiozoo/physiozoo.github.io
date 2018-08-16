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
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"

feature_row2:
  - image_path: "_pages/Dog_example_qrs_NND.png"
    alt: "placeholder image 1"
    title: "Distribution NN intervals"
    excerpt: 'Example of NN intervals distribution from a dog recording'
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"
    
feature_row3:
  - image_path: "_pages/Dog_example_qrs_PSD.png"
    alt: "placeholder image 1"
    title: "Power spectral analysis"
    excerpt: 'Example of a power spectral density plot obtained from a dog NN time series'
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"
    
feature_row4:
  - image_path: "_pages/Dog_example_qrs_Poincare.png"
    alt: "placeholder image 1"
    title: "Poincare plot"
    excerpt: 'Poincare plot'
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"

---

{% include feature_row id="intro" type="center" %}

{% include feature_row id="feature_row" type="center" %}

{% include feature_row id="feature_row2" type="left" %}

{% include feature_row id="feature_row3" type="right" %}

{% include feature_row id="feature_row4" type="center" %}
