Tutorial 2: Signal quality annotations
==========

PhysioZoo allows you to annotate and load signal quality annotations which contains time intervals with quality annotations made based on the electrophysiological signal or beating interval time series. The annotations highlight parts of the RR time series which are not to be trusted because the ECG was of bad quality and the peak detector might have failed in estimating the heart rate within these intervals or just because you want to excluded these segments because they correspond to some transition period between control and drug injection and so you decide to label this time period as ‘bad quality’.

**Making signal quality annotations**

[TO DO]


**Using signal quality annotations**

When using a recording for which you have performed quality annotations, you can load at any time the signal quality annotations: Open -> Open Data Quality File. 

After the quality annotations are loaded, you will see green and red bar appearing on the top of the RR interval time series figure. The part in green correspond to good quality data (i.e. data which analysis can be trusted) and the part in red correspond to bad quality data (i.e. data which should not be trusted.) In addition, the RR time series is highlighted in red for the intervals which are indicated as bad quality.

It is important to note that it is likely that local bad quality data (as in the example below) will be `clearned up' by the prefiltering step (green time series) and so one should not be worried about it. The signal quality annotations are more useful when a 'large' section of the recording is of bad quality in which case the prefiltering step will be useless. For such sections the analysis would be incorrect - the signal quality annotations are useful to indicate that.

.. image:: ../../_static/quality_annotations_eg.png
