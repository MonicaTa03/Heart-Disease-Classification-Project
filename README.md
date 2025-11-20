# Heart-Disease-Classification-Project
A Logistic Regression model to predict heart disease using UCI dataset
# 🫀 Heart Disease Classification Project

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![Library](https://img.shields.io/badge/Library-Scikit--Learn-orange)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)

---

## 📑 Table of Contents
- [📍 Overview](#-overview)
- [📂 Project Structure](#-project-structure)
- [⚙️ The Workflow](#-the-workflow)
- [🏆 Key Results (Highlights)](#-key-results-highlights)
- [📊 Visualizations](#-visualizations)
- [🚀 Future Scope](#-future-scope)

---

## Project Overview 
This project aims to build a machine learning model to predict whether a patient has heart disease based on their medical attributes (Age, Cholesterol, Blood Pressure, etc.). The dataset is sourced from the [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/heart+disease).



## 📂 Project Structure
Here is how the project is organized:
├── data
│   └── heart.csv          # The dataset (UCI Machine Learning Repository)
├── notebooks
│   └── Heart_Disease_Prediction.ipynb   # The main Jupyter Notebook
├── images
│   ├── confusion_matrix.png
│   └── correlation_heatmap.png
└── README.md              # This file



## Tech Stack 
* **Language:** Python
* **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Scikit-Learn
* **Model:** Logistic Regression



## Workflow 
1.  **Data Loading:** Imported dataset from Kaggle.
2.  **EDA (Exploratory Data Analysis):** Analyzed distributions and correlations.
3.  **Preprocessing:**
    * Handling missing values.
    * **Scaling:** Used `StandardScaler` for numerical features.
    * **Encoding:** Used `OneHotEncoder` for categorical variables.
4.  **Modeling:** Trained a Logistic Regression model.
5.  **Evaluation:** Evaluated using Accuracy, Precision, Recall, F1-Score, and ROC-AUC.



## Key Results 
| Metric | Score | Note |
| :--- | :--- | :--- |
| **Accuracy** | 0.9016 | Correctly diagnosed 9 out of 10 patients|
| **Precision** | 0.9333| Highly reliable when predicting disease |
| **Recall** | 0.8750   | Detected most positive cases successfully |
| **F1-Score** | 0.9032 | Excellent separation between classes |
| **ROC-AUC** | 0.9418  | |
> **Insight:** The model achieved a high Recall score, which is crucial in medical diagnosis to minimize False Negatives.



## Visuals

<img width="697" height="517" alt="Image" src="https://github.com/user-attachments/assets/2a81aac3-b2e8-4956-8b60-7d797ed0253d" />

<img width="501" height="469" alt="Image" src="https://github.com/user-attachments/assets/02731b3b-513f-4bce-8845-ba476d072775" />

<img width="575" height="453" alt="Image" src="https://github.com/user-attachments/assets/6154cdc2-9ac1-4120-81ac-8a66096a5ebe" /> 


## 📬 Contact
Created by **Ta Nguyen Nghi Phuong** - Feel free to contact me!
