# Heat Pump Installation Website Analytics and Conversion Prediction Model

## Overview

This project focuses on analysing website traffic patterns, user behavior, and conversion rates for a heat pump installation service. It includes exploratory data analysis (EDA), data preprocessing, and the development of a machine-learning model to predict conversion rates. The goal is to identify key factors influencing customer engagement and optimise the conversion funnel.

## Table of Contents

- [Introduction](#introduction)
- [Data Sources](#data-sources)
- [Libraries Used](#libraries-used)
- [Data Wrangling](#data-wrangling)
- [Exploratory Data Analysis (EDA)](#exploratory-data-analysis-eda)
- [Machine Learning Model Development](#machine-learning-model-development)
- [Model Evaluation](#model-evaluation)
- [Results](#results)
- [Challenges Addressed](#challenges-addressed)
- [Recommendations](#recommendations)
- [Further Investigation](#further-investigation)
- [Contact](#contact)

## Introduction

The project aims to provide insights into how website visitors interact with a heat pump installation service's online platform. By analysing various metrics, such as website visits over time, time taken to book a design consultation, and conversion rates, the project seeks to identify opportunities for improving customer engagement and increasing the likelihood of conversion.

## Data Sources

The project utilises the following datasets:

-   `funnel_data.csv`: Contains data related to user interactions and the various stages of the conversion funnel, including first search, design consultation payments, and completion.
-   `installer_locations.csv`: Contains location data of installers, which can be used to calculate distances and analyse regional trends.
-   `property_estimates.csv`: Contains property estimates that can be linked to user data for further analysis.

## Libraries Used

The following Python libraries were used in this project:

-   **Data Wrangling**:
    -   `pandas`: For data manipulation and analysis.
    -   `calendar`: For date-related functionalities.
-   **Data Preprocessing**:
    -   `LabelEncoder`: For encoding categorical variables.
-   **Geospatial Calculations**:
    -   `math`: For calculating distances between geographical coordinates.
-   **Visualisation**:
    -   `seaborn`: For creating statistical visualisations.
    -   `matplotlib`: For creating plots and charts.
    -   `IPython.display`: For displaying images.
-   **Machine Learning**:
    -   `scikit-learn`: For model development, evaluation, and preprocessing.
    -   `imblearn`: For handling imbalanced datasets using techniques like SMOTE.
    -   `xgboost`: For training gradient boosting models.
-   **Model Evaluation**:
    -   `sklearn.metrics`: For evaluating model performance using metrics like accuracy, confusion matrix, and classification report.

## Data Wrangling

The data wrangling process involved the following steps:

1.  **Loading Data**: Reading the datasets (`funnel_data.csv`, `installer_locations.csv`, `property_estimates.csv`) using pandas.
2.  **Data Type Conversion**: Converting date columns to datetime format using `pd.to_datetime`.
3.  **Handling Missing Values**: Addressing missing data in relevant columns.
4.  **Feature Engineering**: Creating new features such as time deltas between first visit and design consultation payment.

## Exploratory Data Analysis (EDA)

The EDA process involved the following steps:

1.  **Understanding Data**: Examining the structure, data types, and missing values in the datasets.
2.  **Visualising Website Visits Over Time**: Creating time series plots to identify patterns and trends in website traffic.
3.  **Analysing Time Deltas**: Calculating and visualising the time taken from the first visit to design consultation payment.
4.  **Determining Conversion Rates**: Calculating the percentage of website visitors who booked a design consultation.

## Machine Learning Model Development

The machine learning model development process involved the following steps:

1.  **Feature Selection**: Selecting relevant features for the model.
2.  **Data Preprocessing**: Encoding categorical variables using LabelEncoder and handling imbalanced datasets using SMOTE.
3.  **Model Training**: Training various machine learning models, including Support Vector Machines (SVM), XGBoost, and Decision Trees.
4.  **Pipeline Creation**: Implementing a machine learning pipeline using scikit-learn and imblearn to streamline the process.
5.  **Cross-Validation**: Employing cross-validation techniques to ensure model robustness.

## Model Evaluation

The model evaluation process involved the following steps:

1.  **Performance Metrics**: Evaluating model performance using metrics such as accuracy, confusion matrix, and classification report.
2.  **Comparative Analysis**: Comparing the performance of different models to identify the most effective one.
3.  **Visualisation**: Visualising the results using confusion matrices and other relevant plots.

## Results

Key findings from the analysis include:

-   **Website Traffic Patterns**: Peak first visits occurred at the beginning of December 2023, followed by a progressive decrease.
-   **Time to Book Consultation**: The average time from the first visit to design consultation payment is approximately 17.71 days.
-   **Conversion Rate**: Approximately 0.98% of website visitors booked a design consultation.

## Challenges Addressed

The project addressed the following challenges:

-   **Analysing website traffic patterns over time.**
-   **Determining the time taken for users to pay for design consultations after their first visit.**
-   **Calculating the percentage of website visitors who booked a design consultation.**
-   **Understanding how conversion rates vary based on eligibility for the Boiler Upgrade Scheme grant.**

## Recommendations

Based on the analysis, the following recommendations are made:

-   **Track website visits before installation deposit**: Monitor the number of website visits before clients make an installation deposit.
-   **Track proposal downloads**: If proposal downloads are an option, track these to understand client engagement.
-   **Further investigation**: Investigate the reasons for the decline in conversion rates after the initial peak in website visits.

## Further Investigation

Further areas for investigation include:

-   **Impact of Boiler Upgrade Scheme grant eligibility on conversion rates.**
-   **Reasons for the decline in conversion rates after the initial peak in website visits.**
-   **Analysis of installer locations and their impact on service delivery.**

## Contact

For any questions or further information, please contact:

\[Einetein]

\[einsteinmunachiso@gmail.com]

\[https://www.linkedin.com/in/einstein-ebereonwu/]
