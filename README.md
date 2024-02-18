**Biomechanical Sensor Data Analysis**

**Project Overview**

This project focuses on analyzing biomechanical sensor data to understand and predict body motion. By examining time series data from sensors, we aim to identify patterns and characteristics of different movements. The analysis involves detecting peaks, creating descriptive features (mean, standard deviation, minimum, and maximum values), and applying various machine learning models to predict the type of motion performed based on sensor data.

**Objectives**

To analyze time series sensor data for peak detection and feature extraction.
To utilize extracted features to distinguish between different types of motion.
To compare the effectiveness of various machine learning models in predicting motions.

**Data Description**

The dataset comprises time series data collected from biomechanical sensors attached to subjects performing various motions. Each data point represents sensor readings at different timestamps, capturing the dynamics of the movement.

**Methodology**

Data Preprocessing: Initial cleaning and preprocessing to format the sensor data for analysis.
Peak Detection: Utilized signal processing techniques to identify significant peaks in the sensor data, indicative of key motion events.
Feature Engineering: Extracted features such as mean, standard deviation, minimum, and maximum values from the sensor data to characterize each motion.
Model Implementation: Applied several machine learning models to the feature set to predict motion types:
Logistic Regression
Decision Tree
Random Forest
XGBoost
**Key Findings**

Comparative analysis of model performance, highlighting the most effective techniques for motion prediction based on sensor data.
Insights into the characteristics of biomechanical movements and how they are captured by sensor data.
How to Run the Analysis
**Prerequisites**

Python 3.x
Required Python libraries: numpy, pandas, scikit-learn, xgboost, matplotlib
