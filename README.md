# 🏠 House Price Prediction System

## 📌 Overview

This project is an **end-to-end Machine Learning application** that predicts house prices based on features like area, bedrooms, bathrooms, and amenities.

It also provides:

* 📊 Model comparison
* 📈 Price range estimation
* 🔍 What-if analysis for decision making

---

## 🚀 Features

### 1. Price Prediction

* Takes user input (area, bedrooms, etc.)
* Predicts house price using a trained ML model

### 2. Price Range (Confidence Logic)

* Displays estimated range using model error (MAE)
* Makes predictions more realistic

### 3. Model Comparison

* Compares:

  * Linear Regression
  * Random Forest
* Visualized using a bar chart

### 4. What-if Analysis

* Allows users to simulate:

  * “What happens if area increases?”
* Helps in decision-making

---

## 🧠 Tech Stack

* **Python**
* **Pandas / NumPy**
* **Scikit-learn**
* **Streamlit**

---

## 📂 Project Structure

```
house-price-ml-project/
│
├── data/
│   └── Housing.csv
│
├── notebook.ipynb     # Data preprocessing + model training
├── model.pkl          # Saved ML model
├── app.py             # Streamlit application
└── README.md
```

---

## ⚙️ How It Works

1. Data is cleaned and preprocessed
2. Categorical variables are encoded
3. Models are trained and evaluated
4. Best model (Linear Regression) is selected
5. Model is saved using pickle
6. Streamlit app loads model and predicts results

---

## 📊 Model Performance

| Model             | MAE       | Selected |
| ----------------- | --------- | -------- |
| Linear Regression | 970,043   | ✅ Yes    |
| Random Forest     | 1,018,147 | ❌ No     |

---

## ▶️ Run the Project

### 1. Install dependencies

```
pip install streamlit pandas numpy scikit-learn
```

### 2. Run app

```
python -m streamlit run app.py
```

---

## 🎯 Key Learnings

* Data preprocessing and encoding
* Model training and evaluation
* Feature importance analysis
* Building ML-powered applications
* Deploying models using Streamlit

---

## 📌 Future Improvements

* Add more advanced models (XGBoost, etc.)
* Improve UI/UX
* Deploy app online

---

## 👨‍💻 Author

Aditya

---

## ⭐ If you like this project, give it a star!
