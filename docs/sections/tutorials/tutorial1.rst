Tutorial 1: R-peak detection
==========

In this tutorial we will learn how to load an electrocardiogram (ECG) recording and performing R-peak detection.

  1. Start the **PhysioZoo** software
  
  2. Load an ECG recording e.g. File -> Open File -> ecg_Rabbit_02_part_4. The ECG will be displayed.
  
  3. Select the type of mammal of the ECG was recorded from. This can be done by choosing the mammal type in the dropdown menu "Mammal".    After selecting the mammal type, the R-peak detector will run automatically. After the R-peak detector has finished running you will see some red crossed appearing on the ECG signal at the locations that have been detected.

  4. Sometime the R-peak detector might make mistakes and miss some R-peaks/detect some points which are not peaks. You can fix these mistakes manually using the **PhysioZoo** interface. You can do that in two ways:
  - point your cursor on a misdetected peak or at the location where a peak is missin. When you click, **PhysioZoo** will automatically remove/add a peak at this location.
  - if a whole segment contains mis-detection and you need to clear all the peaks within this section then you can do that by drowing a rectangle on the area where you want the peaks to be deleted. When you drop the rectangle, all the peaks contained within it will be deleted.
  
  
NOTE: The R-peak detector is adapted for humans, dogs, rabbits and mice. If you need to use it on another specie then you will need to adapt its parameters accordingly. 

IMPORTANT: The ECG data imported in **PhysioZoo** MUST be in mV (i.e. Physiological units.) The R-peak detector might not run appropriately if the data are not correctly scaled.

.. image:: ../../_static/peak_detection.png
