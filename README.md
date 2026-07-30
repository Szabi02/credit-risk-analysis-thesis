# Retail Credit Risk Prediction Using Machine Learning

This repository contains an end-to-end machine learning project focused on predicting loan defaults using the Lending Club dataset. The project demonstrates the complete data science workflow, including data preprocessing, feature engineering, model training, evaluation, threshold optimization, and model explainability.

> **Note:** The original Lending Club dataset is **not included** in this repository because it is approximately **2.5 GB**, which exceeds GitHub's practical file size limits. The executed Jupyter Notebook, including all outputs and visualizations, is provided. The dataset can be obtained from publicly available Lending Club data sources.

---

# Project Objectives

The main objective of this project is to build and compare multiple machine learning models for predicting whether a loan will default.

The workflow includes:

- Data loading and exploration
- Data cleaning and preprocessing
- Missing value treatment
- Data leakage detection and feature removal
- Feature engineering
- Stratified sampling
- Class imbalance handling using SMOTE
- Model training
- Hyperparameter tuning
- Threshold optimization
- Model evaluation
- Model explainability using SHAP

---

# Models

The following classification models were implemented and compared:

- Logistic Regression (Baseline)
- Logistic Regression (SMOTE)
- Decision Tree
- Random Forest
- XGBoost

---

# Evaluation Metrics

Model performance was evaluated using:

- ROC-AUC
- Accuracy
- Precision
- Recall
- F1-score

In addition to the default classification threshold, business-oriented threshold optimization was performed for Random Forest and XGBoost to improve recall while maintaining acceptable precision.

---

# Explainable AI

To improve model interpretability, SHAP (SHapley Additive exPlanations) was used to analyze the final XGBoost model.

The notebook includes:

- SHAP Summary Plot
- Feature importance analysis
- Interpretation of feature impact on default prediction

---

# Repository Contents

```
.
├── Lending_Club_Credit_Risk.ipynb
├── README.md
└── requirements.txt
```

- **Lending_Club_Credit_Risk.ipynb** – Executed Jupyter Notebook containing the complete workflow, results, and visualizations.
- **requirements.txt** – Python dependencies required to run the notebook.
- **README.md** – Project documentation.

---

# Running the Project

1. Clone this repository.

```bash
git clone https://github.com/<your_username>/<repository_name>.git
```

2. Install the required packages.

```bash
pip install -r requirements.txt
```

3. Download the Lending Club dataset from a public source.

4. Place the dataset in the project directory.

5. Open and run the notebook.

---

# Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- XGBoost
- SHAP
- imbalanced-learn
- Jupyter Notebook

---

# Project Highlights

- End-to-end machine learning workflow
- Large real-world financial dataset
- Extensive data preprocessing
- Data leakage prevention
- Feature engineering
- Class imbalance handling with SMOTE
- Hyperparameter optimization using RandomizedSearchCV
- Business-oriented threshold optimization
- SHAP explainability
- Comparison of multiple machine learning models

---

# Author

# Author

**Szabolcs Molnár**

Budapest, Hungary
