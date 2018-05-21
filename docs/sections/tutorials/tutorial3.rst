Tutorial 3: Preprocessing
==========

When loading the R-peak time series in the HRV module, one of the parameters you need to set is the preprocessing method.
A preprocessing step is usually performed in HRV analysis to filter out suspected ectopic beats, missed beats and artifacts. We implemented in PhysioZoo three methods (and one combination of methods) for pre-filtering the RR-interval:

  * Range, 
  * Moving average,
  * Quotient,
  * Combined (the combination of the Range and the Moving Average filters).
  
You can select the preprocessing filter with the dropdown: Main -> Preprocessing.

You can vary the level of preprocessing by using the dropdown: Main -> Preprocessing level. Three levels of preprocessing are available: Weak, Moderate and Strong. If you want to customize the preprocessing filters then you can access each of the parameters of each filter by going to Options -> Filtering.


