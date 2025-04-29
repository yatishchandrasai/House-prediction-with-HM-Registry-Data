# Datascience-Project
# Title: Interpretable Spatio-Temporal Machine Learning for UK House Price Forecasting: A Study Using HM Land Registry Data 

This repository contains all code, notebooks and data artefacts used to predict 2023 UK residential sale prices by combining:

HM Land Registry Price-Paid Data – official transaction records

OS Code-Point Open – postcode → lat/lon

NaPTAN – coordinates of every rail / underground station

DfE / Ofsted school list – coordinates (and ratings) of all schools

Two engineered features — nearest_station_km and dist_school_km — provide explicit spatial context.
Models benchmarked:

The models used are Linear regression, log_transformed linear regression, Decision tree, Grid search based decision tree, XGboost and Grid search based XG boost

# Performance on the 20 % hold-out set:


Model |	RMSE| (£)	R²
Linear regression model - RMSE: 2.21 M	R^2 : 0.04
Decision Tree model - RMSE-1.82 M	R^2 : 0.35
Extrme Gradient Boosting - RMSE - 1.74 M	- R^2 : 0.40
## Access to the files
Download for the pre-trained models, data can be found in this drive link [drive link](https://drive.google.com/drive/folders/102OFEHgrfmLh2d6ygvDdRjD7_5NZ3JF_?usp=sharing).
OR
Download from onedrive with this [link](https://herts365-my.sharepoint.com/:f:/g/personal/yu23aac_herts_ac_uk/EjSi0YhxuGxDlLO5rdyJUvsBCTgFSnnqKd1Zc2ciMlk0Tw?e=y5HTXx). 
