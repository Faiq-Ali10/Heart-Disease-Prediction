# Heart Disease Prediction

## Introduction
Heart disease is a significant health issue globally, and early detection can be crucial for effective treatment and prevention. This project aims to predict the likelihood of heart disease in individuals based on various medical attributes. By leveraging machine learning techniques, we analyze patient data to assist healthcare professionals in identifying individuals at higher risk.

## Dataset
The dataset used in this project (`heart.csv`) contains information about patients and their medical attributes related to heart disease. It includes the following features:
- `age`: Age of the patient (numerical).
- `sex`: Gender of the patient (categorical: 1 = male, 0 = female).
- `cp`: Chest pain type (categorical: 1 = typical angina, 2 = atypical angina, 3 = non-anginal pain, 4 = asymptomatic).
- `trestbps`: Resting blood pressure (numerical).
- `chol`: Serum cholesterol level in mg/dL (numerical).
- `fbs`: Fasting blood sugar > 120 mg/dL (categorical: 1 = true, 0 = false).
- `restecg`: Resting electrocardiographic results (categorical: 0 = normal, 1 = having ST-T wave abnormality, 2 = showing probable or definite left ventricular hypertrophy).
- `thalach`: Maximum heart rate achieved (numerical).
- `exang`: Exercise induced angina (categorical: 1 = yes, 0 = no).
- `oldpeak`: ST depression induced by exercise relative to rest (numerical).
- `slope`: The slope of the peak exercise ST segment (categorical: 1 = upsloping, 2 = flat, 3 = downsloping).
- `ca`: Number of major vessels colored by fluoroscopy (numerical).
- `thal`: Thalassemia (categorical: 3 = normal, 6 = fixed defect, 7 = reversible defect).
- `target`: Presence of heart disease (categorical: 1 = yes, 0 = no).

## Installation
To run this project locally, follow these steps:
1. Clone this repository:
   ```bash
   git clone https://github.com/Faiq-Ali10/Heart-Disease-Prediction
