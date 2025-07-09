# marineflux_erddapy_demo

## samos.ipynb
This Jupyter notebook demonstrates using erddapy to query the SAMOS fluxes dataset on the MarineFlux ERDDAP server, requesting a subset as various types of python objects (netCDF4-python object, pandas DataFrame, xarray Dataset), filtering out data not flagged as "good", and plotting the data on a map in a few different ways.

## histo.ipynb
This Jupyter notebook demonstrates using erddapy to query the SAMOS fluxes dataset on the MarineFlux ERDDAP server, requesting a subset as an xarray Dataset, filtering out data not flagged as "good", and plotting histograms of each of the variables.