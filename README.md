# Pangeo Tutorial materials for AGU Ocean Sciences 2020

![pangeo-logo](https://aws1.discourse-cdn.com/standard14/uploads/pangeo/original/1X/657e3c5e0885ee4e5c2062c58f9aa094fa4b14a4.png)

This repository tutorial materials for a 30 min workshop that showcase Pangeo data analysis on the cloud. The `notebooks` directory contains Jupyter notebooks that illustrate how to access cloud-based data and analyze it using cloud computing. The links below will launch an interactive environment on [binder.pangeo.io](https://binder.pangeo.io/) Note that binder environments are ephemeral. Any changes you make will be lost once your session ends, and you shouldn't store passwords.

[AGU 2020 Ocean Sciences Tutorial](https://agu.confex.com/agu/osm20/meetingapp.cgi/Session/85251)

To explore 3 difference cloud-optimized datasets (MUR SST, AVISO, CMIP6), select GCP-specific content, and then, once the binder initializes, select the button below 'Pangeo Binder GCE us-central1'.

| [![badge](https://img.shields.io/static/v1.svg?logo=Jupyter&label=Pangeo+Binder&message=GCE+us-central1&color=blue)](https://binder.pangeo.io/v2/gh/pangeo-gallery/osm2020tutorial/master) |

To explore *only* MUR SST on AWS, which will be faster because that is where it is stored, select button below 'Pangeo Binder AWS US-west1', and then, once the binder initializes, select 'AWS-notebooks'.

[![badge](https://img.shields.io/static/v1.svg?logo=Jupyter&label=Pangeo+Binder&message=AWS+us-west-2&color=orange)](https://aws-uswest2-binder.pangeo.io/v2/gh/pangeo-gallery/osm2020tutorial/master) 


## Tutorial Highlights

-----

- **[About Pangeo](https://pangeo.io/):** Pangeo is a community effort for big data in the geosciences using Python. A key component of the Pangeo effort is the improved integration of Xarray and Dask to enable analysis of very large datasets.
- **[About Jupyter](http://jupyter.org/):** Project Jupyter exists to develop open-source software, open-standards, and services for interactive computing across dozens of programming languages. The Jupyter Notebook is an open-source web application that allows you to create and share documents that contain live code, equations, visualizations and narrative text. Uses include: data cleaning and transformation, numerical simulation, statistical modeling, data visualization, machine learning, and much more.
- **[About Xarray](http://xarray.pydata.org/en/latest/index.html):** Xarray is an open source project and Python package that aims to bring the labeled data power of pandas to the physical sciences, by providing N-dimensional variants of the core pandas data structures.
- **[About Dask](http://dask.pydata.org/en/latest/index.html):** Dask is a flexible parallel computing library for analytic computing.
- **[About Geopandas](http://geopandas.org):** Geopandas is a library to facilitate analysis of geospatial vector data
- **[About Intake](https://intake.readthedocs.io/en/latest/index.html):** Intake is a cataloging system designed to "Take the pain out of data access and distribution"


## Workshops

* 2018 AGU workshop: [Scalable Geoscience Tools in Python — Xarray, Dask, and Jupyter](https://agu.confex.com/agu/fm18/meetingapp.cgi/Session/52170).
* 2019 AGU workshop: [Pangeo: Hands on with JupyterHub and Open-source Python Tools for Scalable Analysis of Big Data in the Geosciences](https://www.agu.org/Events/SCIWS12-Pangeo)

## Acknowledgements

At its core, Pangeo is a community effort built around open-source software. As such, the credit for the developments of the software described here belongs with the community that created it.

Elements of this tutorial were taken from the xarray, Dask, Cartopy, Holoviews, and Geoviews documentation. Some pieces of text in the xarray portion of the tutorial were adapted from Hoyer and Hamman (2016).

Pangeo is [supported](https://www.nsf.gov/awardsearch/showAward?AWD_ID=1740633&HistoricalAwards=false) by the [National Science Foundation (NSF)](https://www.nsf.gov/) via the [EarthCube Program](https://www.earthcube.org/) and the [National Aeronautics and Space Administration](https://www.nasa.gov/) via the [ACCESS Program](https://earthdata.nasa.gov/community/community-data-system-programs/access-projects).  NCAR is separately supported by the [National Science Foundation (NSF)](https://www.nsf.gov/).

Google provided compute credits on [Google Compute Engine](https://cloud.google.com/). Amazon provided compute credits on [AWS](https://aws.amazon.com)

<a rel="license" href="http://creativecommons.org/licenses/by/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by/4.0/">Creative Commons Attribution 4.0 International License</a>.