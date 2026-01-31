# 🏠 House Price Prediction

This project implements a **Linear Regression** model to predict housing prices based on various numerical features. This was developed as part of my **Machine Learning Internship at SYNTECXHUB**.

## 🚀 Overview

The goal of this project is to analyze a housing dataset, perform exploratory data analysis (EDA), and build a predictive model that estimates the market value of properties.

## 🛠️ Features

* **Data Preprocessing:** Automatic handling of missing values and filtering of non-numeric data.
* **Feature Engineering:** Selection of key variables like Square Footage, Rooms, and Age.
* **Model Evaluation:** Performance tracking using **RMSE** and ** Score**.
* **Persistence:** Model serialization using `joblib` for future inference.

## 📊 Performance

The model is evaluated based on:

* **Root Mean Squared Error (RMSE):** Measures the average deviation between predicted and actual prices.
* ** Score:** Indicates the proportion of variance explained by the model.

## 💻 Tech Stack

* **Language:** Python 3.10
* **Libraries:** `pandas`, `numpy`, `scikit-learn`, `matplotlib`, `seaborn`

## 📂 Project Structure

```text
├── housing_data.csv         # Raw housing dataset
├── housepricepred.py        # Main training script
└── house_price_model.pkl    # Saved model file
```

## ⚙️ How to Run

1. Clone the repository:
```bash
git clone https://github.com/yourusername/house-price-prediction.git

```


2. Navigate to the project folder:
```bash
cd Syntecxhub

```


3. Run the script:
```bash
python housepricepred.py

```



---

