Electrocardiographic recording
====================

To work with electrophysiological signals they need to be digitized. 
For that purpose both the range and domain need to be digitized.

Sampling rate and quantization level
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
Sampling refers to the process of discretizing the time domain. 
The sampled time domain will be described by the sampling frequency (fs) 
corresponding to the number of samples per second. The resulting digital 
signal will have a discrete domain.

Quantization refers to the process of constraining an input from a continuous 
signal to a discrete set of values. The resulting digital signal will have a discrete range.

The sampling frequency and the quantization that are used will affect the 
quality of the HRV analysis and thus it is important to inspect the raw data 
that are being recorded and eventually, when needed, to adjust the sampling 
frequency and quantization level of the recording device.

Examples below of typical issues
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

.. image:: ../../_static/effect_sampling_frequency.jpg

.. image:: ../../_static/example_quantization.jpg
