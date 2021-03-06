Get Started With Earthpy
========================

Earthpy is a python package devoted to working with spatial and remote sensing data.
Earthpy Also contains an IO module that supports downloading data for the earth
lab earth analytics courses.

Earthpy Modules
---------------

Spatial
IO
Utils

Installation
------------

Dependencies
~~~~~~~~~~~~

Earthpy has several Python package dependencies including : ``rasterio, geopandas, numpy``.

To install earthpy, use pip. ``--upgrade`` is optional but it ensures that the package
overwrites when you install and you have the current version. If you don't have
the package yet you can still use the ``--upgrade argument``.

``pip install --upgrade git+https://github.com/earthlab/earthpy.git``

Then import it into python.

``import earthpy as et``

To import the spatial module use:

``import earthpy.spatial as es``
