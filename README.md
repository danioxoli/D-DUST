# D-DUST Project (Data-driven moDelling of particUlate with Satellite Technology aid)
<br>
<center><img style="margin-right:80px;" src=D-DUST/img/DDUST__Nero.png width="300"></center>

## Project description
The D-DUST (Data-driven moDelling of particUlate with Satellite Technology aid) project focuses on the development of new means to improve both understanding and local monitoring of farming-related particulate matter (PM). The project will primarily consider the Po Valley portion belonging to the Lombardy Region as a testbed for the activities.

<center><img src=D-DUST/img/testbed.png width="600"></center>

This repository contains the code and the information related to the following Work Packages:

1. [WP2 - Data Packages](https://github.com/gisgeolab/D-DUST/tree/WP2)
    - State-of-the-art air quality and PM monitoring: review paper 
    - Data repository containing the output files 
2. [WP4 - Predictive Model Design](https://github.com/gisgeolab/D-DUST/tree/WP4)
    - State-of-the-art of PM modelling and prediction
    - Models development

## 1. WP2 - Data Packages

The D-DUST Work Package 2 focuses on the implementation of the project Analysis-ready Data Repository. A better description of the notebooks and the WP2 structures is provided in its [branch](https://github.com/gisgeolab/D-DUST/tree/WP2). Summarizing, the following notebooks have been developed for data preparation and preprocessing:

- [**Model Variables Request Notebook**](https://github.com/opengeolab/D-DUST/blob/WP2/Model%20Variables%20Request.ipynb): this notebook is used to access modelled air quality data.
- [**Ground Sensor Variables Request**](https://github.com/gisgeolab/D-DUST/blob/WP2/Ground%20Sensor%20Variables%20Request%20.ipynb) : this notebook is used to access data for both meteorological and air quality ground stations.
- [**Satellite Variables Request**](https://github.com/opengeolab/D-DUST/blob/WP2/Satellite%20Variables%20Request.ipynb): this notebook is used to retrieve satellite observations of atmospheric pollutants.
- [**Date selection**](https://github.com/opengeolab/D-DUST/blob/WP2/Date%20selection.ipynb): this notebook is used to select low precipitation and high-temperature periods.
- [**Grid Processing**](https://github.com/gisgeolab/D-DUST/blob/WP2/Grid%20Processing.ipynb): this notebook allows computing summary statistics for each variable in each grid cell.

parte matteo

## 2. WP4 - Predictive Model Design
The data repository created in the WP2, will be used in the WP4 concerning monitoring and prediction models development.

---