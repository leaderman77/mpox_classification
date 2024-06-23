# MPOX Virus Prediction Model
# Introduction
This project develops a machine learning-based predictive model for detecting MPOX virus infections, focusing on minimizing the use of expensive PCR tests by employing symptom-based predictions.
# Background
Detailing the significance of the project in the context of the recent global outbreaks and the need for cost-effective, rapid diagnostic methods.

# Dataset Description
The dataset used for the MPOX virus prediction model consists of 18,849 rows, with each row representing a patient's test and health-related data. The dataset is structured with the following columns:

- Test ID: Unique identifier for each test sample.
- Systemic Illness: Indicators of systemic illness symptoms.
- Encoded Systemic Illness: Numerically encoded systemic illness symptoms for model processing.
- Rectal Pain: Presence of rectal pain (True/False).
- Sore Throat: Presence of sore throat (True/False).
- Penile Oedema: Presence of penile oedema (True/False).
- Oral Lesions: Presence of oral lesions (True/False).
- Solitary Lesion: Presence of solitary lesion (True/False).
- Swollen Tonsils: Presence of swollen tonsils (True/False).
- HIV Infection: HIV infection status (True/False).
- Red blood cells count: Count of red blood cells.
- White blood cells count: Count of white blood cells.
- Home ownership: Indicates if the patient owns a home (1: Yes, 0: No).
- Age: Age of the patient.
- Month of Birth: Birth month of the patient.
- Health Insurance: Indicates if the patient has private health insurance (1: Yes, 0: No).
- Sexually Transmitted Infection: History of sexually transmitted infections.
- MPOX PCR Result: Result of the MPOX PCR test (Positive/Negative).

The dataset labels each instance as "Negative" or "Positive," indicating whether a patient is infected with the MPOX virus. This data is essential for training the predictive model to accurately classify potential MPOX infections based on the symptoms and other health indicators provided.

# Project Scope and Methodology
## Task 1: Domain Understanding - Classification
- Objective: Identify which data attributes to retain or drop for effective classification modeling.
- Approach: Analyzed each variable to determine its relevance and logical applicability to the MPOX classes.
- Outcome: Developed a streamlined dataset focusing on the most impactful attributes for predicting MPOX.
## Task 2: Data Understanding
- Objective: Perform exploratory data analysis on retained variables.
- Approach: Generated statistical summaries and visualizations to understand data distributions and relationships.
- Outcome: Insights from this task informed the preprocessing steps and highlighted potential predictive variables.
## Task 3: Data Preparation
- Objective: Clean and transform the dataset to prepare it for modeling.
- Approach: Identified and resolved issues in the dataset using Python for data cleaning and feature engineering.
- Outcome: A cleaned and optimized dataset ready for predictive modeling, with documented pre and post-transformation states.
## Task 4: Modeling
- Objective: Build and compare multiple classification models using different algorithms.
- Approach: Selected Naïve Bayes, Decision Trees, Logistic Regression, and SVM for their varied characteristics. Adjusted model hyperparameters and assessed their impact.
- Outcome: Each model was evaluated based on its ability to predict MPOX, focusing on maximizing the detection of positive cases.
## Task 5: Evaluation
- Objective: Evaluate model performance against specific success criteria.
- Approach: Used metrics like Recall, Precision, and F-Measure to assess each model's ability to identify MPOX positives effectively.
- Outcome: Identified the best-performing model(s) based on the ability to predict MPOX positive cases, aligning with the healthcare professionals' needs.
# Results and Findings
- Best Model: Decision on the best model based on recall, precision, and overall accuracy.
- Performance Enhancement: Discussion on hyperparameter tuning and its effects on model performance.
- Ensemble Learning: Explored the potential of combining models to improve prediction accuracy.
# Future Work
Suggestions for future enhancements include integrating more diverse data, implementing advanced machine learning techniques, and continuous model training with new data.

# Usage
Instructions on setting up the project, installing dependencies, and running the models are provided to ensure reproducibility.

# Challenges and Learnings
Discussed the complexities of dealing with imbalanced data, the importance of feature selection, and the impact of data quality on predictive accuracy.

# Ethical Considerations
- Addressed potential ethical concerns regarding the deployment of AI in healthcare diagnostics, emphasizing transparency and fairness.
