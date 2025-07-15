# Road Accident Data Analysis Project

## Overview
This project contains Road Accident data, stored in an Excel file (`road_accident_data.xlsx`). The dataset includes detailed accidents informations. This README provides an overview of the data structure, its contents, and potential uses for analysis, along with visualizations from the dashboard.

## Meta Data 
- **ID** : A unique identifier for each accident record. The ID values start from 165433 and are incremented for each new record.
- **State** : The state in the USA where the accident occurred.
- **Date** : The date and time of the accident.
- **Day_of_Week** : The day of the week when the accident occurred.
- **Time_of_Day** : The time of the day when the accident occurred.
- **Weather_Conditions**: The prevailing weather conditions at the time of the accident (e.g., Sunny, Rainy, Snowy, Foggy, Stormy).
- **Road_Conditions** : The condition of the road surface at the time of the accident (e.g., Dry, Wet, Icy, Snowy, Muddy).
- **Light_Conditions** : The lighting conditions at the time of the accident (e.g., Daylight, Dawn, Dusk, Night).
- **Type_of_Road** : The type of road where the accident occurred (e.g., Highway, Street, Freeway, Rural, Urban).
- **Type_of_Junction** : The type of junction where the accident occurred (e.g., Intersection, T-Junction, Roundabout, Crossroads, Overpass, Underpass).
- **Type_of_Accident** : The type of accident that occurred (e.g., Rear-end collision, Head-on collision, Side collision, Rollover, Run-off-road, Pedestrian involved, Cyclist involved).
- **Vehicle_Type** : The type of vehicle involved in the accident (e.g., Car, Truck, Motorcycle, Bicycle, Pedestrian).
- **Driver_Age_Group** : The age group of the driver involved in the accident (e.g., Teenager, Young Adult, Adult, Senior).
- **Num_Vehicles_Involved** : The number of vehicles involved in the accident.
- **Num_Casualties** : The number of casualties (injuries or fatalities) resulting from the accident.
- **Speed_Limit** : The speed limit of the road where the accident occurred.
- **Distance_to_Nearest_Hospital** : The distance to the nearest hospital from the accident location.
- **Distance_to_Nearest_Police_Station** : The distance to the nearest police station from the accident location.
- **Visibility**: The visibility level at the time of the accident.
- **Road_Width** : The width of the road where the accident occurred.
- **Road_Surface_Friction_Coefficient** : The coefficient of friction of the road surface.
- **Vehicle_Speed** : The speed of the vehicle involved in the accident.
- **Time_Taken_for_Emergency_Response** : The time taken for emergency response to arrive at the accident scene.

## Work Done

### 1-Data Cleaning:
Handle Missing values with different approches using **Python**

### 2-Dashboard
Build Intractive dashboard for analysis using **Power BI** 
![Employees Dashboard](images/employees_dashboard.png)


## Results

### 1-KPI's
Summarizes key performance indicators:
- **Total Accidents**: 1,610
- **Avg. Casualties per Accident**:	1.44
- **Avg. Emergency Response Time**:	17.77 minutes
- **% of Accidents with Over-speeding**: 45.78%

### 2-Insights
- Over-speeding is a major contributor, present in nearly 46% of accidents. Enforcing speed limits could drastically reduce accident rates.

- Rainy and Snowy weather dominate accident conditions, highlighting the need for road alerts or driving restrictions during poor weather.

- Dusk and dawn conditions are high-risk times, indicating the effect of low natural light on visibility.

- States like Hawaii and Maryland show high casualty numbers, which could be prioritized for stricter safety regulations or awareness campaigns.

- Average response time (17.77 minutes) may need improvement, especially in rural or remote regions.