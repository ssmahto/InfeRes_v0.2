Welcome to InfeRes: A Python package for inferring reservoir water extent, level and storage volume
====================================================================================================

.. image:: https://img.shields.io/pypi/l/sciris.svg
 :target: https://github.com/ssmahto/InfeRes_test/blob/main/LICENSE

``InfeRes`` is a python package that is designed to help automatic extraction of reservoir characteristics (water surface area, level, and storage-volume) time-series by taking leverage
of the Google Earth Engine data collection (`Landsat series <https://developers.google.com/earth-engine/datasets/catalog/landsat/>`_, `Sentinel-2 <https://developers.google.com/earth-engine/datasets/catalog/sentinel-2/>`_), and high resolition `DEM (30m) <https://www.usgs.gov/centers/eros/science/usgs-eros-archive-digital-elevation-shuttle-radar-topography-mission-srtm-1/>`_.
It built on top of `GDAL <https://gdal.org/>`_, `Scikit-Learn <https://scikit-learn.org/>`_, `NumPy <https://numpy.org/>`_ and `Matplotlib <https://matplotlib.org/>`_,
and other popular python packages. ``InfeRes`` is developed with a novel algorithm which helps inferring reservoir characteristics even from the partially cloudy images.
``InfeRes`` can be applied to monitor water surface area in any reservoir or waterbody; whereas, storage-volume can be obtained for the large reservoirs (storage >= 0.1m:sup:`3`) listed in the `GRanD databse <https://www.globaldamwatch.org/directory/>`_.

Components of InfeRes
---------------------------
1. Data download
  - Using standalone python environment (DataDownload_GEE.py)
  - Using web brwoser-based python environment (DataDownload_GEE_GoogleColab.py)

2. Data processing


Content
----------------

- Dependencies
- Insatllation
- Usage



