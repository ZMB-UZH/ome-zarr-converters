# ome-zarr-converters
Code to convert different microscopy data types to ome-zarr. Note: This is a work in progress.

Currently supported:
- 2D MAPS

## Installation:

We recommend to install the needed packages in a separate conda environment:
```
conda create -n ome-zarr-converters python=3.9 -y
conda activate ome-zarr-converters
conda install -y -c conda-forge jupyterlab
conda install -y -c anaconda ipykernel
pip install numpy dask pandas matplotlib ome-zarr scikit-image xmltodict imagecodecs
```

for viewing, one can use e.g. napari with the napari-ome-zarr plugin:
```
pip install "napari[all]" napari-ome-zarr
```

## Contributors:

Code originally written by [@CamachoDejay](https://github.com/CamachoDejay) and adapted by [@fstur](https://github.com/fstur).
