# Stroke Prediction
## Introduction
Stroke is a medical condition that occurs when blood vessels in the brain are ruptured or blocked, resulting in brain damage. Stroke prediction is a critical area of research in healthcare, as strokes are one of the leading global causes of mortality ([WHO: Top 10 Causes of Death](https://www.who.int/news-room/fact-sheets/detail/the-top-10-causes-of-death)). This underscores the need for early detection and prevention strategies. This project investigates the effectiveness of machine learning techniques in predicting stroke occurrences based on various clinical and lifestyle factors.      

## Dataset Information
The dataset used in this project can be downloaded from [data.world - stroke prediction dataset](https://data.world/rohit0308/stroke-prediction-23).    

## Goal of the Project
The primary goal of this project is to develop a model that predicts the likelihood of a stroke based on input parameters like gender, age, symptoms, and lifestyle factors. Additionally, the project aims to analyze the dataset to identify the most significant features that contribute to stroke prediction.

## Data Story
**Total Instances** : 12760 <br>
**Number of Attributes** : 28 (*27 features, 1 Target*) <br>
**Target Variable** : Diagnosis (Categorical, Binary - *stroke* or *no stroke*) 

### Attributes
| No. | Attribute                             | Description                                                                         | Data Type |
|-----|:---------------------------------------|:-------------------------------------------------------------------------------------|:-----------|
| 1   | Patient_Name                          | Name of the patient.                                                                | string    |
| 2   | Patient_ID                            | Unique ID assigned to each patient.                                                 | integer   |
| 3   | Patient_Age                           | Age of the patient in years.                                                        | decimal   |
| 4   | Patient_Gender                        | Gender of the patient.                                                              | string    |
| 5   | Record_Date                           | Date of the medical record.                                                         | date      |
| 6   | Dietary_Habits                        | Type of diet followed by the patient (e.g., Pescatarian, Keto, Gluten-Free, etc.).  | string    |
| 7   | LDL_Cholesterol                       | Level of LDL (bad) cholesterol in the blood.                                        | decimal   |
| 8   | Work_Type_of_patient                  | Employment status/type of work (e.g., Government Job, Private, etc.).               | string    |
| 9   | Metabolic_Equivalent_of_Task_Score    | Measure of physical activity level based on metabolic equivalent tasks (MET).       | integer   |
| 10  | Marital_Status                        | Marital status of the patient (e.g., Married, Single, Divorced).                    | string    |
| 11  | Physical_Activity                     | Patient’s overall physical activity level (e.g., Low, Moderate).                    | string    |
| 12  | Cholesterol_Levels                    | Detailed cholesterol profile including HDL and LDL values.                          | string    |
| 13  | Stress_Levels                         | Patient’s perceived stress level (numeric value).                                   | decimal   |
| 14  | Average_Glucose_Level                 | Average glucose level in blood.                                                     | decimal   |
| 15  | Heart_Disease                         | Binary indicator (0 or 1) for presence of heart disease.                            | integer   |
| 16  | Body_Mass_Index                       | Patient’s body mass index (BMI).                                                    | decimal   |
| 17  | Alcohol_Intake                        | Frequency of alcohol consumption (e.g., Never, Rarely, Frequent Drinker).           | string    |
| 18  | HDL_Cholesterol                       | Level of HDL (good) cholesterol in the blood.                                       | decimal   |
| 19  | Hypertension                          | Binary indicator for presence of hypertension (1 if present, 0 if not).             | integer   |
| 20  | Family_History_of_Stroke              | Binary indicator if there is a family history of stroke.                            | string    |
| 21  | Diagnosis                             | Current diagnosis related to the patient’s health status (e.g., Stroke, No Stroke). | string    |
| 22  | Residence_Type                        | Patient’s type of residence (e.g., Rural, Urban).                                   | string    |
| 23  | Systolic_BP                           | Systolic blood pressure measurement.                                                | decimal   |
| 24  | Smoking_Status                        | Patient’s smoking status (e.g., Non-smoker, Currently Smokes, Formerly Smoked).     | string    |
| 25  | Diastolic_BP                          | Diastolic blood pressure measurement.                                               | decimal   |
| 26  | Stroke_History                        | Binary indicator (1 if patient has a history of stroke, 0 if not).                  | integer   |
| 27  | Symptoms                              | Symptoms related to health condition (e.g., Confusion, Seizures, Weakness).         | string    |
| 28  | Blood_Pressure_Levels                 | Full blood pressure reading, represented as Systolic/Diastolic (e.g., 120/80).      | string    |
