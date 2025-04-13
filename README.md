# IPL-Predictor

# 🏏 IPL Match Predictions using Machine Learning

Welcome to the **IPL Match Predictions** project! This repository contains a Jupyter Notebook that demonstrates how machine learning can be used to predict the outcome of Indian Premier League (IPL) cricket matches based on historical data and match conditions.

---

## 📌 Project Overview

This project applies data science techniques to predict IPL match winners using features like:
- Team composition
- Toss decisions
- Match venue
- Season trends

We preprocess the data, explore it visually, train machine learning models, and evaluate their accuracy to determine which model best predicts match outcomes.

---

## 📊 Dataset

The dataset used contains information about IPL matches including:
- Teams
- Toss winner and decision
- Match winner
- Venue
- Season
- Player of the match
- Umpires

📁 File: `data.csv`

> If you're running this locally, make sure `data.csv` is placed in the same directory as the notebook.

---

## 🧠 Machine Learning Workflow

1. **Data Cleaning & Preprocessing**
   - Handling missing values
   - Removing unimportant columns
   - Encoding categorical variables

2. **Exploratory Data Analysis (EDA)**
   - Match outcomes by team
   - Toss influence on match results
   - Venue impact

3. **Model Building**
   - Train-Test Split
   - Algorithms used:
     - Logistic Regression
     - Decision Tree
     - Random Forest
     - Support Vector Machines (SVM)
     - (Optionally) XGBoost

4. **Evaluation Metrics**
   - Accuracy
   - Confusion Matrix
   - Classification Report

---

## 🚀 How to Run

### 🧪 Local Setup

1. Clone the repo:
   ```bash
   git clone https://github.com/yourusername/ipl-predictions.git
   cd ipl-predictions
