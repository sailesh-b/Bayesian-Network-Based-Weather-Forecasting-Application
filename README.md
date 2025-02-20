# Building a Bayesian Network-Based Weather Forecasting Application

**Introduction** 
This project focuses on creating a Bayesian Network to model the relationships between weather-related variables, specifically 'HLY-HTDH-NORMAL,' 'HLY-WIND-AVGSPD,' and 'HLY-TEMP-NORMAL,' and performing inference to predict 'HLY-TEMP-NORMAL' based on the values of the other two variables.

**Installation** 
Before using this code, make sure to install the required Python libraries:

pgmpy
pandas
numpy

**1.Dataset**
https://drive.google.com/file/d/1-cRM-nSzEWgLecRUWeE-pifRf70ph1ck/view?usp=sharing
the link provides the dataset
The dataset used in this project is from https://www.noaa.gov/. This is an United Stated government website that provides Environment datas such as Weather dataset, climate, ocean, sattilite information.
Our data is consist of 274 Data collection poins as Area names, then attributes such as 
HLY-TEMP-NORMAL	Temperature mean
HLY-CLDH-NORMAL	Cooling degree hours
HLY-HTDH-NORMAL	Heating degree hours
HLY-PRES-NORMAL	Sea level pressure mean
HLY-CLOD-PCTCLR Clouds clear percentage
HLY-WIND-AVGSPD	Average wind speed

It consist of Hourly data for 1 year from 01/01/2010 Time 00:00 to 31/12/2010 Time 23:00.

**Data Cleaning & Preprocessing**
the actual file contains negative values, void rows etc. The data is cleaned without floating values and negative values.

**Building a Bayesian Network**
bayesian network is builded with 2 attributes and it is depending on the output.
**Generating CPDs**
according to historical data, cpds are generated with probabilities.
**Training & Testing**
trained dataframes first with certain amount of data, then bayesian network is build with one attribute and builded with 2 attributes.
**Final result**
the final result is showing the probabilities of temperature (highest probability will taken as the resulted temperature.)

https://drive.google.com/file/d/1-cRM-nSzEWgLecRUWeE-pifRf70ph1ck/view?usp=sharing

