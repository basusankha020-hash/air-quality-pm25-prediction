# Baseline Model (v1)

This folder contains the first working version of the PM2.5 prediction system.

## What this model does
- Predicts PM2.5 using other pollutant concentrations and time-based features
- Converts predicted PM2.5 into AQI categories using CPCB guidelines

## Features Used
- PM10
- NO2
- SO2
- OZONE
- Latitude, Longitude
- Hour, Day of Week, Month
- Weekend flag

## Status
- Baseline reference model
- RMSE higher than target (<20)
- Will be improved in v2 using better datasets and advanced models
