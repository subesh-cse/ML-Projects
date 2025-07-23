# MNIST Digit Classification 🧠🖊️

This project implements a simple Neural Network using TensorFlow and Keras to classify handwritten digits from the MNIST dataset. It includes data visualization, model training, evaluation, and performance metrics.

---


---

## 📌 Objective

To build a multi-class classification model that can accurately recognize handwritten digits (0–9) from grayscale images using a neural network.

---

## 📊 Dataset

- **Dataset Name:** MNIST  
- **Description:** 70,000 28×28 pixel grayscale images of handwritten digits (0–9)  
- **Source:** Built-in with `keras.datasets`

---

## 🧠 Model Architecture

- Input Layer: `28 x 28` image input (flattened)
- Dense Layer 1: 128 neurons with ReLU activation
- Output Layer: 10 neurons with Softmax activation

```python
model = Sequential()
model.add(Input(shape=(28, 28)))
model.add(Flatten())
model.add(Dense(128, activation='relu'))
model.add(Dense(10, activation='softmax'))
```

---

## 📈 Results & Visualizations

- **Sample Predictions**: Shows actual images with predicted labels  
- **Accuracy**: Evaluated using test dataset  
- **Confusion Matrix**: Displays class-wise prediction performance  
- **Loss & Accuracy Graphs**: Training vs validation performance

---

## ✅ Performance

| Metric        | Value                         |
|---------------|-------------------------------|
| Test Accuracy | ~97% (varies slightly per run)|
| Loss          | Low and stable                |

---

## 📦 Libraries Used

- `TensorFlow` / `Keras`  
- `Matplotlib`  
- `Seaborn`  
- `Scikit-learn`  
- `NumPy`

---

## 🚀 How to Run

1. Open the `MNIST_digit_classification.ipynb` notebook in **Google Colab** or **Jupyter Notebook**
2. Run all cells to:
   - Load and preprocess data
   - Train the model
   - Visualize predictions and accuracy

---

## 📚 Learning Outcome

- Understand how neural networks work on image data  
- Learn basic TensorFlow/Keras workflows  
- Gain experience in visualizing predictions and performance

---

## 💡 Future Improvements

- Use **CNN (Convolutional Neural Network)** for higher accuracy  
- Add **Dropout** or **Batch Normalization** for better generalization  
- Try **Hyperparameter tuning** for optimization

---


