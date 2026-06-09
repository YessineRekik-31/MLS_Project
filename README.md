# 🎓 Student Pass Predictor (MLS_Project)

An end-to-end Machine Learning pipeline that predicts whether a student will pass or fail their final assessment based on their study habits and engagement metrics. The project includes a predictive model built with Scikit-Learn and an interactive web interface powered by Gradio.

---

## 🚀 Features
- **Machine Learning Pipeline:** Data preprocessing, standard feature scaling, and binary classification using Logistic Regression.
- **Interactive UI:** A modern, slide-controlled dashboard built with Gradio's `soft` theme to effortlessly test student data in real-time.
- **Probability Output:** Not only predicts a hard **Pass/Fail** result but also provides the underlying probability score percentage.

---

## 📊 Dataset Structure
The predictive model trains on `studentPerformance.csv`, which tracks the following metrics:
- **Features Used for Prediction:**
  - `Study_Hours`: Total hours dedicated to studying (Numerical, e.g., 0 to 12 hours).
  - `Attendance`: Classroom attendance percentage (Numerical, 0% to 100%).
  - `Practice_Tests`: Number of mock or practice exams taken (Integer, 0 to 10).
- **Target Variable:**
  - `Pass_Fail`: The classification target (`1` for Pass, `0` for Fail).

*Note: The dataset also contains a `Final_Score` column, which is explicitly omitted during training to prevent data leakage and ensure true predictive behavior.*

---

## 🛠️ Tech Stack & Libraries
- **Language:** Python 3
- **Data Manipulation:** `pandas`
- **Machine Learning:** `scikit-learn` (Logistic Regression, StandardScaler, train_test_split)
- **Web Interface:** `gradio`

---

## ⚙️ Installation & Setup

1. **Clone the Repository:**
   git clone [https://github.com/YOUR_USERNAME/MLS_Project.git](https://github.com/YessineRekik-31/MLS_Project.git)
   cd MLS_Project
2. **Install Required Packages:**
```bash
pip install pandas scikit-learn gradio
```
3. 
