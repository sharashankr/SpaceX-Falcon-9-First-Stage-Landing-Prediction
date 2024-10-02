# SpaceX-Falcon-9-First-Stage-Landing-Prediction
This repository predicts if the Falcon 9 first stage will land successfully. SpaceX reduces launch costs to 62 million dollars by reusing the first stage, while others charge over 165 million. Predicting landings helps assess costs and informs competitive bids against SpaceX.

![](https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBMDeveloperSkillsNetwork-DS0701EN-SkillsNetwork/lab_v2/images/landing_1.gif)

The project is divided between multiple notebooks, with work ranging from data collection - to cleaning and finally the ML prediction. Please refer to each notebook for more details. 
For your reference:
## Table of Contents
1. [Data Collection through API](#data-collection-through-api)
    - Request to the SpaceX API
    - Clean the requested data
2. [Web Scraping - More Data Collection](#web-scraping-more-data-collection)
3. [Data Wrangling](#data-wrangling)
4. [Exploratory Data Analysis](#exploratory-data-analysis)
5. [Preparing the Data](#preparing-the-data)
6. [Visual Analysis with Folium](#visual-analysis-with-folium)
7. [Machine Learning Prediction](#machine-learning-prediction)

## Data Collection through API
- **Request to the SpaceX API**: Collected data about SpaceX launches.
- **Clean the requested data**: Filtered and prepared the raw API data for further analysis.

## Web Scraping - More Data Collection
Performed additional data collection by scraping relevant websites to augment the SpaceX API data.

## Data Wrangling
Cleaned and formatted the collected data, handled missing values, and merged different data sources.

## Exploratory Data Analysis
Explored patterns, trends, and insights from the cleaned dataset.

## Preparing the Data
Performed feature engineering and split the data into training and testing sets for model building.

## Visual Analysis with Folium
Created interactive maps to visualize launch sites and success rates using the Folium library.

## Machine Learning Prediction
Built and evaluated machine learning models to predict future SpaceX launch outcomes.
