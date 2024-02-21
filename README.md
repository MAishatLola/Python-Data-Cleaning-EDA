# Diabetes Prediction 💻

## Table of Contents 📖
- [Project Overview](#project-overview)
- [About Dataset](#about-dataset)
- [Goal of the Project](#goal-of-the-project)
- [Data Sourcing](#data-sourcing)
- [Tools](#tools)
- [Data Cleaning/Preparation](#data-cleaning-preparation)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Data Analysis](#data-analysis)
- [Results/Findings](#results-findings)
- [Recommendation](#recommendation)
- [Limitation](#limitation)

### Project Overview
This project is about data cleaning and transformation to ensure quality by delving into the fascinating world of Diabetes Prediction using a Kaggle dataset. This involved techniques like handling missing values, identifying and correcting inconsistencies, handling Outliers and ensuring data format consistency. As well as performing an Exploratory Data Analysis to get a sense of the distribution of variables and their relationships.

![Distributions by BMI Classifications](https://github.com/MAishatLola/Python-Data-Cleaning-EDA/assets/148435526/121d1d5c-eaa0-43d9-ba0b-bfff22924698)

### About Dataset 
The Diabetes Prediction Dataset contains a collection of medical and demographic features (age, BMI, hypertension, etc.) associated with patients' diabetes status (positive/negative), enabling analysis and prediction of diabetes risk.
### Goal of the Project
To uncover hidden patterns and prepare the data for accurate prediction models.
### Data Sourcing
A Kaggle Dataset https://www.kaggle.com/datasets/iammustafatz/diabetes-prediction-dataset
### Tools 
- Python- Data Cleaning [Download Here](https://drive.google.com/file/d/1J7L7S_bAnm8VgGm9fcQ85FSG7c6UjONo/view?usp=sharing)
- Excel- Data Cleaning

  
### Data Cleaning/Preparation

In the initial stage of data cleaning, we performed the following tasks:
1. Data Loading and Inspection
2. Handling and treatinng missing values
3. Handling the outliers


### Exploratory Data Analysis
 - Are there any relationship between the Demographic Features and Diabetics?
   ![Distribution by Gender](https://github.com/MAishatLola/Python-Data-Cleaning-EDA/assets/148435526/5bf3eb05-658f-42d6-87a7-e78a20dd1eab)

 - What are the key Metrics for Diabetics Prediction?

### Data Analysis

Some interesting codes/features we worked with:

```python

import matplotlib.pyplot as plt

x = diabetes_prediction['age']
y = diabetes_prediction['hypertension']

plt.scatter(x, y)

plt.xlabel('Age', fontsize=16)
plt.ylabel('Hypertension (1 for yes, 0 for no)', fontsize=16)
plt.title('Relationship between Age and Hypertension', fontsize=20)

plt.show();
```
### Results/Findings
The Analysis results are summarized as follows:
1. No Significant Relationship Between Age and Hypertension in Diabetes
2. There is little to no significant difference in the range of BMI values (difference between min and max) between males and females with hypertension
3. BMI distribution across genders and hypertension groups shows minimal differences. Interestingly, no individuals with "other" gender classification have hypertension in this dataset.

### Recommendations
Based on the Analysis conducted, these are the recommentions:

- Collection of Data for other risk factors (Family History, Lifestyle, etc) beyond age for predicting hypertension in diabetic patients.

### Limitations
- Insufficient provisions of data for the size and representativeness of "Other" Gender Category

### References
BMI Categorization ©️ [See Here](https://www.cdc.gov/obesity/basics/adult-defining.html)
Kaggle DataSet ©️  [Link](https://www.kaggle.com/datasets/iammustafatz/diabetes-prediction-dataset) 


