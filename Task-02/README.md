# 🫀 Task 02: Heart Disease Classification & Risk Prediction

An end-to-end Machine Learning pipeline developed to predict the likelihood of heart disease based on clinical diagnostic parameters. Built using Python, Scikit-Learn, and XGBoost on Kaggle as part of the **CodeAlpha Data Science Internship**.

---

## 📌 Project Overview

Heart disease is one of the leading causes of mortality worldwide. Early detection through predictive analytics allows healthcare providers to identify high-risk patients and intervene proactively. 

In this project, multiple classification algorithms—including **Logistic Regression**, **Random Forest**, **Support Vector Machines (SVM)**, and **XGBoost**—were trained, evaluated, and benchmarked on a clinical heart disease dataset.

---

## 🛠️ Tech Stack & Dependencies

* **Language:** Python
* **Data Processing:** Pandas, NumPy
* **Machine Learning:** Scikit-Learn, XGBoost
* **Data Visualization:** Matplotlib, Seaborn
* **Environment:** Kaggle Notebooks / Jupyter Notebook

---

## 📊 Workflow & Methodology

1. **Data Preprocessing & Scaling:**
   * Handled missing values and verified data integrity.
   * Standardized continuous clinical variables (`age`, `resting_bp`, `cholesterol`, `max_hr`, `oldpeak`) using **`StandardScaler`**.

2. **Exploratory Data Analysis (EDA):**
   * Generated distribution histograms, box plots, and scatter plots to analyze clinical attributes and isolate outliers.
   * Constructed a **Feature Correlation Heatmap** to identify key predictive indicators linked to heart disease targets.

3. **Model Architecture & Benchmark:**
   * **Logistic Regression:** Linear probabilistic baseline model.
   * **Random Forest Classifier:** Ensemble tree-based model (`n_estimators=100`).
   * **Support Vector Machine (SVM):** Non-linear classification via RBF kernel.
   * **XGBoost Classifier:** Advanced gradient boosting for boosted classification accuracy.

4. **Model Evaluation & Validation:**
   * Evaluated models using **Accuracy, Precision, Recall, F1-Score, and Confusion Matrices**.
   * Conducted **5-Fold Cross-Validation (`cross_val_score`)** to ensure model generalization and stability across data splits.
   * Visualized multi-model **ROC Curves (AUC Scores)** and performance comparison charts.

---

## 📈 Key Findings & Results

* **Top Performing Model:** XGBoost / Random Forest (Ensemble methods provided the highest F1-Score and AUC metrics).
* **Key Features:** Maximum heart rate (`max_hr`), ST depression (`oldpeak`), and chest pain type emerged as strong predictors of heart disease risk.

---

## 🚀 How to Run Locally

1. **Clone the Repository:**
   ```bash
## 🚀 How to Run Locally

1. **Clone the Repository:**
   ```bash
   git clone [https://github.com/mhammadmustafa/CodeAlpha-Machine-Learning-Tasks.git](https://github.com/mhammadmustafa/CodeAlpha-Machine-Learning-Tasks.git)
 
