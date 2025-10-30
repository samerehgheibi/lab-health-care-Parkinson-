# lab-health-care-Parkinson-
# 🧠 Parkinson’s Disease Data Analysis – Lab 2

### 📊 Course: Health Data Analytics | University Lab Project

This notebook focuses on the analysis of **Parkinson’s Disease dataset** using data science techniques to explore, visualize, and model the data for early disease detection.

---

## 🎯 Objective

The main goal of this lab is to:
- Understand the structure of the Parkinson’s dataset  
- Perform **data preprocessing** (handling missing values, normalization, and feature selection)  
- Conduct **exploratory data analysis (EDA)** to identify key variables  
- Apply **machine learning algorithms** to distinguish between healthy and affected patients  
- Evaluate model performance using metrics such as accuracy, precision, and recall  

---

## 🧩 Dataset

The dataset used in this lab contains biomedical voice measurements from individuals with and without Parkinson’s disease.  
Each record includes attributes such as:
- Average vocal fundamental frequency (`MDVP:Fo(Hz)`)
- Variation in frequency (`MDVP:Fhi(Hz)`, `MDVP:Flo(Hz)`)
- Measures of variation in amplitude (`MDVP:Jitter(%)`, `MDVP:Shimmer`)
- Nonlinear dynamical complexity measures (`DFA`, `RPDE`)
- Target variable: `status` (1 = Parkinson’s, 0 = Healthy)

---

## ⚙️ Methodology

1. **Import & Inspect** – Load dataset, check shape and columns  
2. **Data Cleaning** – Remove missing or irrelevant features  
3. **Feature Engineering** – Normalize and select relevant variables  
4. **Exploratory Data Analysis (EDA)** – Use histograms, scatter plots, and correlation heatmaps  
5. **Modeling** – Train classifiers (e.g., Logistic Regression, SVM, Random Forest)  
6. **Evaluation** – Compare performance metrics and visualize ROC curves  

---

## 📈 Results

- Random Forest achieved the **highest accuracy** in classification  
- Voice-related parameters showed strong correlation with Parkinson’s presence  
- Normalization and feature selection significantly improved model stability  

---

## 🧠 Tools & Libraries

- Python 3  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- Scikit-learn  

healthcare.”

