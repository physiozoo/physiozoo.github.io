Tutorial 4: Heart Rate Variability analysis
==========

Start by loading some example data by clicking File -> Open File -> Dog -> qrs_Dog_03. The program will start the analysis and display the following window:

.. image:: ../../_static/hrv_step.png

On the lower figure (A), the RR time series is plotted. Two windows are drawn on it: one window with a red frame and one with a blue frame (and alpha color from within.) The red window defines the part of the RR time series which is plotted on the larger upper figure (B). The blue frame defined the part of the RR time series for which the HRV measures will be computed. On the upper figure (B) the selected window (colored in blue) defines the time interval for which the HRV measures are computed (thus equivalent to the blue window in figure A). The window can be modified (extended/shrank/moved) using the mouse. Pannel (C) shows all the HRV measures that have been computed.

Congrats! You have made your first HRV analysis with PhysioZoo!

NOTE: Every time you move the analysis window to another location the newly selected segment will be automatically analyzed. You can disable this by deselecting the checkbox “Auto Compute” under “Records” in panel 1.

.. image:: ../../_static/warning_sign.jpg
   :height: 100
   :width: 200
   :scale: 50
   :alt: alternate text
The length of the selected window is important. A number of HRV measures assumes that the RR time series is stationary over the selected window. In our context stationary means that the statistical properties of a signal (such as mean and standard deviation) are about constant. Other measures such as the detrended fluctuation analysis measures do not assume stationarity and so a long window can be used.
