# LIME_SHAP-from-scratch

This repository contains code for interpreting a diabetes prediction model using two popular interpretability techniques: SHAP (SHapley Additive exPlanations) and LIME (Local Interpretable Model-agnostic Explanations) which are implemented from scratch. 

Overview
The provided code is a Python script demonstrating the interpretation of a diabetes prediction model trained using a RandomForestClassifier. The script uses two techniques, SHAP and LIME, to interpret the predictions of the model and understand the importance of different features in making predictions.

Requirements
To run the code, the following dependencies are required:
scikit-learn
numpy
pandas
matplotlib

Usage
Data Loading and Model Training:
The script loads the diabetes dataset from a CSV file and splits it into features (X) and target variable (y). It then trains a RandomForestClassifier on the dataset.
SHAP Interpretation:

SHAP values are calculated to explain the contribution of each feature to the model's predictions. The script computes SHAP values for a single instance and for the entire test dataset.
SHAP values provide insights into which features are most influential in making predictions.
LIME Interpretation:

LIME values are computed to interpret the predictions of the model on a local level. LIME values explain the importance of each feature for a single instance prediction.
LIME values are calculated for a single instance and for the entire test dataset.

Visualization:
The script includes functions to visualize the SHAP and LIME values as bar graphs. These visualizations help in understanding the relative importance of features in making predictions.

Conclusion
This script provides a comprehensive demonstration of interpreting a diabetes prediction model using SHAP and LIME techniques. By understanding the importance of different features, users can gain insights into how the model makes predictions and identify factors that contribute most significantly to the predictions. Further exploration and analysis can be conducted based on the interpretations provided by these techniques.
