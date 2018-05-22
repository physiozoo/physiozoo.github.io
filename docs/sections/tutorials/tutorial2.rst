Tutorial 2: Signal quality annotations
==========

In this tutorial you will learn how to perform signal quality annotations using **PhysioZoo** and how to use these for your analysis.


**Introduction**
----------------------

**PhysioZoo** allows you to annotate and load signal quality annotations which contains time intervals with quality annotations made based on the electrophysiological signal or beating interval time series. The annotations highlight parts of the RR time series which are not to be trusted because the ECG was of bad quality and the peak detector might have failed in estimating the heart rate within these intervals or just because you want to exclude these segments because they correspond to some transition period during drug injection and so you decide to label this time period as ‘bad quality’.

It is important to note that it is likely that local bad quality data (as in the example given later) will be 'cleaned up' by the prefiltering step (green time series) and so one should not worry about it too much. The signal quality annotations are more useful when a 'large' section of the recording is of bad quality in which case the prefiltering step will be useless. Analysing such sections with large segments of bad quality data will provide meaningless results - the signal quality annotations are useful to prevent that.

**PhysioZoo software**
----------------------

**Making signal quality annotations**

[TO DO WHEN DONE IN MODULE 1]


**Using signal quality annotations**

When using a recording for which you have performed signal quality annotations, you can load at any time the signal quality annotations: Open -> Open Data Quality File. 

After the quality annotations are loaded, you will see green and red bar appearing on the top of the RR interval time series figure. The part in green correspond to good quality data (i.e. data which analysis can be trusted) and the part in red correspond to bad quality data (i.e. data which should not be trusted.) In addition, the RR time series is highlighted in red for the intervals which are indicated as bad quality.



.. image:: ../../_static/quality_annotations_eg.png


**PhysioZoo library**
---------------------

[TODO]
