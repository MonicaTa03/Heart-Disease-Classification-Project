# Heart-Disease-Classification-Project
A Logistic Regression model to predict heart disease using UCI dataset
# 🫀 Heart Disease Classification Project

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![Library](https://img.shields.io/badge/Library-Scikit--Learn-orange)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)

## 📌 Project Overview (Tổng quan)
This project aims to build a machine learning model to predict whether a patient has heart disease based on their medical attributes (Age, Cholesterol, Blood Pressure, etc.). The dataset is sourced from the [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/heart+disease).

## 🛠️ Tech Stack (Công nghệ sử dụng)
* **Language:** Python
* **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Scikit-Learn
* **Model:** Logistic Regression

## 📊 Workflow (Quy trình)
1.  **Data Loading:** Imported dataset from Kaggle.
2.  **EDA (Exploratory Data Analysis):** Analyzed distributions and correlations.
3.  **Preprocessing:**
    * Handling missing values.
    * **Scaling:** Used `StandardScaler` for numerical features.
    * **Encoding:** Used `OneHotEncoder` for categorical variables.
4.  **Modeling:** Trained a Logistic Regression model.
5.  **Evaluation:** Evaluated using Accuracy, Precision, Recall, F1-Score, and ROC-AUC.

## 📈 Key Results (Kết quả)
Here are the performance metrics of the model on the Test set:

| Metric | Score |
| :--- | :--- |
| **Accuracy** | **0.85** (Thay số của bạn vào) |
| **Precision** | 0.82 (Thay số của bạn vào) |
| **Recall** | 0.88 (Thay số của bạn vào) |
| **F1-Score** | 0.85 (Thay số của bạn vào) |

> **Insight:** The model achieved a high Recall score, which is crucial in medical diagnosis to minimize False Negatives.

## 📷 Visuals
*(Sau khi bạn chạy code xong, hãy chụp màn hình cái "Confusion Matrix" và "Correlation Heatmap" rồi dán ảnh vào đây)*

## 📬 Contact
Created by [Tên của bạn] - Feel free to contact me!
