# 🚗 Car Prices Prediction

This project demonstrates how to build a linear regression model to predict car prices using structured data. The dataset is sourced directly from Kaggle via the `kagglehub` package.

## 📌 About

The goal is to predict car prices based on features such as car make, model, fuel type, and other attributes. The notebook includes steps for data preprocessing, exploratory data analysis, and building a predictive machine learning pipeline.

## 📂 Project Structure

- `main.ipynb` – Jupyter notebook containing the full data loading, analysis, and modeling process.

## 📊 Dataset

- The dataset is sourced from Kaggle: [`yossefazam/carprices`](https://www.kaggle.com/datasets/yossefazam/carprices)
- It is automatically downloaded using the `kagglehub` package.

## 🧠 Model Overview

- **Model Used:** Linear Regression
- **Preprocessing:**
  - Categorical encoding using `OneHotEncoder`
  - Pipelines to streamline transformations and model fitting
- **Evaluation:** Train/test split and R² score

## 🛠️ Setup Instructions

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/car-price-predictor.git
   cd car-price-predictor
