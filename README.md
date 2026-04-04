# 🌸 Ensemble Modeling on Iris Dataset

## 📌 Overview
This project demonstrates the application of **ensemble learning (stacking)** on the Iris dataset to improve classification performance.

In this project, I built multiple machine learning models and combined them into a single **stacked ensemble model**. Instead of relying on one algorithm, I used the predictions of several base models and passed them into a meta-model to make the final prediction. This approach helps improve accuracy and generalization.

---

## 🧠 What I Did in This Project
- Loaded and explored the Iris dataset
- Split the dataset into training and testing sets
- Trained multiple base models:
  - K-Nearest Neighbors (KNN)
  - Naive Bayes
  - Random Forest
- Generated predictions from each base model
- Combined these predictions using a **stacking technique**
- Built a meta-model to learn from base model outputs
- Compared the performance of:
  - Individual models
  - Ensemble (stacked) model
- Evaluated results using accuracy scores

---

## 🚀 Features
- Implementation of stacking ensemble learning
- Multiple base classifiers working together
- Improved prediction accuracy
- Easy-to-understand implementation for beginners



## 📊 Dataset
The project uses the Iris Dataset:
- 150 samples
- 3 flower classes:
  - Setosa
  - Versicolor
  - Virginica
- 4 features:
  - Sepal length
  - Sepal width
  - Petal length
  - Petal width
