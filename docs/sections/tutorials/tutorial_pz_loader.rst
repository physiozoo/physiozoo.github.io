Tutorial: Importing data in **PhysioZoo**
==========

In this tutorial you will learn how to import data in **PhysioZoo**. 

**Introduction**
---------------------

Data loading in **PhysioZoo** is centralized and done through the PZ Loader tool. Three input formats are supported, refer to the tutorial on formats supported by **PhysioZoo** for more information.

**PZ Loader**
---------------------

Open an example annotation file:

File -> Load data -> Dog_05.qrs

The PZ Loader will appear and display the time series as shown in the example belo:

.. image:: ../../_static/PZ_loader.png

In case some information are missing from the file (e.g. mammal type is not available in the header) then the PZ Loader will request the corresponding fields to be filled by the user. 
When all the fields have been filled then click OK and the data will be open in **PhysioZoo**.

**Saving a file with a header**
---------------------

In the case where you will need to re-load the same file later on then after filling the fields of the PZ Loader you can click 'Save As'. This will save your file in the same format as the original input file but with a header which will contain all the information filled in the PZ Loader. When you will load this file again then you will not need to fill the fields again. 
We will give an example to illustrate that:
First using a text editor open the example file: 

/miscellaneous/PZ_Loader_eg.txt

You will see the following file which consists of a time series. There is no information on what this time series it is and neither its units, sampling frequency etc. 

.. image:: ../../_static/PZ_Loader_eg.PNG

Now load the same example using the PZ Loader:

File -> Open File -> examples -> miscellaneous -> PZ_Loader_eg.txt

This file has no header and you will need to enter the necessary information on the PZ Loader interface. Enter the following information:

  * Integration_level: electrocardiogram
  * Mammal: dog
  * Fs: 500
  * Type: electrography
  * Unit: volt

Then click "Save As" and save the file under the name "PZ_Loader_eg_with_header". Open the text file with a text editor. You will see on your screen the following:

.. image:: ../../_static/PZ_Loader_eg_with_header.PNG

The time series was saved with its header consisting of all the information you entered using the PZ Loader. Next time you will need to load this file you will not need to re-fill the PZ Loader fields. They will be loaded automatically from the header. Check it for yourself!

