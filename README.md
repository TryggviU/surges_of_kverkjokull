# Surges of Kverkjökull

Repository of code used to analyse surges of Kverkjökull in a paper of the same name in the journal Jökull.

Please cite the paper if using the code:

> Unnsteinsson T, Spagnolo M, Rea B, Barr I, Girona T, and Mullan D (2026). Surges of Kverkjökull. _Jökull 76_ [in press].


The repository contains two Jupyter Notebooks:

`surface_backscatter_changes.ipynb` uses [Google Earth Engine](https://earthengine.google.com/) (and [geemap](https://geemap.org/)) to track changes in backscatter between yearly mosaics of Sentinel-1 images.

`surface_elevation_changes.ipynb` uses [pdemtools](https://pdemtools.readthedocs.io/en/latest/) to access [ArcticDEM](https://www.pgc.umn.edu/data/arcticdem/) strips to calculate surface elevation changes.
