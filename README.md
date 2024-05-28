# No-Show Appointments Analysis

## Introduction
This project investigates a dataset containing information from 100k medical appointments in Brazil. The main focus is on whether or not patients showed up for their appointments. Various characteristics about the patient are included in each row, such as the scheduled day, the hospital's location, and whether the patient is enrolled in the Brazilian welfare program Bolsa Família. The dataset is sourced from Kaggle and comprises several features.

## Questions to Answer
The primary question guiding this analysis is:

- What factors are important for predicting if a patient will show up for their scheduled appointment?

## Setup
To reproduce the analysis, you can use Jupyter Notebook and Python. The following packages are utilized:

- Pandas: For data manipulation and analysis.
- NumPy: For numerical computing.
- Matplotlib and Seaborn: For data visualization.

Make sure to install the required dependencies using the provided code snippets within the Jupyter Notebook.

## Data Wrangling

### Loading Data
The dataset is loaded using Pandas' `read_csv` function.

### Data Inspection
- The `info()` function is used to check for missing values and data types.
- Descriptive statistics are generated using the `describe()` function to understand the distribution of numerical variables.
- Duplicates and unique values in columns like `PatientId` are investigated.

### Data Cleaning
- Negative or zero ages are dropped from the dataset.
- Duplicates based on `PatientId` and `No-show` are removed.
- The `No-show` column is renamed to `No_show` for ease of use.

## Exploratory Data Analysis
In this section, various visualizations and statistical analyses are performed to answer the research question. The relationships between different variables and their impact on appointment attendance are explored.

## Conclusions
Based on the findings from the analysis, conclusions are drawn regarding the factors influencing appointment attendance. Recommendations may also be provided for healthcare providers or policymakers based on these conclusions.
tments
