# Visceral Fat Dataset
 Perfoming explanatory data analysis(EDA) on a classification dataset on Visceral Adipose

## Introduction
This dataset contains information about individuals and their health-related attributes, including age, ethnicity, blood pressure, diabetes mellitus status, and more. The dataset has been used for various analyses related to health and well-being.

## Description
- **Number**: An identifier for each individual.
- **Age (years)**: Age of the individual in years.
- **Ethnicity**: Ethnicity of the individual (if available).
- **Diabetes Mellitus**: Indicates whether the individual has diabetes mellitus (0 for no, 1 for yes).
- **Mean Diastolic BP (mmHg)**: Mean diastolic blood pressure in mmHg.
- **Mean Systolic BP (mmHg)**: Mean systolic blood pressure in mmHg.
- **Central Armellini Fat (mm)**: Measurement of central armellini fat in mm.
- **Current Gestational Age**: Current gestational age (if applicable).
- **Pregnancies (number)**: Number of pregnancies (if applicable).
- **First Fasting Glucose (mg/dl)**: First fasting glucose level in mg/dl.
- **BMI Pregestational (kg/m^2)**: Body Mass Index (BMI) pregestational in kg/m^2.
- **Gestational Age at Birth**: Gestational age at birth (if applicable).
- **Type of Delivery**: Type of delivery (0 for unknown, 1 for one type, 2 for another type).
- **Child Birth Weight (g)**: Child birth weight in grams.
- **Gestational DM**: Indicates whether the individual has gestational diabetes mellitus (0 for no, 1 for yes).

## Usage
To work with this dataset in Python, you can use the following code to load it into a DataFrame:

```python
import pandas as pd

# Load the dataset from a URL or local file
df = pd.read_csv('visceral_fat.csv')
