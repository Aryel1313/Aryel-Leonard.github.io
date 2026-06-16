# Aryel-Leonard.github.io

Mathematics Major (Data Science & Statistics)
Data Analytics & Business Analytics
SQL | Python | Tableau | Excel

Data Analysis and Classification

## Overview

This project demonstrates the application of statistical analysis, time series forecasting, and machine learning techniques to solve real-world data problems. The project is divided into two main components:

1. **COVID-19 Prevalence Forecasting (Time Series Analysis)**
2. **Zoo Dataset Classification and Clustering (Machine Learning)**

The goal of this project is to showcase data cleaning, exploratory data analysis (EDA), statistical modeling, forecasting, and unsupervised learning techniques using Python.

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Statsmodels
* Scikit-Learn
* SciPy
* Jupyter Notebook

---

# Project 1: COVID-19 Prevalence Forecasting

## Objective

Analyze COVID-19 prevalence data from Sri Lanka (March 2020 – March 2021) and determine whether a forecasting model can be constructed for future prevalence cases.

## Dataset

The dataset contains:

* **I** – Daily prevalence cases
* **dR** – Daily recovery cases
* **R** – Cumulative recovery cases
* **D** – Daily death counts

Source: WHO COVID-19 Data (Sri Lanka)

---

## Methodology

### 1. Data Preparation

* Imported and cleaned the dataset
* Checked for missing values
* Converted dates into a time-series index

### 2. Exploratory Data Analysis

Performed:

* Time series visualization
* Trend analysis
* Seasonal decomposition
* Autocorrelation analysis

Key findings:

* Strong upward trend
* Clear seasonality
* Significant autocorrelation
* Evidence of non-stationarity

### 3. Stationarity Testing

Used the:

* Augmented Dickey-Fuller (ADF) Test

Results indicated:

* p-value > 0.05
* Failure to reject the null hypothesis
* Series is non-stationary

### 4. Correlation Structure Analysis

Generated:

* Autocorrelation Function (ACF)
* Partial Autocorrelation Function (PACF)

These plots were used to assess lag relationships and support forecasting model development.

---

## Key Insights

* COVID-19 prevalence exhibits a strong time-series structure.
* The series contains trend and seasonal patterns.
* Forecasting models can potentially be developed after transforming the data to achieve stationarity.
* ACF and PACF plots provide evidence of temporal dependence between observations.

---

# Project 2: Zoo Dataset Classification & Clustering

## Objective

Apply unsupervised machine learning techniques to classify animals based on their characteristics and identify natural groupings within the dataset.

## Dataset

Zoo Dataset

* 100 animal observations
* 16 descriptive attributes

Examples of attributes:

* Hair
* Feathers
* Eggs
* Milk
* Airborne
* Aquatic
* Predator
* Domestic
* Tail
* Legs

---

## Machine Learning Techniques

### K-Means Clustering

Used K-Means to:

* Group animals into clusters
* Compare clustering performance
* Analyze cluster characteristics

### Hierarchical Clustering

Used:

* Agglomerative Clustering
* Dendrogram Visualization

To examine hierarchical relationships among animal groups.

---

## Key Findings

* Similar species naturally clustered together.
* Hierarchical clustering provided a visual representation of species relationships.
* Clustering algorithms successfully identified meaningful biological groupings.

---

# Skills Demonstrated

### Data Analysis

* Data Cleaning
* Exploratory Data Analysis
* Statistical Interpretation
* Trend Analysis

### Time Series Analysis

* Seasonal Decomposition
* ACF Analysis
* PACF Analysis
* Stationarity Testing
* Forecasting Preparation

### Machine Learning

* K-Means Clustering
* Hierarchical Clustering
* Model Evaluation

### Programming

* Python
* Pandas
* NumPy
* Scikit-Learn
* Statsmodels
* Matplotlib
* Seaborn

---

## Author

**Aryel Leonard**

GitHub: https://github.com/Aryel-Leonard

LinkedIn: http://www.linkedin.com/in/aryel-leonard

