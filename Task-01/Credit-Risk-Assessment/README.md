# 🏦 Task 01: Credit Risk Assessment & Classification

An end-to-end Machine Learning pipeline developed to evaluate financial credit risk and predict loan defaults. Built using Python and Scikit-Learn on Kaggle as part of the **CodeAlpha Data Science Internship**.

---

## 📌 Project Overview

Credit risk modeling is crucial for financial institutions to assess the likelihood of a borrower defaulting on a loan. In this project, multiple machine learning algorithms—including **Random Forest**, **Decision Trees**, and **Logistic Regression**—were trained and evaluated on a credit risk dataset to classify high-risk vs. low-risk applicants.

---

## 🛠️ Tech Stack & Dependencies

* **Language:** Python
* **Data Processing & Scaling:** Pandas, NumPy, Scikit-Learn (`StandardScaler`)
* **Machine Learning:** Scikit-Learn (Logistic Regression, Decision Tree, Random Forest)
* **Data Visualization:** Matplotlib, Seaborn
* **Model Persistence:** Joblib
* **Environment:** Kaggle Notebooks / Jupyter Notebook

---

## 📊 Workflow & Methodology

1. **Data Preprocessing & Feature Engineering:**
   * Cleaned dataset and handled missing value distributions.
   * Scaled numerical features (`income`, `age`, `loan_amount`, etc.) using **`StandardScaler`**.

2. **Exploratory Data Analysis (EDA):**
   * Visualized applicant demographic features and loan metric correlations.
   * Evaluated feature importance and distribution trends across default vs. non-default classes.

3. **Model Training & Comparison:**
   * **Logistic Regression:** Linear classification baseline.
   * **Decision Tree Classifier:** Non-linear decision rules baseline.
   * **Random Forest Classifier:** Optimized ensemble algorithm for robust default risk classification.

4. **Evaluation Metrics:**
   * Assessed performance using **Accuracy, Precision, Recall, F1-Score, and Confusion Matrices**.

---

## 🚀 How to Run Locally

1. **Clone and Open Credit Risk Assessment Directory:**
   ```bash
   git clone [https://github.com/mhammadmustafa/CodeAlpha-Machine-Learning-Tasks.git](https://github.com/mhammadmustafa/CodeAlpha-Machine-Learning-Tasks.git) && cd CodeAlpha-Machine-Learning-Tasks/Credit-Risk-Assessment
