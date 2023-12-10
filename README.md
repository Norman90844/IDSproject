# Lung Cancer Survival Prediction with Synthetic Data

Authors: Marten Mathias Jaani, Norman Tolmats, Joosep Lember

The goal of this project is to predict the likelyhood of a patient's mortality based on medical data using a workflow that identifies the most important features/creates new ones and returns the most accurate model.

To use these workflows, you can use the Jupyter Notebook file 'Cancer Mortality Prediction Workflow.ipynb'. There we have two workflows. You can enter the name of your data file, and the function will output the corresponding graphs describing the model and returns the classifier. The first workflow also has a mortality prediction function. The notebook file 'Real_data_workflow.ipynb' is the same but has been run on real patient data by the instructor.

To replicate the same analysis, you have to make use of the same csv data format. This means that you need to have three columns: SUBJECT_ID, DEFINITION_ID, and TIME. SUBJECT_ID is a unique identifier for patients, DEFINITION_ID categorizes the type of medical intervention (drug, measurement, condition, procedure, etc with unique identifiers), and TIME represents the time in years since diagnosis at which the intervention occurred. Once the data is in that format, you should be able to replicate the same type of analysis.
