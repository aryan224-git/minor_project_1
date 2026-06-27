<div align="center">

# 🎗️ Breast Cancer Recurrence Prediction

## Minor Project 1 — Supervised Machine Learning

<br>

![Python](https://img.shields.io/badge/Python-3.10-blue?logo=python)
![ML](https://img.shields.io/badge/Machine%20Learning-Random%20Forest-orange)
![Dataset](https://img.shields.io/badge/Dataset-UCI-lightgrey)
![Status](https://img.shields.io/badge/Project-Completed-success)

<br><br>

### 🩺 Predicting Breast Cancer Recurrence Using Machine Learning

**A complete supervised ML project covering data preprocessing, EDA, model training, and evaluation.**

<br>

👨‍💻 **Created By:** Aryan Yadav  
📍 **Location:** Varanasi, Uttar Pradesh, India  
📅 **Date:** June 2026

</div>


---

# 📌 About The Project


Breast cancer recurrence prediction is a real-world medical classification problem.

This project uses **Supervised Machine Learning** to predict whether a patient is likely to experience:

<br>

| Class | Meaning |
|-|-|
| 🟢 0 | No Recurrence Event |
| 🔴 1 | Recurrence Event |

<br>


The project follows a complete Machine Learning workflow:

```
Dataset
   ↓
Cleaning
   ↓
Preprocessing
   ↓
EDA
   ↓
Model Training
   ↓
Evaluation
   ↓
Prediction
```


---

# 🎯 Project Goals


✅ Analyze medical dataset

✅ Handle missing values

✅ Perform feature engineering

✅ Train ML classification model

✅ Evaluate performance

✅ Understand model limitations


---

# 📊 Dataset Details


### Dataset Source

🔗 UCI Machine Learning Repository  
Breast Cancer Dataset


<br>

| Information | Details |
|-|-|
| Total Records | 286 |
| Features | 9 |
| ML Type | Binary Classification |
| Data Type | Numerical + Categorical |
| Missing Values | Yes |


### Features

```
age
menopause
tumor-size
inv-nodes
node-caps
deg-malig
breast
breast-quad
irradiat
```


---

# 📂 Project Structure


```
minor_project_1

│
├── 📁 data
│      └── breast-cancer.csv
│
├── 📁 model
│      └── random_forest_model.pkl
│
├── 📁 notebook
│      └── breast_cancer_prediction.ipynb
│
├── 📁 results
│      ├── class_distribution.png
│      └── confusion_matrix.png
│
└── README.md
```


---

# 🧹 Data Preprocessing


The dataset required preprocessing before training.


### Steps Performed:


### 1️⃣ Missing Value Handling

```
Categorical → Mode

Numerical → Median
```


### 2️⃣ Feature Encoding

Categorical values converted using:

```
One Hot Encoding
```


### 3️⃣ Data Splitting

```
Training Data : 80%

Testing Data  : 20%
```


---

# 🔍 Exploratory Data Analysis


The dataset distribution:


```
No Recurrence Events : 201

Recurrence Events    : 85
```


The dataset is imbalanced:

```
70% → No Recurrence

30% → Recurrence
```


Therefore:

⭐ Accuracy alone is not enough.

Important metrics:

- Precision
- Recall
- F1 Score


---

# 🤖 Machine Learning Model


## 🌲 Random Forest Classifier


Used Model:


```python
RandomForestClassifier(
    n_estimators = 300
)
```


### Why Random Forest?


✔ Handles complex patterns

✔ Works well with tabular data

✔ Reduces overfitting

✔ Supports categorical features

✔ Good classification performance


---

# ⚙️ ML Pipeline


```
              Dataset

                 ↓

       Feature Selection

                 ↓

       Missing Value Fix

                 ↓

        Data Encoding

                 ↓

        Train/Test Split

                 ↓

       Random Forest Model

                 ↓

            Prediction

                 ↓

          Evaluation
```


---

# 📈 Model Results


Test Data:

```
58 Samples
```


Performance:


| Metric | Score |
|-|-|
| Accuracy | ⭐ 74.1% |
| Precision | 58.3% |
| Recall | 41.2% |
| F1 Score | 48.3% |


---

# 📊 Confusion Matrix


```

                 Predicted


                 0       1


Actual 0        36      5


Actual 1        10      7

```


Meaning:


| Value | Count |
|-|-|
| True Negative | 36 |
| False Positive | 5 |
| False Negative | 10 |
| True Positive | 7 |


---

# 🧠 Model Analysis


The model achieved:

## 🎯 Accuracy

```
74.1%
```


However, medical prediction requires focus on:

## Recall


The recurrence class recall:

```
41.2%
```


This means some recurrence cases were missed.


Possible improvements:


🚀 Class balancing

🚀 SMOTE oversampling

🚀 Hyperparameter tuning

🚀 Threshold optimization


---

# 🚀 How To Run


## Clone Repository


```bash
git clone https://github.com/aryan224-git/minor_project_1.git

cd minor_project_1
```


## Install Libraries


```bash
pip install pandas numpy scikit-learn matplotlib seaborn joblib
```


## Run Notebook


```bash
jupyter notebook
```


Open:


```
notebook/breast_cancer_prediction.ipynb
```


---

# 🔮 Load Trained Model


```python
import joblib


model = joblib.load(
"model/random_forest_model.pkl"
)


prediction = model.predict(data)

```


---

# 🛠️ Technologies Used


| Technology | Usage |
|-|-|
| 🐍 Python | Programming |
| 📊 Pandas | Data Handling |
| 🔢 NumPy | Calculations |
| 🤖 Scikit-learn | ML Model |
| 📈 Matplotlib | Visualization |
| 🎨 Seaborn | EDA |
| 💾 Joblib | Saving Model |


---

# 📚 References


📌 UCI Machine Learning Repository

📌 Scikit-learn Documentation

📌 Pandas Documentation

📌 Matplotlib Documentation

📌 Seaborn Documentation


---

<div align="center">


# ⭐ Minor Project 1

## Supervised Machine Learning


**Built with Python + Machine Learning 🚀**


</div>
