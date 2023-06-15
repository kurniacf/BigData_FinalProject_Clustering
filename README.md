# Final Project Big Data - Clustering

- Name: Kurnia Cahya Febryanto
- Student ID: 5025201073
- Class: Big Data A

### Algorithm:
- K-Means Clustering with Apache Spark

### Dataset:
Link Dataset: [Airplane Crashes Dataset](https://www.kaggle.com/datasets/saurograndi/airplane-crashes-since-1908)

### Description of the Dataset
The dataset, titled "Airplane Crashes and Fatalities Since 1908", provides a comprehensive history of airplane
crashes throughout the world from 1908 to the present. Originally hosted by Open Data by Socrata,
it is no longer available from the original source and is now hosted on Kaggle.

The dataset contains various information about each crash, including:

- The date of the crash
- The type of airplane
- The operator of the airplane
- The flight's origin and destination
- Information about the number of passengers, survivors, and fatalities

### Table of Contents
1. [Dataset Description](#dataset-description)
   - [Source of the Dataset](#source-of-the-dataset)
   - [Description of the Dataset](#description-of-the-dataset)
2. [Data Acquisition](#data-acquisition)
   - [Setting Up Kaggle API](#setting-up-kaggle-api)
   - [Downloading Dataset](#downloading-dataset)
3. [Setting Up the Environment](#setting-up-the-environment)
   - [Installation of Dependencies](#installation-of-dependencies)
   - [Setting Up Apache Spark](#setting-up-apache-spark)
4. [Data Loading and Exploration](#data-loading-and-exploration)
   - [Loading Dataset into Spark DataFrame](#loading-dataset-into-spark-dataframe)
   - [Initial Data Exploration](#initial-data-exploration)
5. [Data Preprocessing](#data-preprocessing)
   - [Handling Missing Values](#handling-missing-values)
   - [Feature Scaling/Normalization](#feature-scalingnormalization)
6. [Feature Engineering](#feature-engineering)
   - [Feature Selection](#feature-selection)
   - [Feature Preparation](#feature-preparation)
7. [Model Building](#model-building)
   - [Choice of Clustering Algorithm](#choice-of-clustering-algorithm)
   - [K-Means Clustering Algorithm](k-means-clustering-algorithm)
   - [Reason for Choosing the Algorithm](#reason-for-choosing-the-algorithm)
8. [Parameter Tuning](#parameter-tuning)
   - [Initial Model Training](#initial-model-training)
   - [Hyperparameter Tuning](#hyperparameter-tuning)
   - [Retraining Model with Optimized Parameters](#retraining-model-with-optimized-parameters)
9. [Model Evaluation](#model-evaluation)
   - [Elbow Method](#elbow-method)
   - [Silhouette Score](#silhouette-score)
10. [Visualization](#visualization)
    - [Data Visualization during Preprocessing](#data-visualization-during-preprocessing)
    - [Data Visualization during Evaluation](#data-visualization-during-evaluation)
11. [Conclusion](#conclusion)
12. [References](#references)
