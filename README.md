# Anurag_Health-Risk-Classification_202401100300057_
The Health Risk Classification project aims to predict an individual's health risk level—Low, Medium, or High—based on their lifestyle factors such as Body Mass Index (BMI), exercise frequency, and eating habits. The project uses machine learning techniques to analyze these input features and classify health risk,
# 🩺 Health Risk Classification using Machine Learning

## 📌 Project Overview

This project uses a **Random Forest Classifier** to predict an individual's health risk category — **Low**, **Medium**, or **High** — based on their **BMI**, **exercise frequency**, and **eating habits**. The aim is to demonstrate how machine learning can assist in preventive healthcare by analyzing simple lifestyle factors.

---

## 🧠 Problem Statement

Develop a classification model to categorize individuals into different health risk levels using:

- **BMI** (Body Mass Index)
- **Exercise Frequency** (0–5 times per week)
- **Eating Habits** (`Poor`, `Average`, `Good`)

---

## 🛠️ Methodology

1. **Data Generation**: Synthetic data was created to simulate real-world health metrics.
2. **Preprocessing**:
   - Label encoding of categorical features.
   - Train-test split (80/20).
3. **Model Training**:
   - Used `RandomForestClassifier` from scikit-learn.
4. **Evaluation**:
   - Accuracy, Precision, Recall
   - Confusion Matrix & Classification Report
5. **Feature Importance Analysis** to interpret model behavior.

---

## 📊 Results

| Metric     | Value (Example) |
|------------|-----------------|
| Accuracy   | 0.78            |
| Precision  | 0.79            |
| Recall     | 0.78            |

The confusion matrix and classification report indicate strong performance in identifying Low and High risk individuals, with minor misclassifications in the Medium category.

---

## 🔍 Dependencies

Install the following Python libraries before running:

```bash
pip install pandas numpy scikit-learn matplotlib seaborn
