# 🎓 Student Score Predictor — Linear Regression

Welcome to my ML mini-project that predicts student exam scores based on the number of hours they studied using **Simple Linear Regression**. It's a beginner-friendly example of how machine learning can help in real-life academic scenarios.

---

## 📚 Prediction Result

**🧠 Input**: 6.5 hours of study  
**📍 Predicted Score**: ~72.98 marks

---

## 📐 Model Evaluation

| Metric                  | Value   | Description                                |
|-------------------------|---------|--------------------------------------------|
| 📉 Mean Absolute Error  | 3.29    | Average error in predictions               |
| 🔢 Mean Squared Error   | 13.49   | Penalizes larger errors more               |
| 📊 R² Score             | 0.96 ✅ | Model explains **96%** of data variance    |

✅ **Conclusion**: This is an excellent fit! Only ~4% error remains.

---

## 🖼️ Regression Plot

Below is the regression line drawn by the model along with actual data points:

![Regression Line](../plot.png)

---

## 📁 Project Files

| File Name                        | Description                                |
|----------------------------------|--------------------------------------------|
| `student_scores.csv`             | Dataset used in this project               |
| `student-score-predictor.ipynb`  | Kaggle notebook with training & analysis   |
| `plot.png`                       | Regression line graph                      |
| `README.md`                      | Project summary on GitHub                  |

---

## 💡 How It Works

1. 📊 Data is visualized and cleaned using `pandas` and `matplotlib`
2. 📉 Split into train/test sets
3. 🧠 Model trained using `LinearRegression()` from `scikit-learn`
4. 🔮 Prediction is made for new inputs
5. ✅ Model is evaluated using MAE, MSE, and R² Score

---

## 👩‍💻 Author

**Bhoomi Awhad**  
🎓 Student at Dr. D Y Patil Technical Campus, Talegaon  
💡 Passionate about AI, ML, and turning data into real-world impact  
📬 [Connect on LinkedIn](https://linkedin.com) *(replace with your link)*

---

> 🔗 View on GitHub: [Student Score Predictor](https://github.com/your-username/student-score-predictor)
