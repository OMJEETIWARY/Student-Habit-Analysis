# Student Habits Performance Analysis

## 📌 Overview
This project analyzes how different student habits affect academic performance. Using the `student_habits_performance.csv` dataset, the notebook covers data preprocessing, exploratory data analysis (EDA), feature engineering, and regression modeling. The goal is to identify key factors influencing exam scores and build predictive models.

---

## 📂 Dataset
- **File**: `student_habits_performance.csv`  
- **Target Variable**: `exam_score`  
- **Features**: Includes both numerical and categorical variables related to student habits (e.g., study hours, sleep patterns, extracurricular activities).  

---

## 🔎 Methodology
1. **Data Preprocessing**
   - Handle missing values  
   - Encode categorical features  
   - Scale numerical variables  

2. **Exploratory Data Analysis (EDA)**
   - Histograms of features  
   - Correlation heatmap to detect relationships  

3. **Feature Engineering**
   - Separation of target (`exam_score`) from predictors  

4. **Modeling**
   - Linear Regression  
   - Random Forest Regressor  

5. **Evaluation**
   - Root Mean Squared Error (RMSE)  
   - R² Score  

---

## 📊 Results
- Visual insights from EDA highlight correlations between habits and performance.  
- Random Forest generally provides higher predictive accuracy compared to Linear Regression.  

---

## 🚀 How to Run
1. Clone the repo:  
   ```bash
   git clone https://github.com/your-username/student-habits-performance.git
   cd student-habits-performance

