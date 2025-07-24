
# 📰 Fake News Detection - Machine Learning Project

This project aims to classify news articles as **FAKE** or **REAL** using a machine learning approach. It uses **text processing and Naive Bayes classification** to achieve high accuracy on a combined dataset from Kaggle.

---

## 📂 Dataset

The dataset is a combination of:
- `fake.csv` — News articles labeled as fake
- `true.csv` — News articles labeled as real  
📌 **Source**: [Kaggle - Fake and Real News Dataset](https://www.kaggle.com/datasets/clmentbisaillon/fake-and-real-news-dataset)



---

## 📈 Project Highlights

- ✅ Dataset Preprocessing (merging, labeling, shuffling)
- ✅ Text Vectorization using **TF-IDF**
- ✅ Model: **Multinomial Naive Bayes**
- ✅ Evaluation with Accuracy, Confusion Matrix, and Classification Report
- ✅ Visualization: Class Distribution & Confusion Matrix

---

## 🔍 Results

- **Accuracy**: `98.46%`
- **Confusion Matrix**:
  - Real correctly predicted: 4184
  - Fake correctly predicted: 4658
- **Precision / Recall / F1-score**: Excellent across both classes

---

## 📊 Sample Graphs

| Real vs Fake News Distribution | Confusion Matrix |
|-------------------------------|------------------|
| ![Class Distribution](e2c7b122-5a72-45aa-a759-ad5aba14d33a.png) | ![Confusion Matrix](5c10d246-6649-43d1-aa97-d5c10eed3793.png) |

---

## 🚀 Future Improvements

- Export trained model as `.pkl` or `.joblib`
- Add GUI using **Streamlit**
- Experiment with models like **Logistic Regression**, **Random Forest**, or **BERT**


Feel free to ⭐ star the repo if you find it useful!
