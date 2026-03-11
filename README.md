# 🛒 BigMart Sales Prediction

A **Machine Learning project** that predicts product sales for BigMart outlets using multiple regression models and an interactive web application built with Streamlit.

---

## 🌐 Live Demo

🚀 Try the live application here:

👉 **Streamlit Live App:**  
https://your-streamlit-app-link.streamlit.app

> Replace the above link with your actual deployed app link after deploying the project.

---

## 📌 Project Overview

BigMart is a retail chain that sells multiple product categories across different outlets.

The goal of this project is to **predict the sales of products in different BigMart stores using machine learning models**.

This project includes:

- Data loading from XML files
- Data storage using MySQL
- Data preprocessing and feature engineering
- Training multiple machine learning models
- Selecting the best performing model
- Deploying a prediction system using Streamlit

---

## 📊 Features Used

The model uses the following features to predict sales:

- Item Weight
- Item Fat Content
- Item Visibility
- Item Type
- Item MRP
- Outlet Size
- Outlet Location Type
- Outlet Type
- Outlet Age

---

## 🧠 Machine Learning Models Used

The following regression models were trained and evaluated:

- Gradient Boosting Regressor
- Random Forest Regressor
- Linear Regression

The **best performing model** was automatically selected based on model evaluation metrics.

---

## ⚙️ Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- MySQL
- Streamlit

---

## 📂 Project Structure

```
BigMart-Sales-Prediction
│
├── app.py
├── bigmart_best_model.pkl
├── load_data.py
├── model_creation.py
├── requirements.txt
└── README.md
```

---

## 🚀 How to Run the Project

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/yourusername/bigmart-sales-prediction.git
cd bigmart-sales-prediction
```

---

### 2️⃣ Install Required Libraries

```bash
pip install -r requirements.txt
```

---

### 3️⃣ Run the Streamlit Application

```bash
streamlit run app.py
```

---

## 🖥️ Streamlit Application Features

The Streamlit web application allows users to:

- Enter product details
- Select outlet information
- Predict sales instantly
- View prediction results in an interactive interface

---

## 📈 Future Improvements

Possible improvements for this project:

- Add data visualization dashboard
- Deploy the application on cloud platforms
- Add feature importance visualization
- Implement automated model retraining
- Integrate real-time data pipeline

---

## 👨‍💻 Author

**Shubham Shinde**  
Machine Learning & Data Science Enthusiast

---

⭐ If you found this project useful, consider giving it a **star on GitHub**!
