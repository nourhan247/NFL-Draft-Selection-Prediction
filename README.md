# NFL-Draft-Selection-Prediction
Data:- https://drive.google.com/drive/folders/1SaZeOplJKXEBv4em6s483kXj8K3eh3Pb?usp=drive_link

Developed a machine learning system to predict whether college football players would be selected in the NFL Draft using athletic performance metrics and player profile data.

Conducted comprehensive exploratory data analysis (EDA), including class distribution analysis, correlation analysis, missing value assessment, and performance-based feature investigation.

Engineered domain-specific features such as BMI, athletic score, explosiveness, agility metrics, power-speed ratio, athletic efficiency, school frequency encoding, and position-based ranking features.

Created missing-value indicator features to capture potential information contained in absent measurements.

Tuned XGBoost, LightGBM, and CatBoost models using Optuna hyperparameter optimization with 5-fold Stratified Cross-Validation and ROC-AUC evaluation.

Compared multiple gradient boosting algorithms and achieved strong predictive performance through model selection and validation.

Built a stacked/blended ensemble by combining predictions from XGBoost, LightGBM, and CatBoost, improving overall model robustness and generalization.

Generated competition-ready prediction files for unseen player data and evaluated model performance using ROC-AUC metrics.

Ranked in the Top 20% among participants in the Matsuo Lab (Matsuo Laboratory) NFL Draft Prediction Competition, demonstrating strong model performance in an international machine learning competition.
