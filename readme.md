# EDA on Algerian Forest Fires Dataset

## Data Set Information:
1. The dataset includes 244 instances that regroup a data of two regions of Algeria,namely the **Bejaia** region located in the northeast of Algeria and the **Sidi Bel-abbes** region located in the northwest of Algeria.
2. The period from **June 2012 to September 2012.**
3. The dataset includes 11 attribues and 1 output attribue (class)
4. The 244 instances have been classified into **fire (138 classes) and not fire (106 classes) classes.**

## Contents:

The dataset consists of 244 instances, with each instance representing a forest fire. Each instance has the following attributes:

1. Date : (DD/MM/YYYY) Day, month ('june' to 'september'), year (2012)
Weather data observations
2. Temp : temperature noon (temperature max) in Celsius degrees: 22 to 42
3. RH : Relative Humidity in %: 21 to 90
4. Ws :Wind speed in km/h: 6 to 29
5. Rain: total day in mm: 0 to 16.8
FWI Components
6. Fine Fuel Moisture Code (FFMC) index from the FWI system: 28.6 to 92.5
7. Duff Moisture Code (DMC) index from the FWI system: 1.1 to 65.9
8. Drought Code (DC) index from the FWI system: 7 to 220.4
9. Initial Spread Index (ISI) index from the FWI system: 0 to 18.5
10. Buildup Index (BUI) index from the FWI system: 1.1 to 68
11. Fire Weather Index (FWI) Index: 0 to 31.1
12. Classes: two classes, namely Fire and not Fire.


## EDA

Exploratory Data Analysis (EDA) is an important step in data analysis to summarize the main characteristics of a dataset. The Steps are as follows:

#### 1. Understanding the Contents and Impact on Forest Fire:

Temperature (temp), humidity (RH), wind speed (wind), and rainfall (rain) are all important weather variables that can have an impact on forest fires. Here's a brief explanation of how each variable can be useful:

1. **Temperature (temp)**: High temperatures can increase the likelihood of ignition and promote the spread of fires by drying out vegetation. In addition, high temperatures can cause heat stress in firefighters and make it more difficult to fight fires.

2. **Humidity (RH)**: Relative humidity affects the moisture content of vegetation and fuels, and can therefore affect the likelihood of ignition and the spread of fires. High humidity can make it more difficult for fires to start and spread, while low humidity can increase the risk of fires.

3. **Wind speed (wind)**: Wind can spread fires by blowing embers and flames across vegetation and by increasing the rate of fire spread. In addition, wind can make it more difficult to fight fires by making it harder to control the direction and intensity of the flames.

4. **Rainfall (rain)**: Rain can reduce the risk of forest fires by adding moisture to vegetation and fuels. However, heavy rain can also cause flooding and landslides, which can pose additional hazards to firefighters and can make it more difficult to access fire-affected areas.


FFMC, DMC, DC, BUI and ISI are all variables related to the Canadian Forest Fire Weather Index (FWI) System, which is a widely used system for rating fire danger based on weather conditions. Here's a brief description of each variable:

1. **FFMC (Fine Fuel Moisture Code)**: FFMC is a numeric rating of the moisture content of litter and other cured fine fuels. It represents the drying potential of small fuels and is influenced by temperature, relative humidity, wind speed, and precipitation.

2. **DMC (Duff Moisture Code)**: DMC is a numeric rating of the average moisture content of loosely compacted organic layers of moderate depth. It is an indicator of fuel consumption and indicates moisture conditions of decomposing litter beneath the surface layer of vegetation.

3. **DC (Drought Code)**: DC is a numeric rating of the moisture content of deep, compact organic layers. It is an indicator of seasonal drought effects on forest fuels and is influenced by cumulative effects of temperature, relative humidity, and precipitation.

4. **ISI (Initial Spread Index)**: ISI is a numeric rating of the expected rate of fire spread. It combines FFMC and wind speed, and is intended to represent the potential rate of fire spread in the first few hours after ignition.

5. **BUI stands for Buildup Index**: It represents the amount of fuel available for combustion in the forest. It is a function of the DMC (Duff Moisture Code) and the DC (Drought Code). The DMC measures the moisture content of the shallow organic layers of the forest floor, while the DC measures the moisture content of deeper organic layers. A higher BUI value indicates a greater potential for a forest fire to spread and become more severe.

6. **FWI stands for Fire Weather Index**: It is a composite index that combines several weather variables to provide an overall assessment of the potential for a forest fire to start, spread, and become more severe. The FWI is calculated based on the moisture content of different layers of the forest floor, the temperature, the relative humidity, and the wind speed. A higher FWI value indicates a greater potential for a forest fire to occur and become more severe.

#### 2. Data Cleaning

- The dataset should be cleaned before performing EDA.

#### 3. Data Exploration

In this step, we will apply Exploratory Data Analysis (EDA) to extract insights from the data set to answer some to the questions below:

- Which region has more number of forest fires occured?
- Are there any patterns or relationships between weather variables (e.g., temperature, humidity) and the occurrence of forest fires?
- Occurence of forest fires vs Month in which it has occured.
- What are the different range of values in which there is an occurence of forest fires?

## Files

- The Jupyter notebook is used to perform EDA. You can find the Dataset and Jupyter File in this repositry.

## Scope

The questions mentioned are not limited. The dataset can be further explored to find important feautures and a Machine Learning model can be build to detect forest fires.

## Citation
If you use this dataset in your research, please cite the following publication:

Faroudja ABID et al. , Predicting Forest Fire in Algeria using Data Mining Techniques: Case Study of the Decision Tree Algorithm, International Conference on Advanced Intelligent Systems for Sustainable Development (AI2SD 2019) , 08 - 11 July , 2019, Marrakech, Morocco.

## License
This dataset is licensed under the Creative Commons Attribution 4.0 International (CC BY 4.0) license.
