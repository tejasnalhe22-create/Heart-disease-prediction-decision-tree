# Heart Disease Prediction using Decision Tree Classification

This repository contains a machine learning project focused on predicting cardiac health outcomes. By analyzing clinical parameters, the model identifies patterns that correlate with the presence of heart disease.

## 📁 Project Structure

* `1DECISION TREE.ipynb`: The Jupyter Notebook containing data exploration, model training, and visualization of the tree.
* `heart_disease.xlsx - Heart_disease.csv`: The primary dataset containing patient medical records.
* `heart_disease.xlsx - Description.csv`: A reference file explaining the features (columns) within the dataset.

## 📊 Dataset Overview

The model evaluates several clinical features to make a prediction, including:
* **Age & Gender**
* **Chest Pain Type** (cp)
* **Blood Pressure & Cholesterol levels**
* **Maximum Heart Rate Achieved** (thalach)
* **Exercise-Induced Angina** (exang)

## 🚀 Machine Learning Pipeline

1.  **Exploratory Data Analysis (EDA)**: Investigating feature distributions and class balance between healthy and heart disease cases.
2.  **Data Preprocessing**: Handling categorical encoding and splitting data into training and testing sets.
3.  **Model Implementation**: Building a Decision Tree Classifier using `scikit-learn`.
4.  **Tree Visualization**: Generating a visual representation of the decision-making logic (nodes and leaves).
5.  **Evaluation**: Measuring performance using accuracy scores, precision, and recall.



## 🛠️ Requirements

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
