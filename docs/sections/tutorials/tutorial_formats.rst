Tutorial: Formats supported in PhysioZoo
==========

In this tutorial you will learn how to prepare your data for their usage in PhysioZoo.


**Introduction**
---------------------

PhysioZoo supports three types of formats: WFDB, text and mat. The text and mat files structures are specific to PhysioZoo whereas the WFDB follows the standard structure of WFDB powered by Physionet (physionet.org). If you are experienced with WFDB then we recommend you use this standard format.

For any of the three formats a file consists of a header and the data:

.. image:: ../../_static/example_header.png

**General structure of the header**
---------------------

For each of the files the following information can be specified in the header:

  * Mammal: dog, mouse, rabbit, human etc.
  * Fs: the sampling frequency in Hertz
  * Integration_Level: electrocardiogram, electrogram or action potential

As part of the header, information characterizing each Channel available can be entered:

  * type: peak, signal quality, time, interval, beating rate and electrography. See definitions of these in the next section
  * name: any name you want to give to the channel
  * unit: millisecond, second, index, bpm, millivolt, microvolt and volt
  * enable: yes or no. If you specify 'no' then this channel will be ignored when the file will be loaded by the PZ Loader. Only specify 'yes' for the channels you want to use.
  
In the case all or part of these information are not specified then you will be prompted to enter it though the PZ Loader (link).

**Channels Type**
---------------------

A Channel can have the following 'type' which will be handled by PhysioZoo:

Annotations
  * peak: the location of the peaks (e.g. R-peak from an ECG time series). The peaks location can be specified in millisecond/second or index.
  * signal quality: annotation on the signal quality. The signal quality annotations can be specified in millisecond/second or index.

Time series
  * time: a time vector giving the position of each sample of another time series. An entry of type 'time' need to be associated with another time series.
  * interval: the time interval between consecutive beats (e.g. RR time series). The interval length can be specified in second/millisecond or index.
  * beating rate: the reciprocal of the interval in units of beats per minute (e.g. heart rate).
  * electrography: the amplitude of an electrography time series (e.g. ECG). The electrography amplitude is given in microvolt, millivolt or volt. Thus only physiological units are allowed.
  
**Headers in the different formats**
------------------------------------------

Text format (.txt)

.. image:: ../../_static/example_header.png

Matlab format (.mat)

A .mat file need to contain the following fields:

.. image:: ../../_static/example_format_matlab_1.jpg

The Channels field is a structure. Each element of the structure will contain the following information:

.. image:: ../../_static/example_format_matlab_2.jpg

WFDB
This need to be redefined.

Example of appropriate structure for a text file; the file is divided in two parts, the 'Header' and the 'Data'.



  
  
