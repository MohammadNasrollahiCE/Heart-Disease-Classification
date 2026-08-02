# Heart Disease Classification using Decision Tree 🌳❤️

A machine learning classification project that predicts the presence of heart disease using a Decision Tree Classifier.

The purpose of this project is to practice the complete machine learning workflow, including data exploration, data preprocessing, model training, and evaluation.

> ⚠️ Disclaimer: This project is created for educational purposes only and should not be used for medical diagnosis or real-world clinical decisions.

---

## 📌 Project Overview

Heart disease is one of the most common health problems worldwide. In this project, a machine learning model is developed to classify whether a patient is likely to have heart disease based on clinical attributes.

The project follows a typical machine learning pipeline:

- Loading and understanding the dataset
- Exploratory Data Analysis (EDA)
- Data cleaning
- Data preprocessing
- Model training
- Model evaluation

---

## 📂 Dataset

The dataset contains clinical information about patients and is used for a binary classification task.

### Target Variable

| Value | Meaning |
|---|---|
| 0 | No heart disease |
| 1 | Presence of heart disease |

### Features

The dataset includes medical attributes such as:

- Age
- Sex
- Chest pain type
- Resting blood pressure
- Cholesterol level
- Maximum heart rate achieved
- Exercise-induced angina
- ST depression (Oldpeak)
- Slope
- Number of major vessels
- Thalassemia
- Other clinical measurements

---

## 🔍 Exploratory Data Analysis (EDA)

The dataset was initially inspected to understand its structure and characteristics.

The following analyses were performed:

- Dataset preview using `head()`
- Dataset information using `info()`
- Statistical summary using `describe()`
- Checking data types
- Checking missing values
- Detecting duplicate samples

During data cleaning:

- One duplicate record was detected and removed.
- No further data cleaning was required.

Data visualization was performed using **Matplotlib** and **Seaborn** to analyze feature distributions and relationships between variables.

---

## 🛠️ Data Preprocessing

The following preprocessing steps were applied:

1. Removed duplicate records
2. Separated features and target variable
3. Split the dataset into training and testing sets
4. Applied feature normalization

The dataset was divided into:

- Training data
- Testing data

to evaluate the model's ability to generalize to unseen data.

---

## 🤖 Machine Learning Model

### Decision Tree Classifier

A Decision Tree Classifier was used for this classification task.

Decision Trees are suitable for this type of problem because they:

- Can model non-linear relationships
- Are easy to interpret
- Provide insight into feature importance

---

## 📊 Model Evaluation

The trained model was evaluated using:

- Accuracy Score
- Confusion Matrix
- Classification Report

### Results

**Prediction Accuracy = 0.82**


### Classification Report

| Class | Precision | Recall | F1-score | Support |
|---|---:|---:|---:|---:|
| 0 | 0.75 | 0.93 | 0.83 | 29 |
| 1 | 0.92 | 0.72 | 0.81 | 32 |

Overall performance:


---

## 📉 Confusion Matrix

The confusion matrix was used to analyze the prediction results:

- True Positive (TP) = 23
- True Negative (TN) = 27
- False Positive (FP) = 9
- False Negative (FN) = 2

This provides a better understanding of model performance beyond accuracy alone.

---

## 🧰 Technologies Used

- Python
- NumPy
- Pandas
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

## 📁 Project Structure

Classification/
│
├── Heart-Disease-Class-DecisionTree.ipynb
│
├── README.md
│
└── dataset/
    └── HeartDisease.csv


---

## 🚀 Future Improvements

Possible improvements for this project:

### Model Comparison

Train and compare multiple classification algorithms:

- Logistic Regression
- K-Nearest Neighbors (KNN)
- Support Vector Machine (SVM)
- Random Forest
- XGBoost

### Model Optimization

Apply:

- Cross Validation
- GridSearchCV
- RandomizedSearchCV

### Additional Evaluation

Add:

- ROC-AUC Curve
- Precision-Recall Curve
- More detailed error analysis

### Explainability

Improve model interpretation using:

- Feature Importance
- SHAP values

### Deployment

Create a simple web application using:

- Streamlit
- Flask

to allow users to input patient information and receive predictions.

---

## 👤 Author

**Mohammad Nasrollahi**

GitHub:  
https://github.com/MohammadNasrollahiCE
