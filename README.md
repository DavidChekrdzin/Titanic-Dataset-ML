# Titanic Survival Prediction (KNN + GridSearchCV)

This project uses **machine learning** to predict passenger survival on the Titanic dataset.  
It demonstrates **data preprocessing**, **feature engineering**, **handling missing values**, and **hyperparameter tuning** using `GridSearchCV` with a **K-Nearest Neighbors (KNN)** classifier.

---

## 🚀 Features
- Cleans and preprocesses Titanic dataset:
  - Drops irrelevant features
  - Handles missing values
  - Encodes categorical data
  - Creates new engineered features (`FamilySize`, `IsAlone`, `FareBin`, `AgeBin`)
- Splits data into **training** and **testing** sets
- Scales data using **MinMaxScaler**
- Performs **hyperparameter tuning** with `GridSearchCV`
- Evaluates the model with **accuracy score** and **confusion matrix**
- Visualizes results with a **heatmap**

---

## 📂 Project Structure
├── Titanic-Dataset.csv # Dataset file
├── titanic.py # Main Python script
├── README.md # Project documentation

## ⚙️ Installation
1. Clone this repository
2. Install dependencies:
                          Python 3.8+
                          pandas
                          numpy
                          scikit-learn
                          matplotlib
                          seaborn


And a heatmap will be displayed showing prediction performance.
