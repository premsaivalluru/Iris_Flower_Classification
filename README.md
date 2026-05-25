# 🌸 Iris Flower Classification using Decision Tree

A beginner-friendly Machine Learning project that demonstrates how to build a basic classification model using the Iris flower dataset and the Decision Tree algorithm.

This project covers the complete workflow of a supervised learning classification problem using Python and Scikit-learn.

---

# 📌 Project Objectives

- Load and understand a dataset
- Split data into training and testing sets
- Train a classification model
- Make predictions
- Evaluate model performance

---

# 🛠️ Technologies Used

- Python
- Scikit-learn
- NumPy

---

# 📂 Dataset Used

The project uses the built-in **Iris Dataset** available in Scikit-learn.

### Features
- Sepal Length
- Sepal Width
- Petal Length
- Petal Width

### Target Classes
- Setosa
- Versicolor
- Virginica

---

# 🤖 Machine Learning Algorithm

This project uses:

## Decision Tree Classifier

A supervised learning algorithm used for classification tasks that predicts target labels by learning decision rules from data features.

---

# 📦 Installation

Install the required libraries using:

```bash
pip install scikit-learn numpy
```

---

# ▶️ How to Run

```bash
python filename.py
```

---

# 📜 Project Workflow

## 1️⃣ Load Dataset

The Iris dataset is loaded using Scikit-learn.

```python
iris = load_iris()
```

---

## 2️⃣ Split Dataset

The dataset is divided into:
- Training Data (80%)
- Testing Data (20%)

```python
train_test_split()
```

---

## 3️⃣ Train Model

A Decision Tree Classifier is created and trained.

```python
model.fit(X_train, y_train)
```

---

## 4️⃣ Make Predictions

The trained model predicts flower classes for test data.

```python
y_pred = model.predict(X_test)
```

---

## 5️⃣ Evaluate Model

Model performance is evaluated using:
- Accuracy Score
- Classification Report

```python
accuracy_score()
classification_report()
```

---

# 📊 Sample Output

```text
Accuracy: 1.0

Classification Report:

              precision    recall  f1-score   support

           0       1.00      1.00      1.00        10
           1       1.00      1.00      1.00         9
           2       1.00      1.00      1.00        11

    accuracy                           1.00        30
```

---

# 🎯 Learning Outcomes

By completing this project, you will understand:

- Supervised Learning Basics
- Classification Problems
- Data Splitting
- Model Training
- Prediction and Evaluation
- Basic Scikit-learn Workflow

---

# 🚀 Future Improvements

- Add data visualization
- Try other classification algorithms
- Hyperparameter tuning
- Build a web interface
- Deploy the model

---

# 👨‍💻 Author

Developed as a beginner Machine Learning project for learning classification model fundamentals using Python and Scikit-learn.

```
