# Appliance-Energy-Prediction-Regression-Capstone-project-
Appliance Energy Prediction Project
**Project Summary:**
This capstone project revolves around analyzing data related to the energy consumption of household appliances. The dataset comprises energy usage data in watts per hour, recorded every 10 minutes from January to May. The primary objective is to build a machine learning model capable of accurately predicting appliance energy consumption based on various household parameters.

**Problem Statement:**
The dataset consists of 29 columns, with "Appliances" as the dependent variable, and 28 independent variables. These columns encompass various parameters related to a building, including room temperatures (T1 to T9), outdoor temperature (Tout), and room humidity (RH1 to RH9), as well as outdoor humidity (RHout). Additional columns contain data on pressure, wind speed, visibility, and dew point temperature. The goal is to create a machine learning model that predicts appliance energy consumption based on these parameters.

**Data Collection:**
The data was gathered via home sensors, recording readings at 10-minute intervals over 4.5 months.

**Data Preprocessing:**
The project involved several data preprocessing steps, including data loading, type identification, null value handling, and unique value extraction. Exploratory data analysis (EDA) played a significant role, with graphs revealing insights. Outliers were detected using box plots and removed. Additionally, feature engineering was implemented by categorizing appliance usage into High and Low consumption based on hourly mean energy usage.

**Machine Learning Models:**
Following data preparation, a range of regression models were employed, including Linear Regression, Lasso Regression, Ridge Regression, Decision Trees, Random Forest, XGBoost, and Extra Trees Regression. To mitigate multicollinearity between columns, we calculated Variation Inflation Factor (VIF) scores and removed variables with VIF scores exceeding 10. Model evaluation was based on R2 scores, assessing their goodness of fit to the data.
