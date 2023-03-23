# Predicting-the-Length-of-Hospital-Stays
For the final project of the course Deep Learning. I predict the length of stay from hospital data. I am using Tree Models, Ensembles, and a Neural Network.

Length of stay prediction
In this project, you have to predict the length of stay (in days) of a patient that is entering an ICU (Intensive Care Unit) using decision tree models.

The dataset comes from MIMIC project (https://mimic.physionet.org/). MIMIC-III (Medical Information Mart for Intensive Care III) is a large, freely-available database comprising deidentified health-related data associated with over forty thousand patients who stayed in critical care units of the Beth Israel Deaconess Medical Center between 2001 and 2012.

Each row of mimic_train.csv corresponds to one ICU stay (hadm_id+ icustay_id) of one patient (subject_id). Column HOSPITAL_EXPIRE_FLAG is the indicator of death (=1) as a result of the current hospital stay; this is the outcome to predict in our modelling exercise. The remaining columns correspond to vitals of each patient (when entering the ICU), plus some general characteristics (age, gender, etc.), and their explanation can be found at mimic_patient_metadata.csv.

Please don't use any feature that you infer you don't know the first day of a patient in an ICU, e.g. HOSPITAL_EXPIRE_FLAG


You can follow those steps in your first implementation:

1) Explore and understand the dataset.
2) Manage missing data.
3) Manage categorical features. E.g. create dummy variables for relevant categorical features, or build an ad hoc distance function.
4) Build a prediction model
5) Assess expected accuracy of previous models using cross-validation.
6) Predict on the test file, following same preparation steps (missing data, dummies, etc). Remember that you should be able to yield a prediction for all the rows of the test dataset. Submit to Kaggle to check performance.
