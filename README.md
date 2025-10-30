# Students Adaptability Level in Online Education 🎓

This project presents a **comparative study of KNN and Decision Tree classifiers** for predicting students' adaptability to online education.  
It explores how various demographic and learning-related factors affect a student's ability to adapt to digital learning environments.

---

## 🎯 Objective
To analyze and compare the performance of **K-Nearest Neighbors (KNN)** and **Decision Tree** algorithms in classifying students’ adaptability levels in online education.

---

## 📂 Dataset
**Filename:** `students_adaptability_level_online_education.csv`

**Features include:**
- Gender, Age, Education Level  
- Institution Type  
- IT Student (Yes/No)  
- Internet Access  
- Network Type  
- Device Type  
- Self-Learning Capability  
- Adaptability Level (Target)

> The dataset is used solely for educational and research purposes.

---

## 🧠 Methodology
1. **Data Loading & Inspection**
   - Checked missing values, duplicates, and feature types.

2. **Exploratory Data Analysis (EDA)**
   - Generated automated data profiling using `ydata_profiling`.
   - Visualized distributions, correlations, and outliers.

3. **Data Preprocessing**
   - Encoded categorical variables using `OrdinalEncoder`.
   - Split dataset into training and testing sets.

4. **Modeling**
   - Implemented:
     - K-Nearest Neighbors (KNN)
     - Decision Tree Classifier
   - Evaluated models using accuracy, confusion matrix, and classification report.

5. **Model Comparison**
   - Compared both models’ performance to identify the better classifier for adaptability prediction.

---

## 📊 Results
| Model | Accuracy |
|--------|-----------|
| KNN | ~X% |
| Decision Tree | ~Y% |

> (Replace with your actual results after execution.)

---

## ⚙️ Requirements

Install all dependencies using:
```bash
pip install -r requirements.txt
