PV Power Forecasting

Machine learning-based photovoltaic (PV) power forecasting using meteorological measurements and temporal feature engineering.

Project Overview

This project investigates the relationship between weather conditions and photovoltaic power generation using a real-world PV dataset.

The workflow includes:

* Data cleaning and preprocessing
* Timestamp construction and validation
* Exploratory Data Analysis (EDA)
* Physical consistency checks
* Feature engineering
* Machine learning modeling
* Model comparison and evaluation

Dataset

The dataset contains:

* Ambient temperature (°C)
* Global horizontal irradiance (W/m²)
* Wind speed (m/s)
* Precipitation (L/m²)
* Active power (kW)
* Reactive power (kVar)

Machine Learning Models

* Linear Regression
* Polynomial Regression
* Random Forest Regressor
* XGBoost Regressor

Best Model

XGBoost with Cyclical Time Features

* R² = 0.662
* RMSE = 9.18 kW

Tools and Libraries

* Python
* Pandas
* NumPy
* Scikit-Learn
* XGBoost
* Matplotlib

Author

Sam Rafeie
