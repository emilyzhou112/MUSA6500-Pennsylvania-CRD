# Spatial Estimation of Chronic Respiratory Disease Based on Geospatial Learning Procedures - An Approach Using Earth-Engine-Based Remote Sensing Data and Air Quality Variables in the State of Pennsylvania

This study is based on an original paper from:

>  Alvarez-Mendoza, C. I., Teodoro, A., Freitas, A., & Fonseca, J. (2020). Spatial estimation of chronic respiratory diseases based on machine learning procedures—An approach using remote sensing data and environmental variables in quito, Ecuador. Applied Geography, 123, 102273.[https://doi.org/10.1016/j.apgeog.2020.102273](https://doi.org/10.1016/j.apgeog.2020.102273)


## Abstract

In this final project, we investigate the effectiveness of several machine learning models in predicting the number of hospital discharge patients with chronic respiratory diseases (CRD) using environmental and air quality variables. We replicatec and improvec upon Alvarez-Mendoza et al.’s 2020  study of CRD’s spatial distribution in Ecuador by conducting the analysis in the state of Pennsylvania. Our goal is to understand the most significant environmental and atmospheric factors leading to higher CRD risk in Pennsylvania as well as to compare the performance of different machine learning models. 

We have used remote sensing data, air quality data, and hospital discharge data in this project. Specifically, we retrieved Landsat 8 Level 2 Tier 1 data from Google Earth Engine with a spatial resolution of 30m. We obtained median satellite images by season from 2022, from which we computed the NDVI, EVI, SAVI, and Land Surface Temperature. The hospital discharge data is collected by the Pennsylvania Department of Health and available for the public to download from their webpage. The air quality data is collected through various pollutants monitoring sites across the state and distributed by the Pennsylvania Department of Environmental Protection. The variables we included are PM2.5, O3, Wind Speed, and Solar Radiation. To combine vector with raster data and to standardize the spatial unit of our analysis, we aggregated all variables into a fishnet grid of Pennsylvania using zonal statistics and area-weighted reaggregation.Subsequently, we performed dimensionality reduction on our predictor variables to avoid multicollinearity. We plan to fit four machine learning models: simple OLS regression, support vector regression, random forest regression, and multiple-layer perceptron. The root mean square error (RMSE) will be computed to compare across models.

### Contributors

Emily Zhou, Shuai Wang 

*Department of City and Regional Planning, Stuart Weitzman School of Design, University of Pennsylvania*

### Keywords

support vector machine, random forest, multiple layer perceptron, deep learning, bayesian information criteria, google earth engine, geospatial health