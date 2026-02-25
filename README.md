# 🚗 Intelligent Vehicle Price Estimation System  
### End-to-End Machine Learning Deployment Project

> Transforming raw automotive data into a deployed predictive intelligence system.

---

## 📌 Overview

This project was developed during the **5-Day Intensive Workshop on “Machine Learning: From Basics to Deployment”** conducted by *Innomatics Research Labs*.

The objective was to build a complete machine learning pipeline that predicts vehicle prices using **Linear Regression**, and deploy it as an interactive web application using **Streamlit**.

This repository demonstrates the full ML lifecycle — from raw data to real-time predictions.

---

## 🎯 Problem Statement

Accurately estimating used car prices is a common real-world challenge in the automotive resale market.  
This project builds a data-driven system that predicts car prices based on multiple influencing factors such as:

- Brand & Model
- Year of Manufacture
- Fuel Type
- Transmission
- Kilometers Driven
- Engine & Technical Specifications
- Ownership History

---

## 🔄 Machine Learning Lifecycle

### 1️⃣ Data Acquisition
- Raw dataset: `car_data.xlsx`

### 2️⃣ Exploratory Data Analysis (EDA)
- Identified trends and correlations
- Visualized relationships between features and price
- Detected outliers and inconsistencies

### 3️⃣ Data Cleaning & Preprocessing
- Handled missing values
- Encoded categorical variables
- Removed redundant or noisy data
- Prepared features for regression modeling

### 4️⃣ Model Development
- Implemented **Linear Regression (Scikit-learn)**
- Evaluated model performance
- Analyzed feature importance

### 5️⃣ Deployment
- Serialized trained model using `pickle`
- Built a Streamlit-based web interface
- Enabled real-time price prediction via user input

---

## 🛠 Tech Stack

- **Programming Language:** Python  
- **Data Processing:** Pandas, NumPy  
- **Visualization:** Matplotlib, Seaborn  
- **Machine Learning:** Scikit-learn  
- **Deployment:** Streamlit  
- **Environment:** Jupyter Notebook / VS Code  

---

## 📂 Repository Structure

```
Innomatics-Workshop/
│
├── Car Price Prediction.ipynb   # Data analysis & model training
├── app.py                       # Streamlit web application
├── linear_model.pkl             # Trained ML model
├── car_data.xlsx                # Raw dataset
├── feature_importance.xlsx      # Feature impact analysis
├── requirements.txt             # Project dependencies
└── README.md                    # Documentation
```

---

## 🚀 How to Run the Application

### Step 1: Clone the Repository

```bash
git clone https://github.com/Yogi1107/Innomatics-Workshop.git
cd Innomatics-Workshop
```

### Step 2: Install Dependencies

```bash
pip install -r requirements.txt
```

### Step 3: Run the Streamlit App

```bash
streamlit run app.py
```

The application will open in your browser, where you can enter vehicle specifications and receive an instant predicted price.

---

## 📦 requirements.txt

```
streamlit
pandas
scikit-learn
openpyxl
```

---

## 📈 Key Learnings

- Practical implementation of the ML lifecycle  
- Regression-based predictive modeling  
- Feature engineering & preprocessing techniques  
- Model serialization and deployment  
- Building interactive ML-powered web applications  

---

## 👨‍🏫 Workshop Conducted By
Innomatics Research Labs  

## 👨‍💻 Developed By
Sanganna Rajshekhar Jalde
---

⭐ If you found this project helpful, consider giving it a star!
