# 📊 Customer Churn Analysis & Prediction

> An end-to-end Data Analysis and Machine Learning project that explores customer churn patterns and builds a predictive model to identify customers likely to leave a telecom service.

---

## 📌 Project Overview

Customer churn is one of the biggest challenges faced by subscription-based businesses. Understanding why customers leave helps companies improve customer retention and reduce revenue loss.

In this project, customer data is analyzed using Python to uncover churn patterns, generate business insights, and build a machine learning model that predicts whether a customer will churn.

---

## 🎯 Objectives

- Understand customer behaviour
- Clean and preprocess raw data
- Perform Exploratory Data Analysis (EDA)
- Detect outliers
- Discover factors affecting customer churn
- Build a classification model
- Evaluate prediction performance

---

## 📂 Dataset

**Dataset:** IBM Telco Customer Churn Dataset

**Source:** Kaggle / IBM Sample Dataset

The dataset contains information about:

- Customer Demographics
- Internet Services
- Phone Services
- Contract Type
- Monthly Charges
- Total Charges
- Tenure
- Payment Method
- Customer Churn Status

---

## 🛠 Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## 📊 Project Workflow

### 1️⃣ Import Libraries

Imported all required Python libraries for data analysis, visualization, and machine learning.

---

### 2️⃣ Data Loading

- Loaded the customer churn dataset
- Explored dataset structure
- Checked dataset shape

---

### 3️⃣ Data Cleaning

Performed:

- Missing value handling
- Data type conversion
- Duplicate checking
- Basic preprocessing

---

### 4️⃣ Exploratory Data Analysis (EDA)

Analyzed customer behaviour using multiple visualizations.

Examples include:

- Churn Distribution
- Contract Type Analysis
- Monthly Charges Distribution
- Tenure Analysis
- Internet Service Analysis
- Correlation Heatmap

---

### 5️⃣ Outlier Detection

Used Boxplots to identify unusual values in numerical features.

---

### 6️⃣ Business Insights

Key findings include:

- Customers with **Month-to-Month contracts** are more likely to churn.
- Higher monthly charges are associated with increased churn.
- Customers with shorter tenure tend to leave more frequently.
- Long-term customers are generally more loyal.
- Contract type plays an important role in customer retention.

---

## 🤖 Machine Learning

### Problem Type

**Binary Classification**

### Target Variable

```
Churn
```

### Model Used

- Logistic Regression

### Workflow

- Feature Selection
- Data Preprocessing
- Train-Test Split
- Model Training
- Prediction
- Model Evaluation

---

## 📈 Model Evaluation

The classification model is evaluated using metrics such as:

- Accuracy Score
- Confusion Matrix
- Classification Report

---

## 📁 Project Structure

```
Customer_Churn_Analysis/
│
├── README.md
├── Customer_Churn_Project.ipynb
└── requirements.txt
```

## 👨‍💻 Author

**Bansi Sojitra**

Aspiring Data Analyst | Machine Learning Enthusiast | Python Developer

---

## ⭐ Support

If you found this project helpful, consider giving this repository a **⭐ Star**.
