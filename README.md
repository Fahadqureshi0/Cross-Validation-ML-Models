# ❤️ Heart Disease Prediction using Cross-Validation

This project compares the performance of multiple Machine Learning algorithms for predicting heart disease. The models are evaluated using **K-Fold Cross-Validation** to obtain a more reliable estimate of their performance.

---

## 📌 Project Overview

The objective of this project is to predict whether a patient has heart disease based on medical attributes. Instead of relying on a single train-test split, the models are evaluated using **Cross-Validation**, which helps reduce bias and provides a more robust evaluation.

---

## 📂 Dataset

**Dataset:** Heart Disease Dataset

The dataset contains various medical features, including:

- Age
- Sex
- Chest Pain Type
- Resting Blood Pressure
- Cholesterol
- Fasting Blood Sugar
- Resting ECG
- Maximum Heart Rate
- Exercise-Induced Angina
- ST Depression
- Slope
- Number of Major Vessels
- Thalassemia

**Target Variable**

- `0` → No Heart Disease
- `1` → Heart Disease

---

## 🤖 Machine Learning Models

The following models were implemented and compared:

- Logistic Regression (LR)
- Support Vector Machine (SVM)
- Random Forest Classifier
- K-Nearest Neighbors (KNN)

---

## 🔄 Cross-Validation

This project uses **K-Fold Cross-Validation** to evaluate each model.

Advantages of Cross-Validation:

- Better estimate of model performance
- Reduces overfitting
- Uses the entire dataset for both training and validation
- More reliable than a single train-test split

---

## 📊 Evaluation Metric

The models are evaluated using:

- Cross-Validation Accuracy

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Jupyter Notebook

---

## 📁 Project Structure

```
Cross-Validation-ML-Models/
│
├── Heart_Disease.ipynb
├── heart.csv
├── README.md
└── requirements.txt
```

---

## 🚀 How to Run

1. Clone the repository

```bash
git clone https://github.com/Fahadqureshi0/Cross-Validation-ML-Models.git
```

2. Navigate to the project directory

```bash
cd Cross-Validation-ML-Models
```

3. Install dependencies

```bash
pip install -r requirements.txt
```

4. Run the Jupyter Notebook

```bash
jupyter notebook
```

---

## 📈 Results

The performance of the four models was compared using K-Fold Cross-Validation. The model with the highest average cross-validation accuracy can be considered the most reliable for this dataset

---

## 👨‍💻 Author

**Fahad Qureshi**

GitHub: https://github.com/Fahadqureshi0

LinkedIn: https://www.linkedin.com/in/fahad-qureshi-aa8a8727b/

Email: fahadqureshi.dev@gmail.com

---

⭐ If you found this project useful, consider giving it a star!
