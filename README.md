# 📊 Student Performance Analysis (EDA Project)

## 📌 Project Overview
This project performs **Exploratory Data Analysis (EDA)** on student academic performance data using **Python**.  
The goal is to analyze marks, identify top-performing students, compare gender-wise performance, and visualize score distributions.

This project focuses on **data analysis**, not machine learning.

---

## 🛠️ Tools & Libraries Used
- Python
- Pandas
- NumPy
- Matplotlib

---

## 📁 Dataset Information
- File name: `students_performance_100.csv`
- Total records: **100 students**
- Columns:
  - `student_id`
  - `name`
  - `gender`
  - `maths`
  - `physics`
  - `chemistry`
  - `attendance`

---

## ⚙️ Feature Engineering
New columns created:
- `total_marks` → sum of Maths, Physics, Chemistry
- `average_marks` → average of subject marks
- `result` → Pass (≥150) / Fail (<150)

---

## 🔍 Analysis Performed

### ✅ 1. Total & Average Marks Calculation
- Calculated subject-wise totals and averages for each student

### ✅ 2. Top-Performing Students
- Identified top 5 students based on total marks
- Visualized using a bar chart

### ✅ 3. Gender-wise Performance
- Compared average marks of male and female students
- Analyzed pass/fail distribution by gender

### ✅ 4. Pass vs Fail Analysis
- Counted number of students who passed and failed
- Visualized using a pie chart

---

## 📊 Data Visualizations
The following plots were created:
- 📊 Bar chart – Average marks per subject
- 🥧 Pie chart – Pass vs Fail distribution
- 📈 Histogram – Distribution of total marks
- 📦 Boxplot – Subject-wise marks distribution

---

## 📌 Key Insights
- Most students scored above the passing threshold
- Female students showed slightly higher average performance
- Chemistry and Maths had a wider score range compared to Physics
- A few outliers were observed in subject marks

---

## ▶️ How to Run the Project

```bash
pip install pandas numpy matplotlib
