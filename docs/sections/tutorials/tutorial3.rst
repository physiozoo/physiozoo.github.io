Preprocessing
==========

In this tutorial you will learn how to preprocess your RR time series. The resulted preprocessed time series is usually called the 'NN' time series.

**Introduction**
----------------------

When loading the R-peak time series in the HRV module, one of the parameters you need to set is the preprocessing method.
A preprocessing step is usually performed in HRV analysis to filter out suspected ectopic beats, missed beats and artifacts.

We implemented in **PhysioZoo** three methods (and one combination of methods) for pre-filtering the RR-interval:

  * Range, 
  * Moving average,
  * Quotient,
  * Combined (the combination of the Range and the Moving average filters).

**Preprocessing methods**
----------------------
  
You can select the preprocessing filter with the dropdown: Main -> Preprocessing.

You can vary the level of preprocessing by using the dropdown: Main -> Preprocessing level. Three levels of preprocessing are available: Weak, Moderate and Strong. If you want to customize the preprocessing filters then you can access each of the parameters of each filter by going to Options -> Filtering.

The image below shows an example of a rabbit RR time (blue time series) series which has been filtered over the selected window (green time series) using the Moving average filter .

.. image:: ../../_static/prefiltering_step.png

