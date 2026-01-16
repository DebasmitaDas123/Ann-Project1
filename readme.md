# Customer Churn Prediction using Artificial Neural Network (ANN)

This project predicts whether a customer will *stay with or leave a company* using an *Artificial Neural Network (ANN)* trained on a churn dataset.  
It follows an end-to-end machine learning workflow, including *model training, **prediction, and **deployment using Streamlit*.

---

## 📌 Project Description

Customer churn prediction is an important problem in business analytics, especially in banking and subscription-based services.  
This project uses customer demographic and financial data to predict churn probability.

The project is divided into *three major components*:
1. *Model Building & Training*
2. *Prediction Pipeline*
3. *Streamlit Web Application*

---

## 🧠 1. Model Building & Training

- Performed Exploratory Data Analysis (EDA)
- Handled categorical and numerical features using ColumnTransformer
- Built an Artificial Neural Network using TensorFlow & Keras
- Trained and evaluated the model
- Saved:
  - Trained ANN model (model.h5)
  - Preprocessing pipeline (preprocessor.pkl)

*Relevant files:*
- eda.ipynb
- pred3.ipynb
- model.h5
- preprocessor.pkl

---

## 🔮 2. Prediction Pipeline

- Loads the trained ANN model
- Loads the saved preprocessing pipeline
- Applies the *same preprocessing used during training*
- Predicts customer churn probability

This ensures consistency and prevents data leakage.

---

## 🌐 3. Streamlit Web Application

An interactive Streamlit app that allows users to:
- Enter customer details
- Get real-time churn probability
- View a clear churn / non-churn decision

*File:*
- app.py

---

## 🧾 Input Features

- Credit Score  
- Geography  
- Gender  
- Age  
- Tenure  
- Balance  
- Number of Products  
- Credit Card Status  
- Active Member Status  
- Estimated Salary  

---

## 🛠️ Tech Stack Used

### Programming & ML
- Python
- TensorFlow (2.15.0)
- Keras

### Data Processing & Visualization
- Pandas
- NumPy
- Scikit-learn
- Seaborn
- Matplotlib

### Deployment
- Streamlit

### Utilities
- Pickle
- TQDM
- TensorBoard
- IPyKernel

---
---

## 👤 Author Details

*Name:* Debasmita Das
Degree: B.Tech in Computer Science Engineering (Artificial Intelligence & Machine Learning)

Institute: Haldia Institute of Technology

Location: West Bengal, India
*GitHub:*  
https://github.com/DebasmitaDas123

---

## 📦 Installation & Setup

### Step 1: Clone the Repository
```bash
git clone https://github.com/your-username/customer-churn-ann.git
cd customer-churn-ann
pip install -r requirements.txt
streamlit run app.py

