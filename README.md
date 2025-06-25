# 🎓 Student Score Predictor — Linear Regression Project

This beginner-friendly machine learning project uses **Simple Linear Regression** to predict a student's exam score based on the number of hours studied. It’s built with Python and Kaggle's Jupyter Notebook environment using `pandas`, `matplotlib`, and `scikit-learn`.

> 💡 "What if you could predict your exam score just by logging your study hours?"

---

## 📁 Dataset Overview

- **Source**: Manually uploaded CSV file on Kaggle
- **Attributes**:
  - `Hours`: Number of hours studied per day
  - `Scores`: Corresponding exam scores

---

## 🔧 Tech Stack

| Tool             | Purpose                          |
|------------------|----------------------------------|
| Python 3         | Core programming language        |
| pandas           | Data manipulation & cleaning     |
| matplotlib       | Data visualization               |
| scikit-learn     | Model training & evaluation      |
| Jupyter Notebook | Kaggle notebook environment      |
| GitHub           | Project hosting & documentation  |

---

## 📊 Project Workflow

### 1. 📥 Load & Visualize Data
- Import CSV
- Create a scatter plot (Hours vs Scores)

### 2. 🧪 Preprocess
- Check for nulls
- Reshape data if needed

### 3. 📚 Train-Test Split
- 80% training, 20% testing using `train_test_split()`

### 4. 🧠 Train the Model
```python
model.fit(X_train, y_train)

---

## 🔮 Sample Prediction

```python
# Input: 6.5 hours studied
predicted_score = model.predict([[6.5]])
