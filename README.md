# 🍽️ Zomato Restaurant Data Analysis & Rating Prediction

![Python](https://img.shields.io/badge/Python-3.10-blue?logo=python)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-blue?logo=pandas)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-Machine%20Learning-orange?logo=scikitlearn)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-green)
![Seaborn](https://img.shields.io/badge/Seaborn-EDA-blueviolet)

---

# 📌 Project Overview

This project performs **Exploratory Data Analysis (EDA)** and **Machine Learning** on the **Zomato Restaurant Dataset**. The objective is to clean and preprocess restaurant data, uncover meaningful insights through visualization, and build machine learning models to predict restaurant dining ratings.

The project demonstrates a complete data science workflow, including data cleaning, feature engineering, visualization, preprocessing, and regression model development.

---

# 🎯 Objectives

- Perform Exploratory Data Analysis (EDA) on restaurant data.
- Handle missing values and clean inconsistent data.
- Engineer meaningful features from raw data.
- Analyze restaurant distribution across different locations.
- Identify highly rated restaurants and popular restaurant types.
- Predict restaurant dining ratings using Machine Learning.

---

# 📂 Dataset

**Dataset:** Zomato Restaurant Dataset

**Source:** Kaggle

https://www.kaggle.com/datasets/nagar500/pune-restaurants-zomato

---

# 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

# 📁 Project Structure

```
Zomato-Restaurant-Data-Analysis/
│
├── Zomato_Data_Analysis.ipynb
├── README.md
├── requirements.txt
├── .gitignore
├── LICENSE
└── images/
```

---

# 📊 Exploratory Data Analysis

The project includes:

- Dataset inspection
- Missing value analysis
- Data cleaning
- Duplicate removal
- Data type conversion
- Feature engineering
- Restaurant location analysis
- Restaurant type analysis
- Cuisine analysis
- Cost distribution
- Restaurant rating analysis

---

# 🧹 Data Preprocessing

The preprocessing pipeline includes:

- Removing unnecessary columns
- Handling missing values
- Cleaning restaurant names
- Extracting numerical values from text
- Converting appropriate columns to numeric data types
- Creating new features
- Frequency Encoding
- MultiLabel Binarization for cuisines
- Feature Scaling

---

# 📈 Data Visualizations

The project includes various visualizations such as:

- Average restaurant ratings by location
- Restaurant distribution by locality
- Restaurant type distribution
- Cost analysis
- Cuisine popularity
- Restaurant rating trends

---

# 🤖 Machine Learning Models

## Problem Statement

Predict restaurant dining ratings based on restaurant characteristics.

### Features

- Restaurant Type
- Area
- Cuisine
- Cost

### Target

- Dine Rating

---

## Models Implemented

- Linear Regression
- Random Forest Regressor

---

# 📊 Model Evaluation

The models were evaluated using:

- R² Score
- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)

These metrics help assess prediction accuracy and compare model performance.

---

# 🚀 How to Run

Clone the repository

```bash
git clone https://github.com/Sanjivani-29/Zomato-Restaurant-Data-Analysis.git
```

Navigate to the project folder

```bash
cd Zomato-Restaurant-Data-Analysis
```

Install the required dependencies

```bash
pip install -r requirements.txt
```

Run the notebook

```bash
jupyter notebook Zomato_Data_Analysis.ipynb
```

---

# 📌 Key Insights

- Identified factors influencing restaurant ratings.
- Analyzed the relationship between restaurant cost and customer ratings.
- Explored the popularity of different cuisines and restaurant types.
- Compared machine learning models for restaurant rating prediction.

---

