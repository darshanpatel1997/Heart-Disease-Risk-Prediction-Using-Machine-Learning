# Heart-Disease-Risk-Prediction-Using-Machine-Learning

## Overview
This project focuses on analyzing the **Behavioural Risk Factor Surveillance System (BRFSS)** dataset to identify key factors contributing to the risk of heart attacks. By employing robust data preprocessing and machine learning techniques, the study draws meaningful insights into the interplay between health, lifestyle, and pre-existing medical conditions on heart health. The analysis also compares high-performance computing methods to enhance scalability and performance.

## Contents
- **Dataset**: BRFSS, accessed via Kaggle. [Link to Dataset](https://www.kaggle.com/datasets/kamilpytlak/personal-key-indicators-of-heart-disease/data).
- **Research Question**: What factors contribute to the risk of someone suffering a heart attack?

## Key Processes
1. **Data Preparation and Cleaning**:
   - Recoded binary variables for machine learning readiness.
   - Removed duplicate rows and outliers.
   - Imputed missing values for numerical variables using methods like mean, median, and random imputation.
   - Prepared the dataset for exploratory and inferential statistical analyses.

2. **Exploratory Data Analysis (EDA)**:
   - **Uni-variate Analysis**:
     - Histograms for variables like height, weight, and sleep hours revealed distributions and trends.
   - **Bi-variate Analysis**:
     - Investigated relationships between target variable (`HadHeartAttack`) and other variables (e.g., gender, age, physical activity).
   - **Statistical Tests**:
     - Chi-square tests highlighted significant associations.
     - Correlation matrix identified patterns linking physical and mental health.

3. **Machine Learning Implementation**:
   - Developed models using **Random Forest** (R and Pyspark) and **Decision Tree** algorithms.
   - Conducted evaluations using metrics like accuracy, recall, and ROC AUC scores.
   - Models demonstrated high accuracy but highlighted the need for improved precision in predicting heart attacks.

4. **High-Performance Computational Approach**:
   - Leveraged Apache Spark for scalable data processing.
   - Applied distributed computing for efficient Random Forest implementation and evaluation.

5. **Comparison of Methods**:
   - Compared R and Pyspark implementations.
   - Decision Tree displayed better performance in identifying true positives, though both models exceeded 94% accuracy.

## Key Findings
- Behavioral and health factors such as **gender**, **pre-existing conditions**, **physical activity levels**, and **BMI** significantly influence heart attack risk.
- The analysis emphasized the role of data balancing and feature engineering in improving model sensitivity and precision.

## Contributors
- **Data Cleaning**: Darshan,Suwasna
- **Exploratory Analysis**: Mariam, assisted by Suwasna and Darshan
- **Machine Learning Implementation**: Darshan, Mariam
- **Report Compilation**: Suwasna

## Data Management
All processed files, including PCA scores, plots, and the Data Management Plan, can be found in the Appendix.

