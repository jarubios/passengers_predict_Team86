# passengers_predict_Team86
This repository contains the notebooks for the analysis, prediction and visualization of passenger data from land terminals in Colombia. Available on: https://github.com/jarubios/passengers_predict_Team86


## Introduction
This repository contains the different developments or analyzes carried out by the working group (Team 86) to solve the need of the U - Mobile company, within the framework of the Data Science For All (DS4A) training process - Cohort 5

The codes have been generated under the following work methodology:

![Process](https://user-images.githubusercontent.com/12412106/131955451-7d2024ae-608f-4964-afa1-f9810a1ec1b3.jpg)

Note: In the file requirements.txt are the different libraries used in notebooks and that are required for their execution

## Dataset
The main data corresponds to passenger mobility data and vehicle dispatches from the authorized or approved land passenger terminals, available since August 2019 in the Colombian open data portal through the following link

https://www.datos.gov.co/Transporte/Operaci-n-de-pasajeros-y-despacho-de-veh-culos-en-/eh75-8ah6

For the identification of municipalities and Departments you can use the following file:

File:Departamentos_y_municipios_de_Colombia.csv


## Dataclean process
This notebook contains the diferent steps for standarized and adjust the data

File: Data_Cleaning.ipynb


## Exploratory Data Analysis
In this notebook you can find the diffrent analysis performed by the team for known the data and identify the features that have effect on the flow of passengers.

File: EDA_Code.ipynb


## Model predict

In this notebook you can find the predict model, one for each terminal. The model is performed with the algoritm XGBoost and the main metrics for evaluate is Root Squared Mean Error (RMSE) and R2. 

File: Model_XGBoost_Terminal.ipynb

The previous file contains the code generated to find the model of the 48 authorized or approved terminals, therefore a function is generated to update the model of a selected terminal, considering that changes in mobility are not homogeneous throughout the country.

File: Function_XGBoost_Terminals.ipynb


## Front end
This notebook contains the code for the display of the data in the dashboard built with Dash / Plotly. The asset and model folders must be in the same directory as the file with the .py extension

File: Front-end.rar

![Dashboard](https://user-images.githubusercontent.com/12412106/132024705-a54b8b8f-116a-4d5b-888e-d79d708e0627.jpeg)
