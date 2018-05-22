Tutorial 5: Configuration file and custom configurations
==========

**PhysioZoo software**
----------------------

**PhysioZoo** enables you to work with HRV data from different mammals and at different level of integration (i.e. with electrocardiogram, electrogram and action potential data). Since the beating rate and variability pattern varies across species and level of integration then some parameters of the time, frequency and nonlinear based HRV measures must be adjusted.

In the current version of the software these adaptations are already made for the processing of human, dog, rabbit and mouse electrocardiographic data. For processing data from other species or at other levels of integration (electrogram/action potential) you will need to define your own configuration file.

**Specifying a configuration**
Under the “Record” tab you can change the Mammal type to one of the following options: Human, Dog, Rabbit, Mouse and Custom. In built in the software are configuration files for human, dog, rabbit and mouse electrocardiographic data. The “Custom” option enables you to load a Configuration file of your own.

.. image:: ../../_static/select_mammal_type.png

**Modifying the configuration**
If you want to modify some of the HRV measures configuration then you can easily do so with **PhysioZoo** by going to the “Options” menu (see screen below.) There you will find all the parameters of the HRV measures sorted with respect to their category: Time, Frequency and Nonlinear.

If, as an example, you want to change the cut-off frequency between the low frequency and high frequency bands (“LF Band” and “HF Band”) in the frequency based methods then you can do so by changing the 0.341 Hz (see screen below) value to something else more suited to your data.

.. image:: ../../_static/change_config.png

**Exporting a configuration file**
If you have changed the configuration for the analysis of your data and you want to save this configuration for future use then you can do it by clicking on: File -> Save Config File. You can load this configuration file on later use by following the steps from the example Specifying a configuration.


**PhysioZoo library**
---------------------
[TODO]
