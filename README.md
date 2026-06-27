🩺 Breast Cancer Diagnosis Prediction Using Supervised Machine Learning
<p align="center">
<img src="https://img.shields.io/badge/Project-Machine%20Learning-blue?style=for-the-badge" />
<img src="https://img.shields.io/badge/Model-Random%20Forest-green?style=for-the-badge" />
<img src="https://img.shields.io/badge/Dataset-UCI%20Breast%20Cancer-orange?style=for-the-badge" />
<img src="https://img.shields.io/badge/Status-Completed-success?style=for-the-badge" />
</p>

📌 Overview
This project predicts whether a breast cancer case is a no-recurrence-event or a recurrence-event using supervised machine learning. The workflow includes data preprocessing, exploratory data analysis, model training, and evaluation.

📂 Dataset
The dataset used is the Breast Cancer dataset from the UCI Machine Learning Repository.

It contains:

286 samples

9 input features

2 target classes

no-recurrence-events

recurrence-events

Dataset link:
UCI Breast Cancer Dataset

🎯 Objective
The objective of this project is to build a machine learning model that can predict breast cancer recurrence based on patient and tumor-related attributes.

🛠️ Model Used
Random Forest Classifier
Random Forest was selected because:

It performs well on tabular data.

It handles non-linear feature relationships effectively.

It reduces overfitting compared to a single decision tree.

It works well after encoding categorical variables.

📊 Features
The dataset includes:

age

menopause

tumor-size

inv-nodes

node-caps

deg-malig

breast

breast-quad

irradiat

⚙️ Workflow
Load the UCI dataset.

Check missing values.

Encode the target labels.

Impute missing values.

One-hot encode categorical features.

Split data into training and testing sets.

Train the Random Forest model.

Evaluate using classification metrics.

📈 Evaluation Metrics
The project uses:

Accuracy

Precision

Recall

F1-Score

Confusion Matrix

Final Results
Accuracy: 0.7414

Precision: 0.5833

Recall: 0.4118

F1-Score: 0.4828

🧠 Conclusion
This project demonstrates how supervised machine learning can be used for breast cancer recurrence prediction. Random Forest provides a strong and practical approach for this tabular medical dataset.

📁 Project Structure
bash
project-folder/
├── Minor_Project_1.ipynb
├── Minor_Project_1_Report.docx
├── README.md
└── requirements.txt
▶️ How to Run
bash
pip install ucimlrepo pandas scikit-learn seaborn matplotlib
Then run the notebook in Google Colab or Jupyter Notebook.

📚 References
UCI Machine Learning Repository: Breast Cancer Dataset

scikit-learn Random Forest documentation

pandas documentation

seaborn documentation

matplotlib documentation
