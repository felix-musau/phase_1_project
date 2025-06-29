# HAZARD AND RISK ANALYSIS FOR AIRCRAFT OPERATIONS
## Introduction
The overrall safety of an aircraft is determined by many factors. The choice of an aircraft impacts the safety, efficiency and profitability of a business.

As the aviation industry is regularly  subject to unpredictable market conditions and maintainance challenges, understanding which type of aircrafts present lower risk is essential.

Geographical locations and weather conditions among other forces of nature, also, can introduce operational hazards that impact flight safety and perfomance.

In this analysis, I collected data from kaggle to visually represent these factors.
#### For a non-technical presentation of the data refer to this [link](https://github.com/felix-musau/phase_1_project/blob/main/presentation.pdf)
#### For a Tableau presentation, refer to this [link](https://public.tableau.com/app/profile/felix.musau3046/viz/Aviation_analysis_17507632970630/Dashboard1)


### Objectives

- Data Cleaning
- Perform Exploratory Data Analysis
- To collect findings and visualize them
- To come up with business recommendations and steps forward

##  Business Understanding

Accidents are mostly inevittable. However, identifying patterns that led to these accidents in the past may help tailor our decission as we dive into this industry.

 As a team aspiring to venture into the aviation industry, we are curious about:
 
1. Is air as a mode of transport becoming safer with time

2. What is the effect of weather conditions to aircraft accidents

3.  Do varying engine types present different levels of risk

4. Is there a correlation between an aircraft make and its damage

5.  Effect of flight purpose to accidents

6.  What category of an aircraft is safer

## Data Understanding

For this research, we collected data from kaggle which contains information from 1962 and later about civil aviation accidents and selected incidents within the United States, its territories and possesions, and in international waters.

Each record(row) represents information about a certain plane accident incident.

Each column contains a different type of data related to that incident. We are mostly dealing with the following columns:

- `Event.Date` : The date when the accident occured
- `Location` : The state/ exact place where the accident occured
- `Airport.Name` : The airport where the subject plane took off from
- `Injury.Severity` : How critical were the inuries from the accident
- `Aircraft.Damage` : The impact of the crash on the plane
- `Make` : The type of aircraft
- `Total.Fatal.Injuries`
- `Total.Serious.Injuries`
- `Total.Minor.Injuries`
- `Total.Uninjured`
- `Weather.Condition`

Among other categories as we shall explore later in the analysis


