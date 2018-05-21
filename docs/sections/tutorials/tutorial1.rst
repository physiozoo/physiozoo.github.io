Tutorial 1: R-peak detection
==========

In this tutorial we will learn how to load an electrocardiogram (ECG) record and performing R-peak detection.

  1. Start the PhysioZoo software
  
  2. Load an ECG recording by clicking File->Open File. The ECG will be displayed on the screen
  [image showing ECG on interface - need integration of module 1 in module 2]
  
  3. Select the type of mammal of the ECG was recorded from. This can be done by choosing the mammal type in the dropdown menu "Mammal".    After selecting the mammal type, the R-peak detector will run automatically. After the R-peak detector has finished running you will see some red crossed appearing on the ECG signal at the locations that have been detected.
  
  4. Sometime the R-peak detector might make mistakes and miss some R-peaks/detect some points which are not peaks. You can fix these mistakes manually using the PhysioZoo interface.
  
  
NOTE: The R-peak detector is adapted for humans, dogs, rabbits and mice. If you need to use it on another specie then you will need to adapt its parameters accordingly. 

Important: The ECG data imported in PhysioZoo MUST be in mV (i.e. Physiological units.) The R-peak detector might not run appropriately if the data are not correctly scaled.
