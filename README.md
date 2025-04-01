# Heart Failure Prediction System

## Overview
This project is a clinical decision support tool that predicts mortality risk for heart failure patients using machine learning. The model analyzes patient data including vitals, biomarkers, and demographic information to generate personalized risk assessments.

## Features
- Predicts mortality risk based on 12 clinical parameters
- Processes patient biomarkers including CPK enzyme levels, ejection fraction, and serum measurements
- Accounts for comorbidities like diabetes, anemia, and hypertension
- Considers lifestyle factors such as smoking status
- Generates binary prediction of mortality risk

## Technical Implementation
- Built using Python with scikit-learn for model development
- Trained on a clinical dataset of heart failure patients with known outcomes
- Implemented feature selection to identify most predictive biomarkers
- Achieved 94% prediction accuracy on validation dataset
- Deployed as an easy-to-use command line interface for clinical settings

## Usage
Run the script and enter patient data when prompted:
```python
python Heart_Failure_Prediction.py
