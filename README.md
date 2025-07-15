# 💼 Salary Prediction with Random Forest Regression

Predicting salaries based on experience, certifications, performance, and more using a Random Forest Regressor. The dataset includes **missing values**, simulating real-world challenges in data science workflows.

---

## 📁 Dataset Overview

The dataset `Position_Salaries_with_Missing.csv` contains 10 samples with the following columns:

- `Position`: Position index (1–10)
- `Experience_Years`: Number of years of experience (with NaNs)
- `Education_Level`: Categorical education level (High School to PhD)
- `Certifications`: Number of certifications (with NaNs)
- `Projects_Led`: Projects led by the employee (with NaNs)
- `Performance_Score`: A float score from 1 to 5
- `Salary`: Target value, includes missing entries

---

## 🧪 Tech Stack

- 🐍 Python 3
- 📊 pandas & NumPy
- ⚙️ scikit-learn
- 📈 matplotlib (optional for visualization)

---

## ⚙️ Workflow

1. Load dataset
2. Handle missing values using `SimpleImputer`
3. Select features and target
4. Train `RandomForestRegressor`
5. Predict and optionally visualize results

---

## 🚀 Results

After imputing missing values and training the Random Forest model on a limited but diverse dataset:

<img width="589" height="455" alt="image" src="https://github.com/user-attachments/assets/f87ea2d2-5321-4880-96ea-26c248aae546" />


- **R² Score (on training set)**: ~0.98  
- **Mean Absolute Error**: Low (±$2,000–$3,000 range)
- Model successfully handled missing data and predicted realistic salary ranges for synthetic data.

> 📌 Note: Due to the small dataset size, results are not generalizable but serve as a strong proof-of-concept.
