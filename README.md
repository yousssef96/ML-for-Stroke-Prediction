# Description

The goal of this project is to predict the risk of stroke in patients using supervised machine learning models. Using a combination of demographic, health, and lifestyle features, the models aim to classify whether a patient is likely to experience a stroke. This project demonstrates preprocessing, feature selection, handling class imbalance, and model evaluation using Logistic Regression and Support Vector Machines (SVM).

# Context

Stroke is a leading cause of death and disability worldwide. Early detection and prediction of stroke risk can help healthcare providers take preventive measures, prioritize high risk patients, and improve overall patient outcomes. Machine learning models can leverage patient data such as age, BMI, glucose levels, heart disease, hypertension, and lifestyle factors to provide more accurate predictions than traditional subjective assessments.

Healthcare datasets are often imbalanced, with relatively few stroke cases compared to non-stroke cases. This poses challenges for traditional metrics like accuracy, so this project uses Matthews Correlation Coefficient (MCC) to evaluate model performance in a balanced way.

# Potential Impact

A successful model could help doctors and healthcare systems identify patients at higher risk of stroke, allowing early intervention, personalized treatment plans, and better allocation of medical resources. More broadly, predictive models like these can assist in public health planning and reduce the burden of stroke related healthcare costs.

# Evaluation
Model performance is evaluated using:

- Matthews Correlation Coefficient (MCC) : balances all outcomes of the confusion matrix, ideal for imbalanced datasets.

- ROC Curve and AUC : measures the model’s ability to discriminate between stroke and non-stroke cases.

- Confusion Matrix : visualizes true positives, true negatives, false positives, and false negatives.

- Cross-Validation : ensures robust evaluation across multiple subsets of the training data.
