# Dask PDC Tutorial

This tutorial was made using [Dask Tutorial](https://github.com/dask/dask-tutorial) and [Dask Documentation](https://docs.dask.org/en/stable/).

Dask is a parallel and distributed computing library that scales the existing Python and PyData ecosystem. Dask can scale up to your full laptop capacity and out to a cloud cluster.

## Prepare

#### 1. You should clone this repository

    git clone http://github.com/dask/dask-tutorial

and then install necessary packages.
There are three different ways to achieve this, pick the one that best suits you, and ***only pick one option***.
They are, in order of preference:

#### 2a) Create a conda environment (preferred)

In the main repo directory

    conda env create -f binder/environment.yml
    conda activate dask-tutorial

#### 2b) Install into an existing environment

You will need the following core libraries

    conda install -c conda-forge ipycytoscape jupyterlab python-graphviz matplotlib zarr xarray pooch pyarrow s3fs scipy dask distributed dask-labextension

Note that these options will alter your existing environment, potentially changing the versions of packages you already
have installed.

#### You should follow only one of the options above!
