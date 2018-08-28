Tutorial 5: Configuration file and custom configurations
==========

In this tutorial you will learn how to create your custom configuration files for R-peak detection and for performing HRV analysis.

**Introduction**
----------------------

**PhysioZoo** enables you to work with HRV data from different mammals. Since the beating rate and variability pattern vary across species then some parameters of the peak detectors and of the time, frequency and nonlinear HRV measures must be adjusted.

In the current version of the software these adaptations are already available for the processing of Human, dog, rabbit and mouse electrocardiographic data. For processing data from other species or if you are using other data than ECG (e.g. electrogram, action potential) you will need to define your own configuration files. There are two types of configuration files in PhysioZoo: peak detection configuration file and HRV configuration file. 

**PhysioZoo software**
----------------------

**Defining an HRV configuration file**
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

Under the “Main” tab you can change the Mammal type to one of the following options: Human, Dog, Rabbit, Mouse and Custom. In built in the software are configuration files for human, dog, rabbit and mouse electrocardiographic data. By choosing thee “Custom” option under `Mammal' you can define an HRV configuration file of your own.

.. image:: ../../_static/select_mammal_type.png


1. By choosing Mammal->Custom this will prompt you with a selection window. Select the configuration file of the closest mammal to the one you want to use. This will set the default HRV configuration parameters.

2. Modify some of the HRV measures configuration by going to the “Options” menu (see screenshot below.) There you will find all the parameters of the HRV measures sorted with respect to their category: Time, Frequency and Nonlinear as well as the Preprocessing parameters. If, as an example, you want to change the cut-off frequency between the low frequency and high frequency bands (“LF Band” and “HF Band”) in the frequency based methods then you can do so by changing the 0.341 Hz (see screen below) value to something else more suited to your data.

3. Go to File->Save config file and save the configuration file under the name of the mammal you are using.

4. To use this configuration file when you next use **PhysioZoo** you can: (1) File->Load custom config file or (2) Main->Mammal->Custom and choose your configuration file.

.. image:: ../../_static/change_config.png

**Exporting a configuration file**
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

If you have changed the configuration for the analysis of your data and you want to save this configuration for future use then you can do it by clicking on: File -> Save Config File. You can load this configuration file on later use by following the steps from the example Specifying a configuration.


**PhysioZoo library**
---------------------
[TODO]
