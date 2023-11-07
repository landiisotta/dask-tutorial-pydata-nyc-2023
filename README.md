# Dask-tutorial-pydata-nyc-2023

## Get started

Create a conda environment

```
conda create -n dask_tutorial python=3.11
```

Install jupyterLab and graphviz:

```
conda install -c conda-forge jupyterlab=4.0.0
pip install graphviz
brew install graphviz
```

Start a jupyterLab session and follow the notebooks in `./notebooks`:

```
jupyter-lab
```

Check your jupyterLab version (`conda list`) and follow the instructions here https://github.com/dask/dask-labextension to install dask extension in jupyterLab, if jupyterlab=4.0.0 it is sufficient to run:

```
pip install dask-labextension
```

Watch the video at https://www.youtube.com/watch?v=EX_voquHdk0&ab_channel=Dask to use dask extension within jupyterlab.
