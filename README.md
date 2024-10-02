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
    - Extract a Falcon 9 launch records HTML table from Wikipedia
    - Parse the table and convert it into a Pandas DataFrame
3. [Data Wrangling](#data-wrangling)
    - Exploratory Data Analysis
    - Determine Training Labels
4. [Exploratory Data Analysis](#exploratory-data-analysis)
    - Understand the SpaceX DataSet
    - Load the dataset into the corresponding table in a Db2 database
    - Execute SQL queries to answer assignment questions
5. [Preparing the Data](#preparing-the-data)
    - Preparing Data
    - Feature Engineering
6. [Visual Analysis with Folium](#visual-analysis-with-folium)
    - Mark all launch sites on a map
    - Mark the success/failed launches for each site on the map
    - Calculate the distances between a launch site to its proximities
7. [Machine Learning Prediction](#machine-learning-prediction)
    - Perform Exploratory Data Analysis and determine Training Labels
        * Create a column for the class
        * Standardize the data
        * Split into training data and test data
    - Find best Hyperparameter for SVM, Classification Trees, and Logistic Regression
    - Find which method performs best using test data

## Data Collection through API
- **Request to the SpaceX API**: Collected data about SpaceX launches.
- **Clean the requested data**: Filtered and prepared the raw API data for further analysis.

## Web Scraping - More Data Collection
- **Extract a Falcon 9 launch records HTML table from Wikipedia**: Scraped Falcon 9 launch data directly from the relevant Wikipedia page.
- **Parse the table and convert it into a Pandas DataFrame**: Converted the HTML table into a structured DataFrame for further analysis.

## Data Wrangling
- **Exploratory Data Analysis**: Explored initial patterns and trends in the data.
- **Determine Training Labels**: Identified the target labels for training machine learning models.

## Exploratory Data Analysis
- **Understand the SpaceX DataSet**: Performed analysis to understand the features and attributes of the dataset.
- **Load the dataset into the corresponding table in a Db2 database**: Inserted the data into a Db2 database for further querying.
- **Execute SQL queries to answer assignment questions**: Ran SQL queries on the database to gather insights and answers for assignment-related questions.

## Preparing the Data
- **Preparing Data**: Preprocessed the data to ensure readiness for machine learning models.
- **Feature Engineering**: Engineered new features and transformed existing ones for better model performance.

## Visual Analysis with Folium
- **Mark all launch sites on a map**: Plotted each SpaceX launch site on an interactive map.
- **Mark the success/failed launches for each site on the map**: Visualized the success or failure of launches at each site.
- **Calculate the distances between a launch site to its proximities**: Computed distances between launch sites and nearby points of interest.

## Machine Learning Prediction
- **Perform Exploratory Data Analysis and determine Training Labels**:
    * Create a column for the class
    * Standardize the data
    * Split into training data and test data
- **Find best Hyperparameter for SVM, Classification Trees, and Logistic Regression**: Use grid search or cross-validation to find the optimal parameters.
- **Find which method performs best using test data**: Evaluate the performance of the models and select the best one based on accuracy or another relevant metric.
