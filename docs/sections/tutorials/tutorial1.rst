Peak detection
==============

In this tutorial you will learn how to load an electrocardiogram (ECG) recording and perform R-peak detection. You will also learn how to manually correct miss-detections.

**Introduction**
---------------------
Accurate peak detection is critical for performing a meaningfull HRV analysis. Numerous algorithms for finding R-peaks in the Human ECG signal have been developped. However, these need to be adapted to the different dynamic accross mammalian species. **PhysioZoo** builds on the reference open source **gqrs** peak detector to provide an accurate R-peak detector **rqrs** which can be used on different mammalian ECG data.


**Performing peak detection**
-----------------------------

  1. Open PhysioZoo  

  2. Click "Peak Detection" on the Menu bar to open the peak detection interface.
  
  3. Load an ECG recording (e.g. File -> Open File -> Rabbit_example.txt). The ECG will be displayed. The R-peak detector will run automatically. You will see some red crosses appearing on the ECG signal at the locations that have been detected (pannel A).

  4. You can browse through the recording by stretching and moving the red window displayed in pannel B. You can also move through the recording by using the arrows circled in red on the right hand side.

.. image:: ../../_static/peak_detection_fig1.png

**IMPORTANT**: The input ECG data imported in **PhysioZoo** MUST be in mV (i.e. physiological units). The R-peak detector might not run appropriately if the data are not correctly scaled.


**Manual peak correction**
-----------------------------
Sometime the R-peak detector might make mistakes and miss some R-peaks/detect some points which are not peaks. You can fix these mistakes manually using the **PhysioZoo** interface by using the following functionalities:

  1. Select a part of the ECG which is noisy and where some peaks were misdetected.

  2. Point your cursor on a misdetected peak or at the location where a peak is missing. When you click, **PhysioZoo** will automatically remove/add a peak at this location.
  
  3. If a whole segment contains misdetection and you need to clear all the peaks within this section then you can do that by drawing a rectangle on the area where you want the peaks to be deleted (see dotted rectangle figure bellow). When you drop the rectangle, all the peaks contained within it will be deleted.
  
  4. Save your R-peak time series: File -> Save Peaks.

.. image:: ../../_static/peak_detection_fig2.png


**Configuration for other mammals**
----------------------------------
The **PhysioZoo** R-peak detector is readily adapted for humans, dogs, rabbits and mice ECG data. If you need to use it on another specie then you will need to adapt its parameters accordingly. The parameters for the peak detector can be found under the "Config Params" tab.

.. image:: ../../_static/peak_detection_fig3.png

where,

- HRm: Typical heart rate (beats/min)

- QSm: Typical QRS duration (sec)

- QT: Typical QT interval duration (sec)

- RRmin: Minimum RR interval ("refractory period", sec)

- RRmax: Maximum RR interval (sec)

- QRSa: Typical QRS peak-to-peak amplitude (microVolt)

- QRSamin: Minimum QRS peak-to-peak amplitude (microVolt)

..  3. Select the type of mammal the ECG was recorded from. This can be done by choosing the mammal type in the dropdown menu "Mammal".    After selecting the mammal type, the R-peak detector will run automatically. After the R-peak detector has finished running you will see some red crosses appearing on the ECG signal at the locations that have been detected.
