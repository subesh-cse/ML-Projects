# 💓 Heart Disease Prediction using Machine Learning

## 📌 Project Overview

This project uses a supervised machine learning model to predict whether a person has heart disease based on clinical features such as age, blood pressure, cholesterol, etc. The classification model provides a predictive diagnosis from real patient data.

## 🧠 Objective

To build a predictive model using the **Logistic Regression** algorithm that can accurately classify patients into two categories:
- 1: Patient **has** heart disease
- 2: Patient **does not have** heart disease

---

## 📁 Dataset

- 📄 **Name**: Heart Disease UCI-style dataset
- 🧷 **Shape**: 270 rows × 14 columns
- 🔗 **Source**: [Kaggle (Offline Source)](https://www.kaggle.com/datasets)
- ✅ No missing values were found.

---

## 🧪 Features Used

| Feature                | Description                             |
|------------------------|-----------------------------------------|
| `age`                  | Age of the patient                      |
| `sex`                  | Gender (1 = male; 0 = female)           |
| `pain type`            | Type of chest pain                      |
| `BP`                   | Resting blood pressure                  |
| `cholestrol`           | Serum cholesterol (mg/dl)               |
| `fbs`                  | Fasting blood sugar (>120 mg/dl)        |
| `resting ecg`          | Resting electrocardiographic results    |
| `max heart rate`       | Maximum heart rate achieved             |
| `exercise angina`      | Exercise-induced angina                 |
| `ST depression`        | Depression induced by exercise          |
| `ST slope`             | The slope of the peak exercise ST segment |
| `flouroscopy coloured` | No. of major vessels (0-3) colored by fluoroscopy |
| `thal`                 | Thalassemia value (3 = normal, 6 = fixed defect, 7 = reversible defect) |
| `target`               | 1 = Disease, 2 = No disease             |

---

## 📊 Data Preprocessing

- Checked for null values — ✅ **No missing values**
- Converted categorical values using Label Encoding
- Split the data: **80% training** | **20% testing**

---

## 🤖 Model Used

- **Logistic Regression**
- Train-test split: 80:20
- Evaluation metrics: Accuracy, Precision, Recall, F1-score, Confusion Matrix

---

## 📈 Results

- ✅ **Model Accuracy**: **~85.19%**
- 🧾 **Classification Report**:
```
               precision    recall  f1-score   support

           1       0.92      0.80      0.86        30
           2       0.79      0.92      0.85        24

    accuracy                           0.85        54
   macro avg       0.85      0.86      0.85        54
weighted avg       0.86      0.85      0.85        54
```

- 📌 **Confusion Matrix Output**:

![Confusion Matrix](52562fac-fcf0-4f65-8507-54f508ee01bd.png)

---

## 🧠 Conclusion

- Logistic Regression gives solid performance with over **85% accuracy** on unseen data.
- Most false predictions were mild misclassifications between heart disease presence/absence.
- The model is interpretable and deployable in basic clinical tools.

---

## 🚀 Future Work

- Try other classifiers like Random Forest, XGBoost
- Use real-time EHR data with richer features
- Integrate a frontend for real-world usage
