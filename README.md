
## 📊 Medical Insurance Cost Predictor using Regression Models 💰
Welcome to Day 6, 7 & 8 of my **30-Day 30-Model Challenge**! In this project, I tackled the problem of predicting insurance charges using **three regression techniques** in one notebook:

- **Linear Regression** 📈  
- **Polynomial Regression** 🧮  
- **Random Forest Regression** 🌳  

### 📁 Dataset
The dataset used is from the **Medical Cost Personal Dataset**, which includes the following features:

- `age`: Age of the primary beneficiary
- `sex`: Gender
- `bmi`: Body Mass Index
- `children`: Number of dependents
- `smoker`: Smoking status
- `region`: Residential region in the US
- `charges`: Medical insurance cost (target variable)

---

## 🧠 Models Implemented

### 1. **Linear Regression** 📉
A simple yet powerful model to understand linear relationships between features and the target (`charges`).  
- Fitted using scikit-learn's `LinearRegression`
- Performance evaluated using **R² Score**

### 2. **Polynomial Regression** 🧬
Captures **non-linear** relationships by adding polynomial features.  
- Degree used: 2
- Utilized `PolynomialFeatures` from scikit-learn and then applied Linear Regression

### 3. **Random Forest Regression** 🌲
An ensemble model that builds multiple decision trees and averages them for better prediction.
- Used `RandomForestRegressor` from scikit-learn
- Hyperparameter tuning: Default settings (can be further improved)

---

## 📊 Evaluation Metric
- **R² Score (Coefficient of Determination)**: Measures how well the predicted values match the actual values. Higher is better!

---

## 🔍 Results

| Model                  | R² Score |
|------------------------|----------|
| Linear Regression      | **0.74**  |
| Polynomial Regression  | **0.88**  |
| Random Forest Regressor| **0.86**  |

---

## ✅ Conclusion
After evaluating all three models, the **Polynomial Regression model** 🧮 outperformed the others with an impressive **R² score of 0.88**!  

- It captured the **non-linear relationship** between features and charges better than Linear Regression.
- While Random Forest Regression also performed well, it was slightly behind Polynomial Regression in this case.

📌 **Winner**: 🥇 **Polynomial Regression**

---

## 📌 Key Takeaways
- Linear Regression is great for **baseline comparisons**
- Polynomial Regression shines when the data has **curved trends**
- Random Forest is a **robust all-rounder**, especially with more tuning!

---

## 🚀 Part of the 30-Day Challenge!
This project is part of my **#30Days30Models** challenge where I build 1 model every day.  
Follow along the journey to see all kinds of ML algorithms in action! 🎯

> Stay tuned for more — tomorrow brings a new model, a new challenge, and new learning! 🧠✨
