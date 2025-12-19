# Diabeties-Predication
The objective of this project was to develop a diagnostic tool using Machine Learning to predict the onset of diabetes based on clinical diagnostic measurements. A key focus of the project was optimizing the model’s Recall to ensure that patients who are actually diabetic are correctly identified (minimizing False Negatives).

Key Responsibilities & Highlights:

Advanced Data Cleaning: Identified and addressed data quality issues where physiological measurements (e.g., Glucose, Blood Pressure, Insulin, BMI) were incorrectly recorded as zero. Implemented a pipeline to replace these zeros with statistical means to maintain dataset integrity.

Feature Engineering & Scaling: * Streamlined the feature set by removing non-essential variables to focus on high-impact physiological indicators.

Applied StandardScaler to normalize feature distributions, significantly improving the convergence and performance of the Logistic Regression algorithm.

Probabilistic Classification: Leveraged predict_proba to analyze the confidence levels of model predictions rather than relying on default binary outcomes.

Precision-Recall Trade-off & Threshold Tuning: * Executed Threshold Optimization using the binarize technique.

Iteratively adjusted classification thresholds (from 0.5 down to 0.1) to find the optimal balance that maximizes Recall, aligning the model with the healthcare goal of prioritizing patient detection.

Model Evaluation: Critically evaluated performance using Accuracy, Confusion Matrices, and detailed Classification Reports to track how changes in thresholds impacted the detection of positive cases.
