Cardiovascular Disease Prediction Using Machine Learning
Machine Learning Classification · Healthcare Analytics

Overview

This project investigates the application of machine learning techniques to predict cardiovascular disease based on health indicators and lifestyle-related factors. A comparative analysis was conducted to evaluate different classification algorithms and identify an effective approach for predicting cardiovascular disease.

Problem Statement

Cardiovascular disease is a major health concern, and early identification of individuals at risk can support preventive healthcare efforts. This project explores whether health-related features can be used by machine learning models to distinguish individuals with and without cardiovascular disease.

Objectives
- Explore and understand cardiovascular health data.
- Identify patterns and relationships among health-related variables.
- Compare classification algorithms.
- Evaluate model performance, particularly its ability to identify positive cases.
  
Dataset
- Source: Behavioral Risk Factor Surveillance System (BRFSS) 2021 dataset
- Records: 308,854
- Features: 19
- Target: Heart Disease (Yes/No)


Workflow
  Data Collection
  BRFSS 2021 Dataset
          |
  Data Preprocessing
  Cleaning · Encoding · Scaling · Transformation
          |
  Handling Class Imbalance
  SMOTE
          |
  Model Training & Comparison
  Logistic Regression · Random Forest · MLP · Other models
          |
  Evaluation & Analysis
  ROC-AUC · Precision · Recall · F1-score


Evaluation & Findings
Model	ROC-AUC
Logistic Regression	0.837

Logistic Regression demonstrated the best ROC-AUC performance in the comparative analysis. The study also explored the effect of class imbalance and decision threshold adjustment on the model's ability to identify positive cases.

Limitations
- Imbalanced target classes can affect prediction performance.
- Predictive results are dependent on the dataset and selected features.
- The model is intended for academic research and is not a substitute for professional medical diagnosis.




  
