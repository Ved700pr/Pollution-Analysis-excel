# Pollution-Analysis-excel--Table of Contents
1.	Introduction
2.	Source of Dataset
3.	Dataset Preprocessing
4.	Analysis on Dataset
o	i. General Description
o	ii. Specific Requirements
o	iii. Analysis Results
o	iv. Visualization
5.	Conclusion
6.	Future Scope
7.	References

Introduction
Air pollution has become one of the most pressing environmental challenges of our time, especially in urban areas of India. To better understand and address this issue, real-time data on air quality is crucial. This project is based on the “Real-Time Air Quality Index” dataset provided by the Central Pollution Control Board (CPCB) through the Open Government Data (OGD) Platform of India.
The dataset includes real-time air quality measurements collected from various monitoring stations across the country. It provides valuable insights into key pollutants such as PM2.5, PM10, NO₂, SO₂, CO, and O₃, which are known to have serious health and environmental impacts.
Through this project, we aim to explore, visualize, and analyze air quality trends using this dataset. The objective is to identify pollution patterns, understand seasonal variations, and highlight the cities or regions that are most affected. This analysis can help raise awareness about air pollution and contribute to efforts toward cleaner and healthier air.

Source of Dataset

Link :-   https://www.data.gov.in/catalog/real-time-air-quality-index
 
Dataset Preprocessing
The dataset used in this project has been sourced from the official Indian Government portal data.gov.in, specifically from the “Real-Time Air Quality Index” catalog maintained by the Central Pollution Control Board (CPCB). It contains real-time, hourly air quality data collected from automated air monitoring stations across various cities in India.
Each record in the dataset provides values for multiple pollutants including:
•	PM2.5 (Particulate Matter <2.5 microns)
•	PM10 (Particulate Matter <10 microns)
•	NO₂ (Nitrogen Dioxide)
•	SO₂ (Sulphur Dioxide)
•	CO (Carbon Monoxide)
•	O₃ (Ozone)
•	NH₃ (Ammonia)
In addition to pollutant levels, the dataset also includes the Air Quality Index (AQI) value, location details, and timestamps. The data is collected automatically by field instruments without manual intervention, which helps ensure real-time accuracy. However, as with any real-world dataset, there may be occasional anomalies or missing values due to sensor faults or environmental conditions.
This dataset is large, dynamic, and highly relevant for environmental studies, making it suitable for statistical analysis, data visualization, and predictive modeling. It offers a strong foundation to assess pollution levels, identify trends, and support policy-oriented insights for sustainable living.

Analysis on Dataset
To better understand the real-time air quality situation in India, we performed an in-depth analysis of the Air Quality Index (AQI) dataset. The analysis focuses on identifying pollution levels, trends across cities, dominant pollutants, and temporal variations.
1. Data Cleaning and Preparation:
•	Handled missing or null values, especially for pollutant concentrations.
•	Removed outliers and readings that were abnormally high due to sensor errors.
•	Standardized location names for uniformity across records.
2. Exploratory Data Analysis (EDA):
•	City-wise AQI Levels: Cities like Delhi, Mumbai, and Kolkata consistently showed higher AQI values, indicating poor air quality.
•	Dominant Pollutants: PM2.5 and PM10 were found to be the most prevalent pollutants in most urban areas.

3. Statistical Analysis:
•	Correlation Matrix: Strong positive correlations were observed between PM2.5 and PM10, and between NO₂ and CO.
•	Descriptive Statistics: Mean, median, standard deviation, and variance were calculated for each pollutant to understand overall concentration levels.
ii. Specific Requirements
The main objectives of this analytical study were as follows:
1.	To identify overall AQI LEVEL.
2.	To break down sales performance based on gender, age groups, and customer types (B2C vs. B2B).
3.	To determine the top-polluted cities by AQI level.
4.	To review AQI for insights into logistics and fulfillment efficiency.
5.	To evaluate State -wise and city wise of pollution.
iii. Analysis Results
Based on the dataset of real-time AQI values collected across multiple Indian cities, the following insights were discovered:
•	High AQI Zones: Metro cities such as Delhi, Noida, and Faridabad consistently show AQI in the “Poor” to “Very Poor” range.
•	Major Pollutants:
o	PM2.5 and PM10 were the most dominant pollutants across urban regions.
o	NO₂ and CO levels were elevated in traffic-congested zones.


![image](https://github.com/user-attachments/assets/10c2ed29-a9d1-429d-b5b8-3cde44ddbdd1)
![image](https://github.com/user-attachments/assets/b990e8ba-83f5-4e28-bade-ee6e0a4c8652)

Conclusion
This project successfully highlighted how Excel can be a powerful tool for environmental data analysis. Using real-time AQI data from trusted government sources, we were able to extract key insights, visualize trends, and identify critical pollution sources. The interactive dashboard makes complex data understandable and supports efforts in pollution monitoring and public awareness.



