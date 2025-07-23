
# 🏠 House Price Prediction

This project uses the **California Housing Dataset** to predict median house values using machine learning regression techniques.

## 📌 Objective

To build a regression model that can accurately predict housing prices based on features like median income, number of rooms, house age, and more.

---

## 📁 Dataset Used

- **Dataset Name:** California Housing Dataset  
- **Source:** Built-in from `sklearn.datasets` → `fetch_california_housing()`

---

## 🔧 Technologies & Libraries

- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-Learn

---

## 📊 Features in the Dataset

| Feature | Description |
|--------|-------------|
| MedInc | Median income in block group |
| HouseAge | Median house age |
| AveRooms | Average number of rooms |
| AveBedrms | Average number of bedrooms |
| Population | Block group population |
| AveOccup | Average number of household members |
| Latitude | Latitude coordinate |
| Longitude | Longitude coordinate |

---

## 🔍 Exploratory Data Analysis

- Handled missing values
- Plotted heatmaps and pairplots using `seaborn`
- Identified feature correlation with the target (`MedHouseVal`)

---

## 📈 Model Building

- **Model Used:** Linear Regression
- **Train-Test Split:** 80% train / 20% test

### ✅ Model Evaluation

- **R² Score:** `0.575`
- **Mean Squared Error:** `0.556`

---

## 📌 Output Visualization

- Correlation heatmap for feature selection
- Line plot comparing actual vs predicted house prices

---


---

## 💡 Future Improvements

- Use more advanced regression models: Ridge, Lasso, XGBoost, etc.
- Hyperparameter tuning
- Add grid search and cross-validation
- Deploy model as an API using Flask or Streamlit

---

## 🙌 Acknowledgements

- Scikit-learn Team for dataset and models
- Colab for seamless notebook experience

---





