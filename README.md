# 🌳 Decision Tree Classifier - Drug Prediction

A complete machine learning mini-project using a Decision Tree classifier to predict which drug to prescribe based on patient data.  
Perfect for beginners who wanna get their hands dirty with real-life classification tasks! 👨‍⚕️💊

---

## 📌 Project Summary

This project uses the `drug200.csv` dataset to build a **Decision Tree Classifier** that predicts the correct drug for a patient based on:

- Age
- Sex
- Blood Pressure
- Cholesterol
- Sodium-to-Potassium ratio

The pipeline includes data preprocessing, model training, prediction, evaluation, and visualization.  
Accuracy? Oh yeah — it's hitting **98%+**, baby! 😎

---

## 📁 Dataset Info

📄 [`drug200.csv`](https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBMDeveloperSkillsNetwork-ML0101EN-SkillsNetwork/labs/Module%203/data/drug200.csv)

- 200 rows × 6 columns
- Label: `Drug`
- Features: `Age`, `Sex`, `BP`, `Cholesterol`, `Na_to_K`

---

## 🛠️ Built With

- Python 🐍
- `pandas`, `numpy` – for data manipulation
- `scikit-learn` – for the classifier and preprocessing
- `matplotlib`, `pydotplus`, `graphviz` – for visualization
- Jupyter Notebook in Google Colab

---

## 🚀 How to Run It

1. Open the notebook in [Google Colab](https://colab.research.google.com/).
2. Run the first cell to mount your Google Drive:
   ```python
   from google.colab import drive
   drive.mount('/content/drive')
