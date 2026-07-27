# 🚚 Food Delivery Time Analysis & Prediction

> A complete Data Analysis & Machine Learning project using a real-world food delivery dataset. This project focuses on data cleaning, exploratory data analysis (EDA), business insights, feature engineering, and delivery time prediction.

---

## 📌 Project Overview

Food delivery companies need to understand which factors increase delivery time so they can improve customer satisfaction and operational efficiency.

In this project, I analyzed a real-world food delivery dataset, performed extensive data cleaning, generated business insights, engineered new features, and built a machine learning model to predict delivery time.

---

## 🎯 Project Objectives

- Clean messy real-world data
- Handle missing values and duplicates
- Perform Exploratory Data Analysis (EDA)
- Detect and handle outliers
- Engineer meaningful features
- Discover business insights
- Build a regression model to predict delivery time
- Visualize important findings

---

## 📂 Dataset

**Source:** Kaggle Food Delivery Dataset

The dataset contains information about:

- Delivery Partner Details
- Customer Ratings
- Weather Conditions
- Traffic Density
- Vehicle Type
- Festival Status
- City Type
- Delivery Distance
- Delivery Time

---

## 🛠 Technologies Used

- Python
- Jupyter Notebook
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn

---

## 📊 Project Workflow

### 1️⃣ Import Libraries

Imported all required libraries for data analysis, visualization, preprocessing and machine learning.

---

### 2️⃣ Load Dataset

Loaded the dataset using Pandas and inspected its structure.

---

### 3️⃣ Data Understanding

Performed:

- Dataset Shape
- Data Types
- Missing Values
- Duplicate Records
- Statistical Summary

---

### 4️⃣ Data Cleaning

The dataset was cleaned by:

- Removing unwanted spaces
- Correcting column names
- Handling missing values
- Removing duplicate records
- Converting incorrect data types

---

### 5️⃣ Feature Engineering

Created meaningful features such as:

- Delivery Distance
- Date-based Features
- Time-related Features (where applicable)

These engineered features improve analysis and prediction performance.

---

### 6️⃣ Outlier Detection

Detected outliers using:

- Boxplots
- IQR Method

This helps identify abnormal delivery behaviour.

---

### 7️⃣ Exploratory Data Analysis (EDA)

Several visualizations were created to understand delivery behaviour.

#### Distribution Analysis

- Delivery Time Distribution

#### Categorical Analysis

- Delivery Time vs Traffic Density
- Delivery Time vs Weather Condition
- Delivery Time vs City Type

#### Relationship Analysis

- Distance vs Delivery Time
- Ratings vs Delivery Time

#### Correlation Analysis

- Correlation Heatmap

---

## 📈 Business Insights

Key findings include:

- Heavy traffic significantly increases delivery time.
- Weather conditions directly affect delivery efficiency.
- Longer delivery distance generally increases delivery duration.
- Better customer ratings are associated with faster deliveries.
- City type influences delivery performance.
- Multiple operational factors contribute to delivery delays.

---

## 🤖 Machine Learning

A regression model was built to predict:

**Target Variable**

```
Time_taken_min
```

Model pipeline includes:

- Feature Selection
- Data Splitting
- Model Training
- Prediction
- Model Evaluation

---

## 📉 Model Evaluation

The notebook evaluates model performance using regression metrics and visualizations including:

- Actual vs Predicted Values
- Prediction Performance Plot

---

## 📷 Project Outputs

The notebook contains:

- Data Cleaning
- Feature Engineering
- EDA Visualizations
- Correlation Heatmap
- Business Insights
- Machine Learning Prediction
- Final Conclusions

---

## 📁 Project Structure

```
Food_Delivery_analysis_project/
│
├── README.md
├── food_delivery_project.ipynb
└── train.csv
```

---

## 💡 Skills Demonstrated

- Data Cleaning
- Data Wrangling
- Exploratory Data Analysis
- Feature Engineering
- Data Visualization
- Business Analysis
- Machine Learning
- Regression
- Python Programming

---

## 🚀 Future Improvements

- Hyperparameter Tuning
- Advanced Regression Models
- Feature Selection Techniques
- Model Deployment using Flask/FastAPI
- Interactive Dashboard using Power BI or Streamlit

---

## 👨‍💻 Author

**Bansi Sojitra**

Aspiring Data Analyst | Machine Learning Enthusiast | Python Developer

---

⭐ If you found this project useful, consider giving this repository a Star.
