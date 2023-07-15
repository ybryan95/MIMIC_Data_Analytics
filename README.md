![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat&logo=numpy&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-013243?style=flat&logo=matplotlib&logoColor=white)
![ScikitLearn](https://img.shields.io/badge/scikit_learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)

# :hospital: MIMIC III Clinical Database Analysis :hospital:

This repository contains Python code that performs an exploratory and predictive analysis on the MIMIC III Clinical Database (https://physionet.org/content/mimiciii-demo/1.4/). The goal is to generate insights on the patient's data and predict certain outcomes based on patient characteristics.

## :pushpin: Table of Contents

- [Background](#background)
- [Methodology](#methodology)
- [Usage](#usage)
- [Output](#output)
- [Contributing](#contributing)

## :bulb: Background

The Medical Information Mart for Intensive Care III (MIMIC III) is a large, publicly-available database comprising deidentified health-related data associated with over forty thousand patients who stayed in critical care units of the Beth Israel Deaconess Medical Center between 2001 and 2012.

## :wrench: Methodology

The code carries out data processing, exploratory analysis, and predictive modeling using various Python libraries including Pandas, Matplotlib, and Scikit-learn. Specifically, the process includes:

1. Data Processing: Data from different tables like 'PATIENTS.csv', 'CHARTEVENTS.csv', 'D_ITEMS.csv' and 'ADMISSIONS.csv' are loaded, cleaned, merged, and transformed. 

2. Exploratory Data Analysis: A histogram is created to visualize the distribution of Body Mass Index (BMI) among patients.

3. Predictive Modeling: A Linear Regression model is trained to predict BMI based on the patient's characteristics, and a Logistic Regression model is employed to predict whether the patient expired in the hospital.

4. Evaluation Metrics: Accuracy score, ROC curve, and AUROC score are calculated to evaluate the performance of the logistic regression model.

5. Dimensionality Reduction and Clustering: PCA and t-SNE are used for dimensionality reduction, and k-means clustering is performed on the reduced dimension data.

## :computer: Usage

This Python code can be utilized to perform an in-depth analysis on the MIMIC III Clinical Database. You would need to have access to the database, which requires completing the CITI "Data or Specimens Only Research" course.

## :bar_chart: Output

The code generates several outputs including plots (Histogram, Scatter plot, PCA and t-SNE visualizations), and prediction scores (accuracy, ROC curve, AUROC, and feature importance).

## :people_holding_hands: Contributing

Contributions are welcome. Please make sure to update tests as appropriate.

> :warning: This code is provided as is. The user is responsible for ensuring compliance with the terms of use of the MIMIC III Clinical Database.
