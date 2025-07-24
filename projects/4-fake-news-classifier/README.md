
# 📰 Fake News Detection - Machine Learning Project

This project aims to classify news articles as **FAKE** or **REAL** using a machine learning approach. It uses **text processing and Naive Bayes classification** to achieve high accuracy on a combined dataset from Kaggle.

---

## 📂 Dataset

The dataset is a combination of:
- `fake.csv` — News articles labeled as fake
- `true.csv` — News articles labeled as real  
📌 **Source**: [Kaggle - Fake and Real News Dataset](https://www.kaggle.com/datasets/clmentbisaillon/fake-and-real-news-dataset)



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



## 🚀 Future Improvements

- Export trained model as `.pkl` or `.joblib`
- Add GUI using **Streamlit**
- Experiment with models like **Logistic Regression**, **Random Forest**, or **BERT**

---

## 📁 Files in This Repository

| File | Description |
|------|-------------|
| `Fake_News_Detection.ipynb` | Main notebook with full training, evaluation, and visualizations |
| `README.md` | You're reading it 😊 |

---



Feel free to ⭐ star the repo if you find it useful!
