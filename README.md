# 🎯 Predicting Student Test Scores — Kaggle Competition

Machine Learning project focused on predicting student exam performance using regression models and ensemble learning techniques.

This project is based on the Kaggle competition:

🏆 **Playground Series — Season 6, Episode 1**

The objective is to accurately predict a student’s `Exam_score` (0–100) using demographic, academic, and behavioral features.

---

# 📌 Project Overview

This repository demonstrates an end-to-end machine learning workflow, including:

✅ Exploratory Data Analysis (EDA)
✅ Data preprocessing
✅ Feature engineering
✅ Regression modeling
✅ Cross-validation
✅ Pipeline optimization
✅ Model evaluation and improvement

The project begins with baseline regression models and progressively improves performance through better preprocessing strategies and validation techniques.

---

# 📂 Dataset Information

📎 Competition Source:
https://www.kaggle.com/competitions/playground-series-s6e1

## 🏋️ Training Dataset

| Property          | Value        |
| ----------------- | ------------ |
| Observations      | 630,000      |
| Features          | 12           |
| Target Variable   | `Exam_score` |
| Additional Column | `id`         |

---

## 🧪 Test Dataset

| Property        | Value        |
| --------------- | ------------ |
| Observations    | 270,000      |
| Features        | 12           |
| Target Variable | Not included |

The test set is used for generating competition submissions.

---

# 🧠 Notebook Overview

The project is divided into the following notebooks:

## 📓 `pred_score_eda.ipynb`

This notebook was created primarily to conduct exploratory data analysis (EDA) and evaluate baseline models in order to establish an initial benchmark score.
To achieve this, the notebook contains the core exploratory and modeling workflow, including:

### 🔍 Exploratory Data Analysis

* Feature distributions
* Correlation analysis
* Outlier detection
* Target variable exploration

### ⚙️ Data Preprocessing

* Handling categorical variables
* Missing value inspection
* Feature scaling and transformations

### 🤖 Modeling

* Baseline regression models
* Cross-validation setup
* Performance evaluation

### 📊 Evaluation

Models are evaluated using standard regression metrics and Kaggle leaderboard performance.


#### 📌 Baseline Score

| Model    | Public Score |
| -------- | ------------ |
| LightGBM | **8.809787** |

---

## 📓 `pred_score_fe.ipynb`

Building upon the previous notebook, this notebook focuses on advanced feature engineering and model optimization to improve overall performance and achieve a higher competition score.
As a result, the notebook contains the following sections:

### ⚙️ Data Preprocessing

* Handling categorical variables
* Feature scaling and transformations

### Improvements Added

* Scikit-learn Pipelines
* K-Fold Cross Validation
* Better preprocessing workflow

#### 📌 Achieved score

| Model    | Public Score |
| -------- | ------------ |
| LightGBM | **8.756784** |

---

# 🛠️ Technologies Used

| Category         | Tools                           |
| ---------------- | ------------------------------- |
| Programming      | Python                          |
| Data Analysis    | Pandas, NumPy                   |
| Visualization    | Matplotlib, Seaborn             |
| Machine Learning | Scikit-learn, LightGBM, XGBoost |
| Deep Learning    | TensorFlow                      |
| Environment      | Jupyter Notebook                |

---

# 💡 Skills Demonstrated

This project highlights practical machine learning and data science skills, including:

* 📊 Exploratory Data Analysis (EDA)
* 🧹 Data Cleaning & Preprocessing
* 🏗️ Feature Engineering
* 📉 Regression Modeling
* 🔁 Cross-Validation
* ⚡ Ensemble Learning
* 🧠 Neural Networks
* 📈 Model Evaluation & Optimization
* 🧪 Experimentation Workflow

