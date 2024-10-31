# Early Detection of Alzheimer's Disease Using Explainable AI-Powered Deep Learning
This repository contains a comprehensive study on the early detection of Alzheimer’s disease, focusing on developing Machine Learning models (SVM, Random Forest, XGBoost) and Deep Learning (VGG-16, ResNet-50, VGG-19) models, and a model that integrate MRI and tabular data to create a multi-feature model (ResNet-50V2) for robust, early prediction.

Objective:
The objective of this research is to create reliable models that utilize tabular and MRI data from the OASIS-1 dataset, designing a multi-feature approach that detects Alzheimer’s disease with improved accuracy while effectively mitigating overfitting.

# Key Components of the Study

* Data Preprocessing and EDA
MRI and Tabular Data: Preprocessed and cleaned both MRI and tabular data to ensure high-quality inputs.

* Exploratory Data Analysis (EDA): Conducted a thorough analysis of the dataset to uncover key patterns and correlations relevant to Alzheimer's progression.

* Model Development
- Machine Learning and Deep Learning Models: Implemented various ML and DL models for Alzheimer’s detection, comparing and optimizing their performance.
- Multi-Feature Model: Integrated MRI and tabular data features to develop a unified, multi-feature model.

* Explainable AI (XAI) Integration
Enhanced the multi-feature model with explainable AI to interpret the predictions and provide visual explanations of the MRI regions contributing significantly to each prediction. This helps in understanding which areas of the brain are influential in the early detection of Alzheimer’s disease.

* Web Application for Model Predictions
A web application captures user inputs, displays model predictions, and provides XAI-based explanations, visually highlighting the MRI regions that have the greatest impact on each prediction. This interface makes the predictive model accessible and interpretable to a wider audience.

This repository provides the code for each of these components, enabling replication and further exploration of the methodologies used in this study. The explainable AI-powered model aims not only to improve Alzheimer’s detection but also to offer transparency in model decision-making, facilitating a better understanding of the biological insights behind the predictions.

