# 🎓 Student Score Predictor — Linear Regression Project

This project uses **simple linear regression** to predict a student's score based on the number of hours they studied. Built using Python and Jupyter Notebook in Kaggle, it's a great beginner-level machine learning project. 📈

---

## 📂 Dataset

- Source: Manually uploaded to Kaggle (CSV format)
- Features:
  - `Hours`: Number of study hours
  - `Scores`: Student exam scores

---

## 🚀 What This Project Does

- Loads and visualizes data (scatter plot)
- Trains a Linear Regression model
- Predicts scores based on new inputs
- Evaluates model performance using:
  - MAE (Mean Absolute Error)
  - MSE (Mean Squared Error)
  - R² Score (Accuracy)

---

## 📊 Results

| Metric | Value |
|--------|-------|
| Mean Absolute Error (MAE) | **3.29** |
| Mean Squared Error (MSE)  | **13.49** |
| R² Score                  | **0.96 ✅** |

> ✅ The model explains **96% of the data pattern**, which is excellent for a simple dataset.

---

## 🔮 Sample Prediction

```python
# Input: 6.5 hours studied
predicted_score = model.predict([[6.5]])
