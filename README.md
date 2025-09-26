# 🎓 Student Score Prediction – Elevvo Internship

For the first internship task, I worked on building a Machine Learning model to predict students’ exam scores based on several factors such as:  

📌 Study hours – Attendance – Sleep – Extracurricular activities – Family income – etc.  

---

## ✅ Steps
- Data Cleaning & Encoding (converted categorical values into numeric).  
- Exploratory Data Analysis (EDA) to understand key influencing factors.  
- Splitting data into training and testing sets.  
- Training a **Linear Regression Model**.  
- Trying **Polynomial Regression (degree=2)** as a Bonus.  
- Model evaluation using **MSE** and **R²**.  
- Visualization:  
  - Scatter plot (Actual vs Predicted).  
  - Correlation Heatmap.  
- Extracted **Feature Importance** from the Linear model to identify the most impactful features.  

---

## 📊 Results
### Linear Regression
- Mean Squared Error (MSE): **4.40**  
- R² Score: **0.689**  

### Polynomial Regression (degree=2)
- Mean Squared Error (MSE): **3.55**  
- R² Score: **0.749**  

---

## 🔎 Insights
- Polynomial Regression performed **better** than Linear Regression, achieving a lower error and higher R².  
- **Hours_Studied, Previous_Scores, and Attendance** were the most significant predictors of exam performance.  
- Other features such as **extracurricular activities** and **peer influence** had less impact.  

---

## ✅ Conclusion
Polynomial regression was able to capture more complex patterns in the data, leading to improved accuracy.  
However, study-related factors and prior performance remain the strongest indicators of student success.  

---

📂 **Full code + analysis is available on GitHub:**  
👉 [Student Score Prediction Repo](https://github.com/noran66/Student-Score-Prediction.git)
