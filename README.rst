Welcome to InfeRes: A Python package for inferring reservoir water surfacea area, level and storage volume
============================================================================================================

.. image:: https://img.shields.io/pypi/l/sciris.svg
 :target: https://github.com/ssmahto/InfeRes_test/blob/main/LICENSE

``InfeRes`` is a python package that is designed to help automatic extraction of reservoir characteristics (water surface area, level, and storage-volume) time-series by taking leverage
of the Google Earth Engine data collection (`Landsat series <https://developers.google.com/earth-engine/datasets/catalog/landsat/>`_, `Sentinel-2 <https://developers.google.com/earth-engine/datasets/catalog/sentinel-2/>`_), and high resolition `DEM (30m) <https://www.usgs.gov/centers/eros/science/usgs-eros-archive-digital-elevation-shuttle-radar-topography-mission-srtm-1/>`_.
It built on top of `GDAL <https://gdal.org/>`_, `Scikit-Learn <https://scikit-learn.org/>`_, `NumPy <https://numpy.org/>`_ and `Matplotlib <https://matplotlib.org/>`_,
and other popular python packages. ``InfeRes`` is developed with a novel algorithm which helps inferring reservoir characteristics even from the partially cloudy images.
``InfeRes`` can be applied to monitor water surface area in any reservoir or waterbody; whereas, storage-volume can be obtained for the large reservoirs (storage >= 0.1m:sup:`3`) listed in the `GRanD <https://www.globaldamwatch.org/directory/>`_ databse.

Components of InfeRes
---------------------

1. Data download

 - Using standalone python environment (**DataDownload_GEE.py**)
 - Using web browser-based python environment (**DataDownload_GEE_GoogleColab.py**)

2. Data processing

 - Main python module (**main.py**)
 - Python module to create reservoir's Area-Elevation-Storage curves (**CURVE.py**)
 - Python module for pre-processing of satellite images (**PREPROCESSING.py**)
 - Python module to estimate reservoir's area and storage time-series (**WSA.py**)


Dependencies
----------------

 - Python version-3.8 and above (we used Anaconda3, which is an open-source distribution of the Python)
 - Python standard library (os, numpy, pandas, matplotlib, csv)
 - Python advanced library (ee, osgeo, rasterio, sklearn.cluster, scipy.ndimage, skimage.morphology)

Installation
---------------

- Install the latest version of Anaconda (download `here <https://docs.anaconda.com/free/anaconda/install/windows/>`_).

   *To create the conda environment with python=3.10, for instance, use:*
   
    (base) C:/User/UserName/conda create -n environment_name python=3.10

   *To activate the conda environment, use:*
   
    (base) C:/User/UserName/conda activate environment_name
   
- Install all libraries within the built environment (following steps are recommended).

 i) conda install -c conda-forge **rasterio**
 ii) conda install -c conda-forge **gdal=3.9.0** (assuming 3.9.0 is the latest vesrion of GDAL)
 iii) conda install -c conda-forge **spyder**
 iv) conda install -c conda-forge **earthengine-api**
 v) Similarly install all the other libraries

- Open spyder and load all the InfeRes modules (i.e **DataDownload_GEE.py, main.py, CURVE.py, PREPROCESSING.py, and WSA.py**)

Usage Instructions
---------------------

egregregre




