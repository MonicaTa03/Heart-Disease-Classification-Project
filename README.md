# 🩺 Heart-Disease-Classification-Project: Can AI Save Lives?

![Python](https://img.shields.io/badge/Python-3.8%2B-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Scikit-Learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white)
![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)
![Status](https://img.shields.io/badge/Status-Completed-success?style=for-the-badge)

> *Predicting the presence of heart disease using Logistic Regression with **90% accuracy** *

---

## Table of Contents
- [Overview](#-overview)
- [Project Structure](#-project-structure)
- [The Workflow](#-workflow)
- [Key Results (Highlights)](#-key-results)
- [Visualizations](#-visualizations)
- [Contact](#-contact)

---

## Overview
Heart disease is one of the leading causes of death globally, that is why early detection is important.
This project use **Machine Learning (Logistic Regression)** to analyze clinical parameters (such as Chest Pain, Cholesterol, Blood Pressure) and predict whether a patient is likely to have heart disease.

**Objective:** Build a model that minimizes False Negatives (as missing a sick patient).

---

## Project Structure
Here is how the project is organized:

```bash
├── data
│   └── heart.csv          
├── notebooks
│   └── Heart_Disease_Prediction.ipynb   
├── images
│   ├── confusion_matrix.png
│   └── correlation_heatmap.png
│   └── ROC curve
└── README.md              
```


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


## Visualizations

<img width="697" height="517" alt="Image" src="https://github.com/user-attachments/assets/2a81aac3-b2e8-4956-8b60-7d797ed0253d" />

<img width="501" height="469" alt="Image" src="https://github.com/user-attachments/assets/02731b3b-513f-4bce-8845-ba476d072775" />

<img width="575" height="453" alt="Image" src="https://github.com/user-attachments/assets/6154cdc2-9ac1-4120-81ac-8a66096a5ebe" /> 


## 📬 Contact
Created by **Ta Nguyen Nghi Phuong** for MachineLearningI

