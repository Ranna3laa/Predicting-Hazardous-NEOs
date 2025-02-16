# 🚀 Predicting Hazardous Near-Earth Objects (NEOs) 🌍☄️

## 📌 Project Overview
This project focuses on predicting whether a **Near-Earth Object (NEO)** is hazardous using NASA’s real-world dataset. The dataset contains **338,199 records** of space objects observed from **1910 to 2024**, with some classified as "hazardous," meaning they pose a potential threat to Earth.

## 🎯 Project Goal
The objective is to develop a **Machine Learning model** that accurately predicts the hazard level of NEOs. **Early identification** of dangerous asteroids is crucial for **planetary defense** and space safety.

## 📊 Dataset Overview
- **Source**: NASA's NEO Observations
- **Timeframe**: 1910 - 2024
- **Total Records**: 338,199
- **Target Variable**: `is_hazardous` (1 = Hazardous, 0 = Non-Hazardous)

## 🛠 Technologies & Tools
The following tools and libraries will be used to process data and build the classification model:
- **Python** 🐍: Pandas, NumPy, Scikit-learn
- **Machine Learning Models** 🤖: Decision Tree, Random Forest, Logistic Regression
- **Data Visualization** 📊: Matplotlib, Seaborn, Plotly
- **Feature Engineering & Data Preprocessing** 🔄

## 🚀 Project Workflow
1. **Data Importing & Cleaning**
   - Import the dataset and address missing values.
   - Ensure the data is clean and reliable for accurate modeling.

2. **Exploratory Data Analysis (EDA)**
   - Perform thorough **EDA** to uncover patterns and trends.
   - Use visualization libraries (Matplotlib, Seaborn, Plotly) to create informative graphs.

3. **Data Preprocessing**
   - Perform necessary preprocessing steps including:
     - Feature selection and encoding categorical variables.
     - Normalizing or scaling numerical features.
   - **Handling Imbalanced Classes:** The `is_hazardous` target column is likely imbalanced. To address this:
     - Use **SMOTE (Synthetic Minority Over-sampling Technique)**
     - Apply **undersampling** methods
     - Adjust **class weights**
     - Use **Balanced Accuracy** as a performance metric

4. **Model Training & Evaluation**
   - Train one or more **machine learning models** using the preprocessed data.
   - Evaluate model performance using:
     - **Precision, Recall, F1-Score, and AUC-ROC Curve**
   - Select the best-performing model based on these metrics.

## 🔥 Why This Matters?
An accurate **NEO prediction model** can contribute to planetary defense strategies by helping scientists and space agencies **assess potential threats** and take necessary preventive measures.

---
🌠 **Analyze Space. Predict Threats. Protect the Planet.** 💫
