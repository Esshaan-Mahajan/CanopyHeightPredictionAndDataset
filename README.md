# CanopyHeightPredictionAndDataset

Devised and implemented a novel approach to estimate global canopy heights for the period 1980-2020 leveraging NASA GEDI 
LiDAR, meteorological datasets, Google Earth Engine, and GPUs on Pratyush HPC, fastest in India. Model was able to beat all 
previous attempts to accurately predict canopy height of a location, with an RMSE score of 2.02.

## Introduction
- In this project we aim to create a global canopy height dataset and find correlations of it with other geological factors like min/max temperature, precipitation, evapotranspiration etc.
- With the help of this dataset we can fine tune a model , and with the help of this model we can predict canopy heights of previous years with the help of geological factors available. As no other reliable source of canopy height data is available.
- With canopy height data of previous years available we can observe trends and analyse the reasons for the trends.

Note: A thorough description can be found out at ppt named,"Global Canopy Height and model". Also, the excel file, "canopy height name" contains the 2019 dataset used. Other dataset used is available here: https://developers.google.com/earth-engine/datasets/catalog/IDAHO_EPSCOR_TERRACLIMATE
## Motivation
- Make the first ever time varying data of canopy height using GEDI scanner.
- Estimating the carbon stored on land on a global scale, thus helping us to accurately quantify the carbon dioxide being eaten by the land. This is a very important component of the global carbon cycle and is a missing link in the climate change computations. 
- A second use of this data would be within the numerical weather prediction models to enable them to perform yield/crop forecasts. This is still absent in the present systems.
- Such an algorithm enabling us to estimate crop heights will help in real time agricultural monitoring. For example, over a field if the farmers grow similar/same crops every year and for a particular year if we get an anomalously low crop height, the government can step in to help farmers of that region by artificial rain or offering them pesticides if their region is infected


## Results
<img width="960" alt="image" src="https://github.com/Esshaan-Mahajan/CanopyHeightPredictionAndDataset/assets/56061481/e2646578-d41e-4eba-afe6-b1468d83ae5d">
