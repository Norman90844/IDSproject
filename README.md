# Lung Cancer Survival Prediction with Synthetic Data

Authors: Marten Mathias Jaani, Norman Tolmats, Joosep Lember

The goal of this project is to predict mortality within a one-year period using a workflow that identifies the most important features and returns the most accurate model.

To use these workflows, you can use the Jupyter Notebook file. There, you can enter the name of your data file, and the workflow will find the most important features and return the most accurate model.

To replicate the same analysis, you have to make use of the same data format. This means that you need to have three columns: SUBJECT_ID, DEFINITION_ID, and TIME. SUBJECT_ID is a unique identifier for patients, DEFINITION_ID categorizes the type of medical intervention (drug, measurement, condition, procedure, etc.), and TIME represents the time in years since diagnosis at which the intervention occurred. Once the data is in that format, you should be able to replicate the same type of analysis.
