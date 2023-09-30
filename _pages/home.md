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
      url: "https://github.com/physiozoo/physiozoo/archive/v1.6.8.zip"    
    - label: '<i class="fas fa-newspaper"></i> Download Examples'
      url: "https://github.com/physiozoo/Examples/archive/v1.6.7.zip"   
    - label: '<i class="fas fa-cogs"></i> Download Installer'
      url: "https://github.com/physiozoo/physiozoo/releases/download/v1.6.8/PhysioZooInstaller_1_6_7.exe"

excerpt: "Continuous physiological time series analysis from Human and other mammals"

intro: 
  - excerpt: 'PhysioZoo is a collaborative platform dedicated to the study of
        continuous physiological time series analysis from Human and other mammals.'

feature_row:
  - image_path: "assets/images/home_page_interface.png"
    alt: "placeholder image 1"
    title: "PhysioZoo user interface"
    excerpt: 'A user friendly interface to perform Heart Rate Variability analysis.'
    url: "https://docs.physiozoo.com/en/stable/index.html"
    btn_label: "Install"
    btn_class: "btn--primary"
    
peak_detection:
  - image_path: "assets/images/peak_detection.png"
    alt: "placeholder image 1"
    title: "Peak detection"
    excerpt: 'PhysioZoo HRV provides algorithms and a user interface for R-peak detection of mammalian ECG data. In addition, it provides manual annotations tools (peak and data quality) to ensure the reliability of the analyzed data.'
    url: "https://docs.physiozoo.com/en/stable/sections/tutorials/peakdetection.html"
    btn_label: "Read More"
    btn_class: "btn--primary"

prefiltering:
  - image_path: "assets/images/Figure_S3.png"
    alt: "placeholder image 1"
    title: "Prefiltering"
    excerpt: 'PhysioZoo HRV includes a number of prefiltering methods in order to remove sudden drop or increase in the beat to beat intervals due to transient noise or ectopic beats.'
    url: "https://docs.physiozoo.com/en/stable/sections/tutorials/preprocessing.html"
    btn_label: "Read More"
    btn_class: "btn--primary"

hrv_measures:
  - image_path: "assets/images/Dog_example_qrs_Poincare.png"
    alt: "placeholder image 1"
    title: "HRV measures and data visualization"
    excerpt: 'PhysioZoo includes state of the art HRV measures tailored to the type of mammal that is studied and data visualization features including Poincare plots, power spectrum, distribution of NN intervals and multi scale entropy plot.'
    url: "https://docs.physiozoo.com/en/stable/sections/tutorials/hrvanalysis.html"
    btn_label: "Read More"
    btn_class: "btn--primary"


desat_detection:
  - image_path: "assets/images/desat_detection.png"
    alt: "placeholder image 1"
    title: "Desaturation detection"
    excerpt: 'PhysioZoo SPO2 provides algorithms for detecting oxygen desaturations in continuous oximetry time series as well as visualization tools delimiting the beginnings and ends of the detected desaturations.'
    url: "https://oximetry-toolbox.readthedocs.io/en/latest/"
    btn_label: "Read More"
    btn_class: "btn--primary"

prefiltering_obm:
  - image_path: "assets/images/prefiltering_obm.png"
    alt: "placeholder image 1"
    title: "Prefiltering"
    excerpt: 'PhysioZoo SPO2 includes a number of prefiltering methods that can be used to remove sudden drop or increase in the oximetry time series due to transient noise or other technical issues.'
    url: "https://oximetry-toolbox.readthedocs.io/en/latest/"
    btn_label: "Read More"
    btn_class: "btn--primary"

data_visualization:
  - image_path: "assets/images/spo2_vis_example.png"
    alt: "placeholder image 1"
    title: "OBM measures and data visualization"
    excerpt: 'PhysioZoo SPO2 includes a set of oximetry digital biomarkers broadly divided into five categories: general statistics, complexity, periodicity, desaturations and hypoxic burden'
    url: "https://oximetry-toolbox.readthedocs.io/en/latest/"
    btn_label: "Read More"
    btn_class: "btn--primary"

waveform_delineator:
  - image_path: "assets/images/fiducials.png"
    alt: "placeholder image 1"
    title: "ECG waveform delineator"
    excerpt: 'PhysioZoo ECG provides algorithms for detecting fiducial points in continuous ECG time series.'
    url: "https://pecg.readthedocs.io/en/latest/"
    btn_label: "Read More"
    btn_class: "btn--primary"

