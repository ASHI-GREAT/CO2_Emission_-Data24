# CO2_Emission_-Data24

###  🌍 Overview
This project focuses on analyzing and modeling Carbon Dioxide (CO₂) emissions per capita across 212 countries, using a rich dataset of environmental, energy, health, and socio-economic indicators. The data, covering metrics from 2004 to 2014, provides a global perspective on how different factors contribute to a country's per-capita carbon emissions.
The project involves data preprocessing, exploratory data analysis (EDA), feature engineering, and the development of machine learning models — specifically using Random Forest Regression — to accurately predict CO₂ emissions. The ultimate goal is to derive insights that support sustainable development and informed environmental policymaking.

### 🎯 Objective
Primary Goal:
To build a robust machine learning model that can accurately predict CO₂ emissions per capita using environmental and socio-economic data from multiple countries.
Key Objectives:

* Analyze the relationship between energy use, pollution, infrastructure, and carbon emissions.

* Identify the most influential features contributing to CO₂ emissions.

* Handle missing and inconsistent data through effective preprocessing.

* Evaluate and compare machine learning models, with a focus on Random Forest Regression.

* Test the model on unseen data to assess generalization and real-world applicability.

## Environmental and Socio-Economic Indicators (212 Countries)
This dataset comprises diverse environmental, energy, health, and socio-economic indicators from 212 countries, aimed at predicting Carbon Dioxide (CO₂) emissions per capita. The data includes numerical and categorical features related to energy usage, pollution levels, resource depletion, and infrastructure, primarily around the years 2004 to 2014.

## 🧹 Data Quality

Missing Values:
Several features have missing values (e.g., water withdrawals, fossil fuel usage). Imputation strategies (mean/median or KNN) may be required.

## Data Types:
13 numerical (float64)
3 categorical (object) — most converted to numerical during preprocessing

Categorical mortality columns were encoded numerically or imputed.

## 🎯 Target Variable
Carbon dioxide emissions per capita (tonnes) 2011 is the output variable used for regression modeling.


