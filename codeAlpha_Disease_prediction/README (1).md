# CodeAlpha_Disease_Prediction

## Disease Prediction from Medical Data

This project focuses on predicting the likelihood of three major health conditions—**Heart Disease**, **Diabetes**, and **Breast Cancer**—by analyzing structured patient data. It serves as part of the CodeAlpha Machine Learning Internship program.

## Objective

The primary goal is to apply advanced classification techniques to medical datasets to provide accurate diagnostic possibilities based on patient metrics.

## Approach & Technologies

We implemented a complete machine learning pipeline including data cleaning, feature scaling, and model benchmarking.
- **Data Source:** Datasets were acquired from the **UCI Machine Learning Repository**.
- **Preprocessing:** Handled missing values via median imputation and performed feature scaling using 'StandardScaler'.
- **Algorithms Used:**
  - **Support Vector Machine (SVM)**
  - **Logistic Regression**
  - **Random Forest**
  - **XGBoost**

##  Key Features & Medical Metrics

The models utilize various patient attributes to make predictions:
- **Heart Disease:** Age, chest pain type, cholesterol levels, and maximum heart rate.
- **Diabetes:** Glucose levels, BMI, age, and insulin levels.
- **Breast Cancer:** Cell nucleus features such as radius, texture, and perimeter.

##  Results & Batch Audit
The performance was verified using a Batch Audit on the test sets.
| Disease | Best Performing Model | Accuracy |
| **Heart Disease** | SVM | 93% |
| **Diabetes** | XGBoost | 73% |
| **Breast Cancer** | Random Forest | 98% |

*Note: The Diabetes model has been optimized using SMOTE to improve recall and ensure critical cases are not missed.*

##  File Structure
- 'Disease_Prediction.ipynb': Main Jupyter/Colab notebook with full source code.
- 'requirements.txt': Necessary libraries to run the project.
- 'models/': Folder containing persisted '.joblib' files for models and scalers.

##  How to Run
1. Clone the repository: 'git clone https://github.com/YourUsername/CodeAlpha_Disease_Prediction.git'
2. Install dependencies: '`pip install -r requirements.txt'
3. Open 'Disease_Prediction.ipynb' in Jupyter or Google Colab to see the analysis and run predictions.


**Internship:** CodeAlpha ML Internship  
**Intern:** GANESH KUMAR   
**Tag:** @CodeAlpha
