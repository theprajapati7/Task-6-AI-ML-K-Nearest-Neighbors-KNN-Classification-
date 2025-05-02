# 🌸 K-Nearest Neighbors (KNN) Classification – Iris Dataset

This project demonstrates how to implement the **K-Nearest Neighbors (KNN)** algorithm for classification using the **Iris dataset**. It includes data preprocessing, model training, evaluation, and visualization of decision boundaries.

---

## 🔧 Tools & Libraries Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib

---

## 📊 Dataset

We use the **Iris dataset**, a classic multiclass classification dataset with 3 classes:
- Setosa
- Versicolor
- Virginica

Each record includes:
- Sepal Length
- Sepal Width
- Petal Length
- Petal Width

---

## 🧠 Workflow

1. **Import Libraries**
2. **Load and Explore Dataset**
3. **Normalize Features using StandardScaler**
4. **Split Data into Train/Test Sets**
5. **Train KNN Classifier with Various K Values**
6. **Evaluate Accuracy & Confusion Matrix**
7. **Visualize Decision Boundary (2D)**

---

## 📈 Model Evaluation

We experimented with different values of **K** (from 1 to 10) and printed accuracy scores to select the best-performing model. A **confusion matrix** was used to evaluate the final model.

---

## 📉 Decision Boundary

To visualize how KNN classifies data points, we plotted a **2D decision boundary** using only the first two features (Sepal Length and Sepal Width).

---

