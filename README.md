# 🏠 House Price Prediction Using Machine Learning

A Machine Learning web application that predicts house prices using multiple regression algorithms. The project compares the performance of various regression models and allows users to estimate house prices through an interactive Flask web interface.

---

## 📌 Project Overview

This project predicts house prices based on key housing attributes such as average area income, house age, number of rooms, number of bedrooms, and area population. Multiple regression models are trained, evaluated, and deployed, allowing users to compare prediction performance and generate real-time house price estimates.

---

## ✨ Features

- 🏠 House Price Prediction
- 🤖 Multiple Machine Learning Models
- 🌐 Interactive Flask Web Application
- 📊 Model Performance Comparison
- 📈 Real-Time Price Prediction
- 💾 Pre-trained Pickle Models
- 📋 Evaluation Metrics Display
- 📂 Clean and User-Friendly Interface

---

## 🛠️ Tech Stack

- Python
- Flask
- Scikit-Learn
- Pandas
- NumPy
- LightGBM
- XGBoost
- HTML5
- CSS3
- Pickle

---

## 📂 Project Structure

```text
House-Price-Prediction/
│
├── app.py
├── model.py
├── USA_Housing.csv
├── model_evaluation_results.csv
├── requirements.txt
├── README.md
│
├── LinearRegression.pkl
├── RidgeRegression.pkl
├── LassoRegression.pkl
├── ElasticNet.pkl
├── PolynomialRegression.pkl
├── RobustRegression.pkl
├── SGDRegressor.pkl
├── RandomForest.pkl
├── ANN.pkl
├── SVM.pkl
├── LGBM.pkl
├── KNN.pkl
│
├── templates/
│   ├── index.html
│   ├── results.html
│   └── model.html
│
└── static/
```

---

## 🚀 Installation

Clone the repository

```bash
git clone https://github.com/your-username/House-Price-Prediction.git
```

Navigate to the project

```bash
cd House-Price-Prediction
```

Install dependencies

```bash
pip install -r requirements.txt
```

---

## ▶️ Run the Application

```bash
python app.py
```

Open your browser

```
http://127.0.0.1:5000
```

---

## 📋 Input Features

- Average Area Income
- Average Area House Age
- Average Number of Rooms
- Average Number of Bedrooms
- Area Population

---

## 🤖 Machine Learning Models

- Linear Regression
- Robust Regression
- Ridge Regression
- Lasso Regression
- Elastic Net
- Polynomial Regression
- SGD Regressor
- Artificial Neural Network (ANN)
- Random Forest Regressor
- Support Vector Machine (SVM)
- LightGBM
- K-Nearest Neighbors (KNN)

---

## 📊 Model Evaluation Metrics

The project compares model performance using:

- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- R² Score

---

## ⚙️ Workflow

1. Load the USA Housing dataset.
2. Preprocess the data.
3. Train multiple regression models.
4. Evaluate model performance.
5. Save trained models.
6. Deploy the best-performing models using Flask.
7. Predict house prices based on user inputs.

---

## 💡 Applications

- Real Estate Price Estimation
- Property Value Prediction
- Housing Market Analysis
- Educational Machine Learning Project
- Regression Model Comparison

---

## 🔮 Future Improvements

- Automatic Best Model Selection
- Feature Importance Visualization
- Interactive Charts
- User Authentication
- Cloud Deployment
- Deep Learning Enhancements
- Advanced Data Visualization
- Responsive Dashboard

---

## 📦 Requirements

- Python 3.x
- Flask
- Scikit-Learn
- Pandas
- NumPy
- LightGBM
- XGBoost

Install all dependencies using:

```bash
pip install -r requirements.txt
```

---

## 👩‍💻 Author

**Sanika Kulkarni**

B.Tech – Artificial Intelligence and Data Science

---

## ⭐ Support

If you found this project useful, consider giving this repository a ⭐ on GitHub.