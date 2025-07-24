# 🛍️ Customer Segmentation Using K-Means Clustering

This project demonstrates **customer segmentation** using **unsupervised learning (K-Means Clustering)** on the Mall Customers dataset. The goal is to identify distinct customer groups based on behavior for targeted marketing strategies.

---

## 📂 Dataset

- **Dataset**: `Mall_Customers.csv`
- **Source**: Public dataset (can be uploaded manually)
- **Attributes**:
  - `CustomerID`
  - `Gender`
  - `Age`
  - `Annual Income (k$)`
  - `Spending Score (1-100)`

---

## 🧠 ML Technique Used

- **Algorithm**: K-Means Clustering
- **Objective**: Group customers with similar behavior
- **Libraries**: 
  - `pandas` 
  - `numpy` 
  - `matplotlib` 
  - `seaborn` 
  - `scikit-learn`

---

## 📊 Visualizations

- **Elbow Method**: To find the optimal number of clusters (K)
- **Scatter Plot**: Customers segmented into different clusters
- **Cluster Centroids**: Visualized to interpret group characteristics

---

## ✅ Results

- **Optimal Clusters Found**: 5
- **Customer Segments Identified**:
  - High income, high spenders
  - Low income, low spenders
  - Moderate income, moderate spenders
  - Young impulsive buyers
  - Senior conservative buyers

---

## 📁 Files

- `Customer_Segmentation.ipynb`: Full notebook with code, EDA, and visualizations
- `README.md`: This file

---

## 🚀 How to Run

1. Upload the `Mall_Customers.csv` dataset in Colab
2. Run the notebook cell-by-cell
3. Explore the plots and results

---

## 📌 Future Scope

- Apply PCA for better visualization in 2D
- Try different clustering methods like DBSCAN or Agglomerative
- Deploy as an interactive dashboard using Streamlit

---

## 🧠 Skills Practiced

- Unsupervised ML
- Data Preprocessing
- EDA & Visualization
- Model Interpretation

