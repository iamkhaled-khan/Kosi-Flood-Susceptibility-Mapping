# Flood Susceptibility Mapping of the Kosi Megafan

This repository contains the code and data for the paper:

Flood Susceptibility Mapping of the Kosi Megafan Using Ensemble Machine Learning and SAR Data.


What this study does
The Kosi River in Nepal and India is one of the most flood-prone rivers in South Asia. This study maps which parts of the Kosi Megafan are most at risk of flooding, using satellite radar data (Sentinel-1 SAR) and machine learning models. The best-performing model — a stacked ensemble — identified that about 39% of the Megafan is in high to very high flood risk zones, affecting an estimated 2.69 million people.

Repository contents
File / Folder Description Sensitivity Analysis.ipynbFlood mapping from Sentinel-1 SAR imagery Data_Processing. ipynb Model training, evaluation, and susceptibility map generation. Population Exposure Quantification.ipynbPopulation living in flood-risk zonesfigures/All figures used in the papershp files/Kosi Megafan boundary shapefile

Requirements
Python 3.8+, numpy, pandas, scikit-learn, xgboost, tensorflow, shap, rasterio, geopandas, matplotlib

Funding
NASA Terrestrial Hydrology Program (Grant No. 80NSSC24K0829).


DOI: https://doi.org/10.3390/rs18081158
