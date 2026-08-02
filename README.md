# ❤️ Heart Disease Classification using Machine Learning

A complete end-to-end Machine Learning project for predicting the presence of **heart disease** using two popular supervised learning algorithms:

* 📈 Logistic Regression
* 🌳 Decision Tree

The purpose of this project is not only to build classification models, but also to practice the complete machine learning workflow including data preprocessing, exploratory data analysis, model training, evaluation, and model comparison.

---

## 📌 Project Highlights

✅ Complete Data Preprocessing

✅ Exploratory Data Analysis (EDA)

✅ Logistic Regression with Pipeline , Cross-Validation & Hyperparameter Tuning

✅ Decision Tree Classifier

✅ SVM Classifier

✅ Model Comparison

✅ Performance Evaluation

✅ Reproducible Environment (`requirements.txt`)

---

# 📂 Repository Structure

```text
.
├── dataset/
│   └── heart.csv
│
├── Heart-Disease-Class-LogReg.ipynb
├── Heart-Disease-Class-DecisionTree.ipynb
├── Heart-Disease-Class-SVM.ipynb
│
├── requirements.txt
└── README.md
```

---

# 📊 Dataset

This project uses the **Heart Disease Dataset**, a binary classification dataset containing medical information collected from patients.

### Features include:

* Age
* Sex
* Chest Pain Type
* Resting Blood Pressure
* Cholesterol
* Fasting Blood Sugar
* Resting ECG
* Maximum Heart Rate
* Exercise-Induced Angina
* Oldpeak
* ST Slope
* Number of Major Vessels
* Thalassemia

### Target

| Value | Meaning          |
| ----- | ---------------- |
| 0     | No Heart Disease |
| 1     | Heart Disease    |

---

# 🧹 Data Preprocessing

The following preprocessing steps were performed before training the models:

* Removed duplicate records
* Checked for missing values
* Dataset inspection using `info()` and `describe()`
* Exploratory Data Analysis (EDA)
* Train/Test Split
* Feature Standardization (Logistic Regression only)

---

# 📈 Exploratory Data Analysis

Several visualizations were created to better understand the dataset and identify relationships between features and the target variable.

The analysis includes:

* Feature distributions
* Class distributions
* Correlation analysis
* Medical feature exploration using Seaborn visualizations

---

# 🤖 Models

## 1️⃣ LSVM

A classification algorithm suitable for binary classification tasks.

Workflow
Data Standardization
Model Training with Cross-Validation & Hyperparameter Tuning
Prediction
Evaluation
📈 Result

One interesting observation during experimentation was the impact of feature standardization.

| Before SVM with LR	     After SVM              |
| --------------------------------------------------|
| 85% Accuracy	             87% Accuracy           |

This demonstrates the importance of proper feature scaling when using distance- or optimization-based machine learning algorithms such as SVM.

---

## 1️⃣ Logistic Regression

A linear classification algorithm suitable for binary classification tasks.

### Workflow

* Data Standardization
* Model Training with Pipeline , Cross-Validation & Hyperparameter Tuning
* Prediction
* Evaluation

### 📈 Result

One interesting observation during experimentation was the impact of **feature standardization**.

| Before Logistic Regression | After Logistic Regressio |
| -------------------------- | ------------------------ |
| **82% Accuracy**           | **85% Accuracy**         |

This demonstrates the importance of proper feature scaling when using distance- or optimization-based machine learning algorithms such as Logistic Regression.

---

## 2️⃣ Decision Tree

A tree-based machine learning algorithm capable of learning nonlinear decision boundaries without requiring feature scaling.

### Workflow

* Model Training
* Prediction
* Performance Evaluation

---

# 📊 Evaluation

The models were evaluated using:

* Accuracy Score
* Precision
* Recall
* F1-Score
* Confusion Matrix
* Classification Report

These metrics provide a comprehensive view of model performance beyond simple accuracy.

---

# 🛠 Technologies Used

* Python
* NumPy
* Pandas
* Matplotlib
* Seaborn
* Scikit-learn
* Jupyter Notebook

---

# 🚀 Getting Started

Clone the repository:

```bash
git clone https://github.com/your-username/heart-disease-classification.git
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Launch Jupyter Notebook:

```bash
jupyter notebook
```

---

# 🎯 What I Learned

Through this project, I practiced:

* Data Cleaning
* Exploratory Data Analysis
* Feature Engineering Fundamentals
* Data Standardization
* Binary Classification
* SVM
* Logistic Regression
* Decision Trees
* Model Evaluation
* Comparing Multiple Machine Learning Models

---

# 🔮 Future Improvements

Some possible extensions include:

* Random Forest
* Gradient Boosting
* XGBoost
* LightGBM
* SHAP Explainability

---

# 📄 Requirements

The repository includes a **requirements.txt** file, allowing the project environment to be recreated easily with a single command:

```bash
pip install -r requirements.txt
```

---

# 🤝 Contributing

Contributions, suggestions, and improvements are always welcome.

If you find this project useful, consider giving it a ⭐ on GitHub!

---

# 📜 License

This project is intended for educational and learning purposes.

