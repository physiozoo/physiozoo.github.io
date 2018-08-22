Introduction
************

The **PhysioZoo** platform is an open source project dedicated to the study of
the heart rate variability (HRV) in electrophysiological recordings of humans
and other mammals.  The main components of the platform are:

- *Software*

  - An open-source algorithmic toolbox for matlab (``mhrv``), which implements
    all standard HRV analysis algorithms (and more). This can be used by your
    own data analysis code using it's matlab-like API.
    
  - An open-source graphical user interface (GUI) that allows performing
    advanced multi-window or multi-record HRV analysis of both ECG and
    RR-intervals data in various formats while also exporting results and
    figures. This can be performed easily by non-technical users without writing
    any code.

- *Databases*: A set of annotated databases of electrophysiological signals, both raw
  electrocardiogram and beat-interval time series, from dog, rabbit and mouse.

- *Configuration*
  
  - A set of configuration files that adapt the HRV measures and algorithms to
    work with data from different mammals.
    
  - All HRV measures can be further adapted for the analysis of other mammals by
    creating simple human-readable mammal-specific configuration files.

  
The **PhysioZoo** mission is to standardize and enable the reproducibility of
HRV analysis in mammals’ electrophysiological data. This is achieved through
its open source code, freely available software and open access databases. It
also aims to encourage the scientific community to contribute their
electrophysiological databases and novel HRV algorithms/analysis tools for
advancing the research in the field.

We always welcome your feedback on how to improve the **PhysioZoo** software to
best serve your research needs. Do not hesitate to drop us an email at:
physiozoolab@gmail.com.
