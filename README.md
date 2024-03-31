# Heart Disease Detection

## Overview
This our IEEE AI-for-Healthcare project aims to predict the presence of heart disease based on various medical attributes of patients. It utilizes machine learning techniques to analyze a dataset containing information about patients' age, sex, chest pain type, resting blood pressure, serum cholesterol level, fasting blood sugar level, resting electrocardiographic results, maximum heart rate achieved, exercise-induced angina, ST depression induced by exercise, slope of the peak exercise ST segment, number of major vessels colored by fluoroscopy, thalassemia, and the presence of heart disease.

## Dataset
The dataset used in this project contains the following features:
1. Age: Age of the patient.
2. Sex: Gender of the patient (0 = female, 1 = male).
3. CP (Chest Pain Type): Type of chest pain experienced by the patient (0 = typical angina, 1 = atypical angina, 2 = non-anginal pain, 3 = asymptomatic).
4. Trestbps (Resting Blood Pressure): Resting blood pressure of the patient (in mm Hg).
5. Chol (Serum Cholesterol): Serum cholesterol level of the patient (in mg/dl).
6. Fbs (Fasting Blood Sugar): Fasting blood sugar level of the patient (> 120 mg/dl is considered high, 0 = false, 1 = true).
7. Restecg (Resting Electrocardiographic Results): Resting electrocardiographic results (0 = normal, 1 = having ST-T wave abnormality, 2 = showing probable or definite left ventricular hypertrophy).
8. Thalach (Maximum Heart Rate Achieved): Maximum heart rate achieved during exercise.
9. Exang (Exercise Induced Angina): Exercise-induced angina (0 = no, 1 = yes).
10. Oldpeak (ST Depression Induced by Exercise Relative to Rest): ST depression induced by exercise relative to rest.
11. Slope: The slope of the peak exercise ST segment (0 = upsloping, 1 = flat, 2 = downsloping).
12. CA (Number of Major Vessels Colored by Fluoroscopy): Number of major vessels colored by fluoroscopy (0-3).
13. Thal: A blood disorder called thalassemia (3 = normal, 6 = fixed defect, 7 = reversible defect).
14. Target: Presence of heart disease (0 = no, 1 = yes).

## Project Structure
- `README.md`: This file providing an overview of the project.
- `heart.csv`: Contains the dataset used for training and testing.
- `heart_diseases`: Jupyter notebooks for data exploration, preprocessing, model training, and evaluation.
- `requirements.txt`: List of Python dependencies required for the project.

## Usage
1. Clone this repository to your local machine.
2. Install the dependencies listed in `requirements.txt`.
3. Navigate to Jupyter notebook to explore the data and train models.
4. Use the trained models for heart disease prediction on new data.
5. Refer to the notebooks and source code for detailed implementation and analysis.


