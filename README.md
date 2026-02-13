# Analysis of Electric Vehicles’ Impact on PM2.5 Levels in California

## Project Overview

This project analyzes the relationship between electric vehicle (EV) adoption, charging infrastructure growth, and air quality across California counties. The objective is to evaluate whether increasing EV adoption contributes to improvements in air quality, specifically reductions in PM2.5 (fine particulate matter) concentrations.

The analysis integrates geospatial data, environmental datasets, vehicle population statistics, and air quality measurements to visualize and evaluate spatial and temporal trends in EV growth and pollution levels.

This project was completed as part of a Geographic Information Systems (GIS) analysis focusing on spatial data processing and environmental analytics.

---

## Objectives

- Analyze the growth of electric vehicles and charging infrastructure across California counties.
- Examine the relationship between EV adoption and PM2.5 air pollution levels.
- Integrate geographic shapefiles with environmental and demographic datasets.
- Visualize spatial patterns in EV distribution and air quality trends.
- Compare air quality metrics across multiple years to identify long-term trends.

---

## Data Sources

The project integrates multiple public datasets:

- California county shapefiles (geographic boundaries)
- EPA Air Quality System (AQS) – PM2.5 and AQI data
- California Air Resources Board (ARB) datasets
- EV charging station datasets (latitude & longitude coordinates)
- Vehicle population datasets (BEV and PHEV counts)
- County-level population and demographic data

All datasets were cleaned, transformed, and merged to create a unified geospatial analysis framework.

---

## Technologies Used

- Python
- Pandas & NumPy (data processing)
- GeoPandas (geospatial analysis)
- Matplotlib & Seaborn (visualization)
- Folium & ipyleaflet (interactive mapping)
- Scikit-learn (data preprocessing)
- Reverse Geocoder

---

## Methodology

### 1. Data Collection
- Downloaded shapefiles and environmental datasets from public sources.
- Retrieved EV charging station data with geographic coordinates.
- Collected air quality and vehicle population datasets for multiple years.

### 2. Data Cleaning & Preparation
- Converted raw population and environmental data into structured tables.
- Cleaned and formatted datasets for consistency across counties.
- Converted latitude and longitude coordinates into geospatial points.
- Normalized and aligned datasets for merging.

### 3. Geospatial Integration
- Loaded California county shapefiles using GeoPandas.
- Merged demographic, EV, and air quality datasets using county identifiers.
- Created GeoDataFrames for spatial analysis.

### 4. Analysis & Visualization
- Generated thematic maps showing population and EV distribution.
- Plotted EV charging stations on county maps.
- Compared EV adoption trends across multiple years.
- Created spatial plots for AQI and PM2.5 analysis.
- Visualized relationships between EV growth and air quality metrics.

---

## Key Analysis Components

### Electric Vehicle Growth Analysis
EV adoption trends were analyzed by aggregating BEV and PHEV vehicle counts across counties and comparing growth across multiple years.

### Charging Infrastructure Mapping
Charging station coordinates were converted into geospatial points and mapped to counties to evaluate infrastructure distribution.

### Air Quality Analysis
PM2.5 and AQI datasets were aggregated by county and analyzed across multiple years to observe pollution trends.

### Spatial Correlation Study
Regions with higher EV adoption were compared against PM2.5 concentrations to identify potential environmental improvements.

---

## Results & Insights

- EV adoption increased significantly across most California counties between 2010 and 2023.
- Counties with higher EV adoption and charging infrastructure tend to show improved air quality indicators.
- Spatial visualization highlights uneven distribution of EV infrastructure across regions.
- GIS-based analysis provides insights into sustainability trends and transportation impacts.

---

## Project Structure

