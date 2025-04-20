# Fraudulent_Claim_Detection
# Group Members: Naresh Padiyar, Sruthi Melepurath

## 📌 Project Overview

Global Insure, a leading insurance provider, handles thousands of claims every year. A significant portion of these claims are later discovered to be fraudulent, resulting in major financial losses. This project aims to build a predictive machine learning model to classify claims as **fraudulent** or **legitimate**, enabling early detection and proactive fraud prevention.

---

## 🧾 Problem Statement

Currently, Global Insure relies on manual inspections to detect fraudulent claims. This method is time-consuming, inefficient, and often identifies fraud only **after** the company has made payments. There is a need for a **data-driven solution** to identify high-risk claims early in the approval process.

---

## 🎯 Business Objective

- Develop a model that classifies insurance claims as **fraudulent** or **legitimate**.
- Use historical claim data and customer profiles to extract meaningful patterns.
- Predict the **likelihood of fraud** for new claims before approval.
- Minimize financial losses and optimize claims processing efficiency.

---

## 📊 Key Questions Addressed

1. **How can we analyse historical claim data to detect patterns indicating fraud?**
2. **Which features are most predictive of fraudulent behaviour?**
3. **Can we predict the likelihood of fraud for incoming claims?**
4. **What actionable insights can be drawn from the model to improve fraud detection?**

---

## 🧰 Tools & Technologies

- **Python**
- **Pandas, NumPy** – Data manipulation
- **Matplotlib, Seaborn** – Exploratory Data Analysis (EDA)
- **Scikit-learn** – Machine Learning models and evaluation
- **Jupyter Notebook** – Development environment

---

## 🛠️ Assignment Tasks / Methodology

### 1. Data Preparation
- Load and inspect the dataset
- Understand schema, data types, and missing values

### 2. Data Cleaning
- Handle missing values, duplicates, and data inconsistencies
- Convert categorical variables to numerical

### 3. Train-Validation Split
- Use a **70-30 split** to divide data into training and validation sets

### 4. Exploratory Data Analysis (EDA)
- Analyze class distribution (fraudulent vs legitimate)
- Visualize key relationships (e.g., claim amount, incident type, customer hobbies)

### 5. Feature Engineering
- Create new features based on domain knowledge
- Normalize/scale numerical features
- Encode categorical features

### 6. Model Building
- Train multiple models (e.g., Logistic Regression, Random Forest)
- Compare performance using metrics such as **Accuracy**, **Recall**, **Precision**, and **F1 Score**

### 7. Predicting & Model Evaluation
- Evaluate model performance on the validation set
- Select the best-performing model (based on recall and interpretability)

---

✅ **Logistic Regression** was selected due to better accuracy, recall, and model interpretability.

---

## 💡 Key Insights

- Customers with hobbies like **Chess** and **Cross-Fit** are more likely to file fraudulent claims.
- Claims with **Minor Damage** are more likely to be fraudulent than **Total Loss** claims.
- The model allows for **early risk assessment**, enabling faster and smarter claim processing.

---

