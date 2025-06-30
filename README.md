# ❤️ Heart Disease Prediction Project

This project predicts the presence of heart disease in patients using machine learning models built and run in Google Colab.  
The dataset is a well-known heart disease dataset that combines four databases

---

## 📊 Dataset Overview

This dataset contains **14 key attributes** (from an original 76) that are most commonly used for heart disease prediction:

- **age**: Age of the patient
- **sex**: Gender (1 = male; 0 = female)
- **cp**: Chest pain type (4 values)
- **trestbps**: Resting blood pressure (in mm Hg)
- **chol**: Serum cholesterol in mg/dl
- **fbs**: Fasting blood sugar > 120 mg/dl (1 = true; 0 = false)
- **restecg**: Resting electrocardiographic results (values 0, 1, 2)
- **thalach**: Maximum heart rate achieved
- **exang**: Exercise induced angina (1 = yes; 0 = no)
- **oldpeak**: ST depression induced by exercise relative to rest
- **slope**: Slope of the peak exercise ST segment
- **ca**: Number of major vessels (0–3) colored by fluoroscopy
- **thal**: 0 = normal; 1 = fixed defect; 2 = reversible defect
- **target**: 0 = no heart disease; 1 = heart disease

---

## 🧩 **Project Goal**

To develop a machine learning model that can predict whether a patient has heart disease (target = 1) or not (target = 0) based on the 13 clinical features.

---

## 📌 **How to Run**

1. Open `heart_disease_prediction.ipynb` in [Google Colab](https://colab.research.google.com/).
2. Run each cell in order to:
   - Load and explore the dataset.
   - Visualize the data (correlation heatmap, feature distributions).
   - Train and evaluate machine learning models.
   - Check model performance metrics.

---

## ⚙️ **Requirements**

- Python 3.x
- pandas
- numpy
- seaborn
- matplotlib
- scikit-learn

---

## 📁 **Files**

- `heart_disease_prediction.ipynb` — Main Colab notebook with code and analysis.
- `README.md` — This file.

---

## 📅 **Source**

- Often referred to as the **Cleveland Heart Disease dataset**, which is the most commonly used portion.

---
