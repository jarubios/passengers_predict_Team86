# passengers_predict_Team86
This repository contains the notebooks for the analysis, prediction and visualization of passenger data from land terminals in Colombia

## Introduction
This repository contains the different developments or analyzes carried out by the working group (Team 86) to solve the need of the U - Mobile company, within the framework of the Data Science For All (DS4A) training process - Cohort 5

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

File

## Model predict

In this notebook you can find the predict model, one for each terminal. The model is performed with the algoritm XGBoost and the main metrics for evaluate is Root Squared Mean Error (RMSE) and R2. 

File: Model_XGBoost_Terminal.ipynb

## Front end
This notebook contains the code for the display of the data in the dashboard built with Dash / Plotly

File



