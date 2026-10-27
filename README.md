Cardiovascular Disease Prediction Using Machine Learning:
An Empirical Benchmark, Physiological Sanitization, and Clinical
Interpretability Analysis

Abstract—Cardiovascular diseases (CVDs) remain the predominant etiology of premature global mortality, accounting for
approximately 17.9 million annual deaths according to the World Health Organization. While routine non-invasive clinical
examinations capture essential demographic, hemodynamic, biochemical, and behavioral risk markers, raw patient registries
frequently suffer from recording anomalies, uncalibrated physiological boundaries, and high-dimensional non-linear
interactions that hinder standard clinical scoring. In this study, we present a scientifically validated, leak-free machine learning
framework for automated cardiovascular risk stratification evaluated on an expansive cohort of 70,000 patient examination
records. We establish a physiologically grounded cleaning protocol that enforces biological pressure and stature plausibility
boundaries, pruning 1,387 erroneous records (1.98%) while preserving 98.02% of genuine observations (N = 68,613) and
maintaining an ideal natural class distribution (50.53% healthy vs. 49.47% diseased). Furthermore, we engineer standardized
clinical biomarkers—including Quetelet Body Mass Index (BMI), chronological age in clinical years, and arterial pulse
pressure (∆P)—to quantify vascular stiffness and hemodynamic burden. Benchmarking five foundational supervised machine
learning paradigms (Logistic Regression, K-Nearest Neighbors, Decision Trees, Random Forest, and Calibrated Support
Vector Machines) under an 80/20 stratified partition (N_test = 13,723) reveals that the Random Forest ensemble emerges as the
champion architecture. It attains an overall test classification accuracy of 73.30%, an Area Under the Receiver Operating
Characteristic Curve (ROC-AUC) of 0.8003, a precision of 76.20%, and a specificity of 79.54%. Mean Decrease in Impurity
(Gini MDI) analysis reveals that hemodynamic indicators—specifically systolic blood pressure (34.06%), diastolic blood
pressure (17.27%), and arterial pulse pressure (13.44%)—account for approximately 64.77% of total predictive power,
corroborating hemodynamic arterial stiffness as the primary non-invasive determinant of cardiovascular pathology. Finally, the
calibrated pipeline is demonstrated across diverse simulated clinical patient profiles and integrated into an interactive clinical
dashboard for reproducible point-of-care screening.
