# Heart Failure Risk Prediction

This project uses clinical data from 299 patients with heart failure to predict the risk of death using machine learning models.  
It was originally developed as a Data Science project in the 4th semester at the University of Luxembourg.

## Project Overview

The dataset contains 13 medical features and a target column `DEATH_EVENT` indicating whether the patient died during follow-up.  
Key features include:

- Age  
- Ejection fraction (heart function)  
- Serum creatinine (kidney function)  
- High blood pressure, anaemia, diabetes  
- Follow-up time  

We explore the data and build three models:

- Logistic Regression  
- Random Forest Classifier  
- K-Nearest Neighbors (KNN)

Logistic Regression achieved the best performance on the test set, with around 80% accuracy on unseen data.

## What’s in this repository?

- `notebooks/heart_failure_prediction.ipynb` – main notebook with:
  - Data cleaning & exploration
  - Visualizations (age distribution, survival, ejection fraction, correlation heatmap)
  - Model training and evaluation (Logistic Regression, Random Forest, KNN)
- `report/Heart_Failure_Risk_Prediction_Report.pdf` – full project report with explanations and conclusions.

## How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/<your-username>/heart-failure-risk-prediction.git
Install the required packages:
pip install -r requirements.txt

Open the notebook:
jupyter notebook notebooks/heart_failure_prediction.ipynb
