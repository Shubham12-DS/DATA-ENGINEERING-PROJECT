# 🛒 BigMart Sales Prediction – Data Engineering & Machine Learning Project

A complete **Data Engineering and Machine Learning pipeline** that predicts product sales for BigMart outlets using multiple regression models and an interactive web application built with Streamlit.

🔗 **GitHub Repository:**  
https://github.com/Shubham12-DS/DATA-ENGINEERING-PROJECT

---

# 🌐 Live Demo

🚀 Try the live application here:

👉 **Streamlit App:**  
https://your-streamlit-app-link.streamlit.app

*(Replace this link after deploying your Streamlit application.)*

---

# 📌 Project Overview

BigMart is a retail chain that sells multiple product categories across different outlets.

The objective of this project is to **predict the sales of products in different BigMart stores using machine learning models**.

This project demonstrates an **end-to-end data engineering workflow**, including:

- Data extraction from XML files
- Data loading into MySQL database
- Data preprocessing and transformation
- Feature engineering
- Training multiple machine learning models
- Automatic model selection
- Deployment using Streamlit

---

# 📊 Features Used

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

# 🧠 Machine Learning Models Used

The following regression models were trained and evaluated:

- Gradient Boosting Regressor
- Random Forest Regressor
- Linear Regression

The **best performing model** was automatically selected based on evaluation metrics.

---

# ⚙️ Technologies Used

This project uses the following technologies:

- Python
- Pandas
- NumPy
- Scikit-learn
- MySQL
- Streamlit

---

# 📂 Project Structure

```
DATA-ENGINEERING-PROJECT
│
├── app.py
├── bigmart_best_model.pkl
├── load_data.py
├── model_creation.py
├── requirements.txt
└── README.md
```

---

# 🚀 How to Run the Project

## 1️⃣ Clone the Repository

```bash
git clone https://github.com/Shubham12-DS/DATA-ENGINEERING-PROJECT.git
cd DATA-ENGINEERING-PROJECT
```

---

## 2️⃣ Install Required Libraries

```bash
pip install -r requirements.txt
```

---

## 3️⃣ Run the Streamlit Application

```bash
streamlit run app.py
```

---

# 🖥️ Streamlit Application Features

The Streamlit web application allows users to:

- Enter product information
- Select outlet details
- Predict sales instantly
- View prediction results interactively

---

# 📈 Future Improvements

Possible improvements for the project include:

- Adding a data visualization dashboard
- Deploying the application on cloud platforms
- Adding feature importance visualization
- Implementing automated model retraining
- Integrating real-time data pipeline

---

# 👨‍💻 Author

**Shubham Shinde**  
Machine Learning & Data Science Enthusiast

GitHub:  
https://github.com/Shubham12-DS

---

⭐ If you found this project helpful, please consider **starring the repository**!
