# Appliance-Energy-Prediction-Regression-Capstone-project-
Project Summary

The main focus of the capstone project is to conduct an analysis on the data related to the energy consumption of household appliances. Specifically, the data pertains to the energy used by these appliances in watts per hour, and was collected every 10 minutes between the months of January and May. The goal of the project is to utilize this data to develop a machine learning model that can accurately predict appliance energy consumption based on various household parameters.

The capstone project involves the utilization of a dataset that consists of 29 columns, one of which is the dependent variable, called "Appliances," and the remaining 28 columns are independent variables. The dataset contains various parameters related to a building, such as temperature values of different rooms (T1 to T9) and outdoor temperature (Tout), expressed in Celsius. It also includes humidity values of different rooms (RH1 to RH9) and outdoor humidity (RHout), expressed as a percentage. Additionally, the dataset includes other columns such as pressure, wind speed, visibility, and dew point temperature, measured in units of millimeters of mercury (mm Hg), meters per second (m/s), kilometers (Km), and degrees Celsius (°C), respectively. The majority of the column values in the dataset are of the floating-point data type. The goal of the project is to develop a machine learning model that can predict appliance energy consumption based on these parameters.

date: the date in year-month-day format time: the time in hour:minute:second format Appliances: the energy use of appliances in the house in Watt-hours (Wh), which is the dependent variable being predicted

T1, temperature measured in the kitchen area in Celsius.
RH1, relative humidity measured in the kitchen area in %.

T2, temperature measured in the living room area in Celsius.
RH2, relative humidity measured in the living room area in %.

T3, temperature measured in the laundry room area in Celsius.
RH3, relative humidity measured in the laundry room area in %.

T4, temperature measured in the office room in Celsius.
RH4, relative humidity measured in the office room in %.

T5, temperature measured in the bathroom in Celsius.
RH5, relative humidity measured in the bathroom in %.

T6, temperature measured outside the building on the north side in Celsius.
RH6, relative humidity measured outside the building on the north side in %.

T7, temperature measured in the ironing room in Celsius.
RH7, relative humidity measured in the ironing room in %.

T8, temperature measured in teenager room 2 in Celsius.
RH8, relative humidity measured in teenager room 2 in %.

T9, temperature measured in parents' room in Celsius.
RH9, relative humidity measured in parents' room in %.

To, temperature measured outside from Chievres weather station in Celsius.
Pressure, atmospheric pressure measured from Chievres weather station in mm Hg.

RHout, relative humidity measured outside from Chievres weather station in %.
Wind speed, wind speed measured from Chievres weather station in m/s.

Visibility, visibility measured from Chievres weather station in km.
Tdewpoint, dew point temperature measured from Chievres weather station in Celsius.

rv1, random variable 1 with no unit.
rv2, random variable 2 with no unit.
