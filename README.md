# Disease Prediction ML

## Overview
This repository contains machine learning models for predicting multiple diseases based on health data. The project is implemented in Python, leveraging various machine learning algorithms.

The primary aim of this project is to develop accurate predictive models for diagnosing diseases using machine learning techniques. By leveraging machine learning algorithms, the project aims to assist healthcare professionals in early detection and diagnosis, thereby improving patient outcomes and reducing healthcare costs.

# Programming Languages and Libraries Used
 Python: Main programming language used for implementing the machine learning models.
## Libraries
The following Python libraries were used in this project:

NumPy: Used for numerical computing and handling arrays and matrices.
Pandas: Used for data manipulation and analysis.
Scikit-learn (sklearn): Used for implementing machine learning algorithms and model evaluation.
Matplotlib: Used for data visualization.
Seaborn: Used for statistical data visualization.
Streamlit: Used for deploying and sharing the machine learning models as web applications.

# Included Disease Prediction Models
## Diabetes Prediction Model
Attributes:
Pregnancies
Glucose
Blood Pressure
Skin Thickness
Insulin
BMI
Age
Diabetes Pedigree Function
## Heart Disease Prediction Model
Attributes:
Sex
Chest Pain Type (cp)
Resting Blood Pressure (trestbps)
Serum Cholesterol (chol)
Fasting Blood Sugar (fbs)
Resting Electrocardiographic Results (restecg)
Maximum Heart Rate Achieved (thalach)
Exercise-Induced Angina (exang)
ST Depression Induced by Exercise Relative to Rest (oldpeak)
Slope of the Peak Exercise ST Segment (slope)
Number of Major Vessels Colored by Fluoroscopy (ca)
Thalassemia (thal)

## Parkinson's Disease Prediction Model
Attributes:
Name (ASCII subject name and recording number)
Average Vocal Fundamental Frequency (MDVP:Fo(Hz))
Maximum Vocal Fundamental Frequency (MDVP:Fhi(Hz))
Minimum Vocal Fundamental Frequency (MDVP:Flo(Hz))
Several Measures of Variation in Fundamental Frequency (MDVP:Jitter(%), MDVP:Jitter(Abs), MDVP:RAP, MDVP:PPQ, Jitter:DDP)
Several Measures of Variation in Amplitude (MDVP:Shimmer, MDVP:Shimmer(dB), Shimmer:APQ3, Shimmer:APQ5, MDVP:APQ, Shimmer:DDA)
Ratio of Noise to Tonal Components in the Voice (NHR, HNR)
Health Status of the Subject (status) - 1: Parkinson's, 0: Healthy
Two Nonlinear Dynamical Complexity Measures (RPDE, D2)
Signal Fractal Scaling Exponent (DFA)
Three Nonlinear Measures of Fundamental Frequency Variation (spread1, spread2, PPE)
These attributes provide information about various factors related to each disease. The models will use these attributes to predict the likelihood of an individual having the respective disease.
