# Prodigy_DS_05
# Traffic Accident Analysis Dashboard
#### *Dataset Link: https://www.kaggle.com/datasets/devansodariya/road-accident-united-kingdom-uk-dataset/data*

### *Dashboard Link: https://amityedu96491-my.sharepoint.com/:u:/g/personal/drishti_gautam_s_amity_edu/EdBDULCe8DZJnu2g0VcH-NABXWIdauhkYALk7QSYMVQ5uA?e=DTWH10*

## Problem Statement
#### *Prodigy Task 05: Analyze traffic accident data to identify patterns related to road conditions, weather, and time of day. Visualize accident hotspots and contributing factors.*

 This dashboard analyzes traffic accident data from the United Kingdom to identify patterns related to road conditions, weather, and time of day. It provides insights into accident hotspots and highlights contributing factors, analysing certain parameters for their impact, process and results related to the accidents. 

The analysis focuses on visualizing key accident metrics and their correlations with authoritative, environmental and temporal factors.

---

### Features of the Dataset

The dataset used for this project is the "Road Accident (United Kingdom)" dataset from Kaggle. Prominent features utilized for analysis and visualization include:

- **Accidental / Longitude**: Location of the accident.
- **Accident_Severity**: Severity of the accident on a scale of 1 to 5.
- **Number_of_Vehicles**: Number of vehicles involved in the accident.
- **Number_of_Casualties**: Number of casualties resulting from the accident.
- **Light_Conditions**: Lighting conditions at the time of the accident.
- **Weather_Conditions**: Weather conditions at the time of the accident.
- **Road_Surface_Conditions**: Road surface conditions at the accident location.
- **Year**: Year when the accident occurred.

---

### Steps Followed

1. **Data Loading**: 
   - The dataset was loaded into Power BI Desktop in CSV format.
2. **Data Cleaning and Profiling**:
   - Missing and null values were identified and handled appropriately.
   - Features such as lighting, weather, and road surface conditions were analyzed for completeness and accuracy.
   - Feature like Accident_Severity was mapped from numerical data to string data for readabilty and comprehension in the dashboard.
3. **Feature Engineering**:
   - Accident hotspots were identified using geospatial data (Accidental / Longitude).
   - Accident severity was categorized to aid in visualization.
4. **Visualization Design**:
   - Various visualizations were created to represent correlations between accident severity, weather conditions, road surface conditions, and time of day.
   - Interactive filters were added for features such as year, weather conditions, and accident severity.
5. **Dashboard Publishing**:
   - The final dashboard was published to Power BI Service for easy accessibility.

---

### Key Insights

1. **Accident Hotspots**:
   - High-accident areas were identified using geospatial clustering based on latitude and longitude data.
   - Heatmaps were used to visualize accident density across different locations.

2. **Accident Severity**:
   - Most accidents were of moderate severity (Severity Level 2).
   - Severe accidents (Severity Level 1) showed a significant correlation with poor weather and road conditions.

3. **Weather and Lighting Conditions**:
   - Accidents were more frequent during heavy rain.
   - Poor lighting conditions, such as nighttime without streetlights, contributed significantly to severe accidents on single carriageways.

4. **Casualty Count on Road Types**:
   - Single carriageways roadtype has witnessed a humongous amount of accidents irrespective of weather and lighting conditions. Which points to one thing that is lack of authoritative rules and guidance. 


5. **Vehicle and Casualty Statistics**:
   - The number of vehicles involved in accidents was positively correlated with the number of casualties.
   - Multi-vehicle accidents were more likely to result in severe casualties.

---

### Visualizations

The following visuals were included in the dashboard:
- **Interactive Filters**: To enable users to drill down by year, severity, and other key metrics.
- **Geospatial maps**: To display accident hotspots based on geolocation data.
![Snap2](https://github.com/user-attachments/assets/22fc066a-6b6e-4ed4-aa00-31f34c4d2d0a)
- **Cards**: To show the distribution of accident severity levels and casualties.
- **Multi-row cards**: To show the distribution of accidents based on road types.
- **Stacked Bar Charts**: To show the distribution of current yera accidents due to Weather_Conditions.
- **Donut Chart**: To visualise the number of cases that police investigated. 
- **Area Charts**: To depict temporal trends in accidents over the years.
- **Line and Clustered Chart**: To represent the proportion of accidents under various weather, lighting, and road conditions.
- **Slicers**: To filter the road surface conditions.

---

### Publishing

- The dashboard was published to Power BI Service for sharing with stakeholders and accessing live insights.

---

### Dashboard Snapshots

![Dashboard Showing Interactiveness](https://github.com/user-attachments/assets/96ed5683-61a4-4100-9712-17f0f9d8b9f0)

![Snap2](https://github.com/user-attachments/assets/22fc066a-6b6e-4ed4-aa00-31f34c4d2d0a)


---

### Conclusion

This dashboard provides actionable insights into traffic accidents by identifying key patterns and hotspots. It equips viewers, authorities and researchers with the data needed to implement effective road safety measures, ensuring better planning and management of road networks.
![snap4](https://github.com/user-attachments/assets/3f6e3764-7a47-4637-8fcb-3aabcd3d5078)
