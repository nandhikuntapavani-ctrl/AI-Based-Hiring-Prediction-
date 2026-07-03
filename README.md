# 🤖 AI-Based Hiring Prediction System using Machine Learning

![Python](https://img.shields.io/badge/Python-3.x-blue)
![Machine Learning](https://img.shields.io/badge/Machine%20Learning-Project-green)
![Status](https://img.shields.io/badge/Status-Completed-success)
![Platform](https://img.shields.io/badge/Platform-Google%20Colab-orange)

---

## 📌 Project Overview

Recruitment is a time-consuming process for companies, especially when screening thousands of applications. Human recruiters often spend significant effort evaluating candidate profiles, skills, experience, and education.

This project builds an **AI-Based Hiring Prediction System** using **Machine Learning** to predict whether a candidate should be:

✅ Hired
❌ Rejected

The system analyzes candidate-related features and helps automate the hiring decision process.

---

## 🎯 Objective

The main objectives of this project are:

* Analyze candidate recruitment data
* Preprocess and clean dataset
* Identify important hiring factors
* Train Machine Learning models
* Predict hiring decisions accurately

---

## 📂 Dataset Information

The dataset contains candidate-related features such as:

* Candidate Name
* Age
* Gender
* Education Level
* Skills Score
* Interview Score
* Experience (Years)
* Certifications
* Technical Assessment Score
* Communication Score
* Projects Completed

### Target Variable

**Recruiter Decision**

| Value | Meaning |
| ----- | ------- |
| 0     | Reject  |
| 1     | Hire    |

---

## 🛠️ Tech Stack

* **Programming Language:** Python
* **Platform:** Google Colab

### Libraries Used

* pandas
* NumPy
* Matplotlib
* Seaborn
* scikit-learn

---

## 🔄 Project Workflow

### 1️⃣ Data Loading

* Import dataset into Colab
* Load CSV file using Pandas
* Check dataset shape and columns

### 2️⃣ Data Preprocessing

* Handle missing values
* Remove duplicates
* Encode categorical features
* Clean inconsistent entries

### 3️⃣ Exploratory Data Analysis (EDA)

Analyzed:

* Candidate distribution
* Hiring ratio
* Feature importance
* Score distributions

### 4️⃣ Feature Engineering

* Convert categorical features into numerical format
* Normalize numerical values
* Train-test split

### 5️⃣ Model Training

Machine Learning models used:

* Logistic Regression
* Decision Tree
* Random Forest
* Support Vector Machine (SVM)

### 6️⃣ Model Evaluation

Metrics used:

* Accuracy
* Precision
* Recall
* F1-score
* Confusion Matrix

---

## 📊 Machine Learning Pipeline

```text id="hirepipe1"
Raw Dataset
   ↓
Data Cleaning
   ↓
EDA
   ↓
Feature Encoding
   ↓
Train-Test Split
   ↓
Model Training
   ↓
Evaluation
   ↓
Prediction
```

---

## 🚀 Results

The trained model successfully predicts hiring decisions based on candidate attributes.

### Key Outcomes

✔ Reduced manual screening effort
✔ Faster hiring decisions
✔ Improved recruitment efficiency
✔ Data-driven candidate evaluation

---

## 📈 Sample Insights

* Higher technical scores increase hiring probability
* Candidates with more experience have better selection chances
* Certifications positively influence recruiter decisions
* Strong communication skills improve selection rate

---