measures_data_visualization:
  - image_path: "assets/images/violin plot _ quality control.png"
    alt: "placeholder image 1"
    title: "ECG measures and data visualization"
    excerpt: 'PhysioZoo ECG includes a set of electrocardiogram digital biomarkers broadly divided into two categories: (1) interval and segments and (2) waves characteristics.'
    url: "https://pecg.readthedocs.io/en/latest/"
    btn_label: "Read More"
    btn_class: "btn--primary"


PPG_sample:
  - image_path: "assets/images/PPG_sample.png"
    alt: "PPG"
    title: "PPG Toolbox"
    excerpt: 'The pyPPG toolbox is designed for the analysis of finger photoplethysmogram (PPG) signals, offering a range of features such as robust beat 
               detection, precise fiducial point identification, and a comprehensive evaluation of standard biomarkers.'
    url: "https://pyppg.readthedocs.io/en/latest/tutorials/PZ_PPG.html"
    btn_label: "Read More"
    btn_class: "btn--primary"

PPG_FP:
  - image_path: "assets/images/PPG_FP - PZ.png"
    alt: "PPG_FP"
    title: "PPG Fiducial Points"
    excerpt: 'The pyPPG toolbox provides the extraction of 15 fiducial. The fiducial points of the PPG signal include the systolic peak (sp), the pulse onset and               offset (on, off), the dicrotic notch (dn), and the diastolic peak (dp). The fiducial points of PPG derivatives are represented by u, v, w, a, b, c, 
              d, e, f, p1, p2. The biomarkers are calculated based on this set of fiducial points.'
    url: "https://pyppg.readthedocs.io/en/latest/tutorials/PZ_PPG.html"
    btn_label: "Read More"
    btn_class: "btn--primary"


PPG_BM:
  - image_path: "assets/images/PPG_BM.png"
    alt: "PPG_BM"
    title: "PPG Biomarkers"
    excerpt: 'The pyPPG toolbox includes a comprehensive collection of 74 standard PPG morphological biomarkers which are calculated from the timings and 
              amplitudes of the fiducial points. The biomarkers were categorized into four groups: (1) PPG Signal; (2) Signal Ratios; (3) PPG Derivatives; and 
              (4) Derivatives Ratios. For PPG analysis 9 statistical measurements are provided for each biomarker.'
    url: "https://pyppg.readthedocs.io/en/latest/tutorials/PZ_PPG.html"
    btn_label: "Read More"
    btn_class: "btn--primary"
    
---

{% include feature_row id="intro" type="center" %}

{% include video provider="youtube" id="JkE2FUSlq2g" %}

## News
* 2022-10-01: [PhysioZoo `v1.6.8`](https://github.com/physiozoo/physiozoo/releases/tag/v1.6.8)
    PPG toolbox released.
* 2022-06-08: [PhysioZoo `v1.6.7`](https://github.com/physiozoo/physiozoo/releases/tag/v1.6.7)
    pecg toolbox released.
* 2022-03-04: [PhysioZoo `v1.6.4`](https://github.com/physiozoo/physiozoo/releases/tag/v1.6.4)
    released.
* 2021-03-16: [PhysioZoo `v1.5.9`](https://github.com/physiozoo/physiozoo/releases/tag/v1.5.9)
    released.
* 2018-09-06: [PhysioZoo `v1.0.0`](https://github.com/physiozoo/physiozoo/releases/tag/v1.0.0)
    is now publicly available!

<br/>

# PhysioZoo HRV

PhysioZoo HRV is a collaborative platform dedicated to the study of the heart rate variability (HRV) from Humans and other mammals’ electrophysiological recordings.

<!-- {% include feature_row id="feature_row" type="center" %} -->

{% include feature_row id="peak_detection" type="left" %}

{% include feature_row id="prefiltering" type="right" %}

{% include feature_row id="hrv_measures" type="left" %}

<br/>

# PhysioZoo ECG

PhysioZoo ECG is a collaborative platform dedicated to the study of digital electrocardiography biomarkers
to assess cardiac conduction.

{% include feature_row id="waveform_delineator" type="left" %}

{% include feature_row id="measures_data_visualization" type="right" %}

<br/>

# PhysioZoo SPO2

PhysioZoo SPO2 is a collaborative platform dedicated to the study of oximetry digital biomarkers (OBM) analysis from Human continuous oximetry (SpO2) time series.

{% include feature_row id="desat_detection" type="left" %}

{% include feature_row id="prefiltering_obm" type="right" %}

{% include feature_row id="data_visualization" type="left" %}

<br/>

# PhysioZoo PPG

PhysioZoo PPG is a collaborative platform dedicated to the study of digital photoplethysmography biomarkers
to assess cardiac conduction.

{% include feature_row id="PPG_sample" type="right" %}

{% include feature_row id="PPG_FP" type="left" %}

{% include feature_row id="PPG_BM" type="right" %}
