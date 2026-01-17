# Diabetes Prediction using Machine Learning

This repository contains a machine learning project designed to predict the risk of diabetes in patients. By utilizing clinical data such as glucose levels, BMI, and age, the model provides data-driven insights to assist healthcare professionals in early diagnosis and proactive patient care.

---

## 📌 Project Overview
Diabetes is a chronic condition that affects millions of people worldwide. Early detection is critical for effective treatment. This project implements a classification pipeline that analyzes physiological parameters to categorize patients as diabetic or non-diabetic using supervised learning algorithms.

### Key Objectives:
* **Early Detection:** Identify high-risk patients before the onset of severe symptoms.
* **Comparative Analysis:** Evaluate the performance of **Logistic Regression** and **Decision Trees**.
* **Healthcare Support:** Provide a reliable tool for medical practitioners to supplement clinical diagnoses.

---

## 📊 Dataset Features
The model utilizes a dataset containing the following physiological indicators:

| Feature | Description |
| :--- | :--- |
| **Glucose** | Plasma glucose concentration (2 hours in an oral glucose tolerance test). |
| **Blood Pressure** | Diastolic blood pressure (mm Hg). |
| **BMI** | Body Mass Index ($weight\ in\ kg / (height\ in\ m)^2$). |
| **Age** | Patient's age (years). |
| **Insulin** | 2-Hour serum insulin (mu U/ml). |
| **Skin Thickness** | Triceps skin fold thickness (mm). |
| **Pregnancies** | Number of times pregnant. |

---

## 🛠️ Tech Stack
* **Language:** Python 3.x
* **Libraries:**
    * `Pandas` & `NumPy`: Data manipulation and preprocessing.
    * `Scikit-learn`: Implementation of Logistic Regression and Decision Tree models.
    * `Matplotlib` & `Seaborn`: Data visualization and exploratory data analysis (EDA).

---

## 🚀 Getting Started

### 1. Prerequisites
Ensure you have Python installed. You can install the required dependencies via pip:
```bash
pip install numpy pandas scikit-learn matplotlib seaborn

### 2. Installation

Clone the repository:

git clone [https://github.com/yourusername/Diabetes-Prediction.git](https://github.com/yourusername/Diabetes-Prediction.git)
cd Diabetes-Prediction

### 3. Usage
Run the main script to train the model and generate a prediction report:

python diabetes_prediction.py
📈 Model Performance
The project compares two primary classification algorithms:

Logistic Regression: Used as a baseline model for binary classification, providing high interpretability and probabilistic insights.

Decision Tree: Utilized to capture non-linear relationships and complex interactions between health features.

Evaluation Metrics:

Accuracy: Overall correctness of the model.

Precision/Recall: Critical for medical datasets to minimize false negatives.

F1-Score: The harmonic mean of precision and recall.

🤝 Contributing
Contributions are what make the open-source community such an amazing place to learn, inspire, and create.

Fork the Project.

Create your Feature Branch (git checkout -b feature/AmazingFeature).

Commit your Changes (git commit -m 'Add some AmazingFeature').

Push to the Branch (git push origin feature/AmazingFeature).

Open a Pull Request.

📝 License
Distributed under the MIT License. See LICENSE for more information.