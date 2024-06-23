# MPOX Virus Prediction Model
# Introduction
This project develops a machine learning-based predictive model for detecting MPOX virus infections, focusing on minimizing the use of expensive PCR tests by employing symptom-based predictions.
# Background
Detailing the significance of the project in the context of the recent global outbreaks and the need for cost-effective, rapid diagnostic methods.

# Project Workflow
## Task 1: Domain Understanding - Classification
- Objective: Focus solely on classification modeling.
- Variable Selection:
- Retained: Systemic Illness, Sore Throat, Rectal Pain, Oral Lesions, HIV Infection, Red blood cells, White blood cells, Age, Health Insurance.
- Dropped: Test ID, Home ownership, Month of Birth, Sexually Transmitted Infection.
## Task 2: Data Understanding
- Statistical Analysis: Basic statistical descriptions and distribution plots for retained variables.
- Visual Outputs: Screenshots of the class variable distributions (included in the repository).
## Task 3: Data Preparation
- Data Issues & Solutions:
- Organized findings of data quality issues and implemented corrections.
- Example: Variable "Red blood cells" had outliers; solutions included applying normalization techniques.
- Implementation Evidence: Screenshots before and after data corrections.
## Task 4: Modelling
- Selected Algorithms: Naïve Bayes, Decision Tree, Logistic Regression, and SVM with RBF kernel.
- Algorithm Details:
-- Type (Parametric/Non-parametric), learnable parameters, hyperparameters considered for tuning.
- Model Building:
-- Features used, training-test split justification, and ensuring consistent labels ratio across datasets.
## Task 5: Evaluation
- Success Criteria: Focus on high recall to ensure positive cases are not missed.
- Model Evaluation:
-- Test confusion matrices for each model.
-- Selection of relevant evaluation metrics based on success criteria (e.g., Recall, F-Measure).
- Best Model Selection:
-- Discussion on which models best meet the healthcare professionals' needs.
- Hyperparameter tuning results and performance comparison.
# Enhancements
- Ensemble Learning: Justification and results from combining learners in a voting ensemble.
- Model Critique & Limitations: Analysis of the best model's performance, limitations, and potential ethical concerns.
# Technologies Used
- Python, Scikit-Learn, TensorFlow, Pandas, NumPy, Matplotlib, Seaborn.
- Results
- Summary of the model's performance, including key statistics and visualizations demonstrating the efficacy of the predictive model.

# Usage
- Instructions on how to set up, install dependencies, and run the project.

# Challenges and Future Work
- Discussion of challenges faced, learnings from the project, and potential areas for further development.
