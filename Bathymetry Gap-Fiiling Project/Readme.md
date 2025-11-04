###### \*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\* **BRIEF OVERVIEW** \*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*

The project was executed to predict missing depths in bathymetry datasets. As the world strives to achieve a global seafloor map by 2030, it is crucial for ocean mappers/hydrographers to adopt artificial intelligence technology (machine learning \& deep learning models) to enhance seafloor data acquisition and processing.



* Project Title: Bathymetry Gap-Filling using Machine Learning (ML) Models
* Data: Bathymetry Data (NetCDF file)
* Source: GEBCO Gridded Bathymetry Data ([https://download.gebco.net/](https://download.gebco.net/))
* Aim: Predict missing depth data using ML models
* Models used: KNN, Random Forest
* Results: Missing depths were replaced with the predicted values. The Root Mean Squared Error (RMSE) for the models are:

&nbsp;  KNNImputer → 3.29m and,

&nbsp;  Random Forest model → 3.28m, cross-validation accuracy → 0.922 ± 0.069

