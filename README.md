

---

# Mental Health Fitness Predictor

## Overview

The Mental Health Fitness Predictor project aims to analyze and predict mental health fitness based on various indicators across different countries. It utilizes datasets encompassing prevalence rates of mental disorders and disability-adjusted life years (DALYs) due to mental disorders.

## Datasets Used

1. **Dataset 1: Disability-Adjusted Life Years (DALYs)**
   - Contains information on DALYs attributed to mental disorders across different years and countries.

2. **Dataset 2: Prevalence of Mental and Substance Use Disorders**
   - Provides prevalence rates of specific mental disorders (e.g., schizophrenia, bipolar disorder) across countries.

## Project Structure

The project involves several key steps:

1. **Data Collection and Preparation**
   - Data was sourced from CSV files stored in Google Drive and merged into a unified dataframe.
   - Missing values were handled, and categorical variables were encoded using LabelEncoder.

2. **Exploratory Data Analysis (EDA)**
   - Visualizations such as heatmaps and pair plots were generated to understand correlations and distributions within the dataset.
   - Time-series plots were used to visualize trends in mental fitness across countries.

3. **Modeling**
   - Two models were trained:
     - **Linear Regression**: Predicts mental fitness based on various features.
     - **Random Forest Regressor**: Provides an alternative prediction model for comparison.

4. **Model Evaluation**
   - Performance metrics (Mean Squared Error, Root Mean Squared Error, R-squared Score) were computed for both models using train-test split.

## Results

- **Linear Regression Model Performance**
  - Mean Squared Error: 1.36
  - Root Mean Squared Error: 1.17
  - R-squared Score: 0.74

- **Random Forest Regressor Model Performance**
  - Mean Squared Error: 0.005
  - Root Mean Squared Error: 0.07
  - R-squared Score: 0.999

## Conclusion

The project demonstrates promising results in predicting mental health fitness using machine learning techniques. Further refinement and validation could enhance the accuracy and applicability of the models for real-world use cases.

---

Feel free to customize this README with additional details or sections specific to your project's context and findings.
