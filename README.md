# Crop_Fertilizer_Prediction

Machine Learning–Driven Precision Agriculture for Smart Crop and Fertilizer Recommendations


📘 Overview

This project uses machine learning algorithms to predict the most suitable crop and fertilizer type for specific soil and weather conditions.
By analyzing essential agricultural parameters like NPK levels, temperature, humidity, pH, and rainfall, the model enables data-driven farming to optimize yield and resource usage.

This system can serve as the backend for an AI-powered agricultural advisory platform for farmers, agronomists, and agricultural startups.

🎯 Key Objectives

Predict the optimal crop for a given soil composition and environmental condition.

Recommend the ideal fertilizer to improve soil fertility for that crop.

Enable precision farming through explainable, data-based insights.

Provide a scalable ML pipeline ready for deployment in real-time applications.

📂 Dataset

Source: Kaggle – Crop Recommendation Dataset

Attributes:

Feature	Description
N	Nitrogen content in soil
P	Phosphorus content in soil
K	Potassium content in soil
temperature	Average temperature (°C)
humidity	Relative humidity (%)
ph	Soil pH level
rainfall	Rainfall in mm
label	Target variable (type of crop)
🧠 Workflow

Data Loading and Cleaning

Imported and explored the dataset.

Checked for missing values, outliers, and inconsistencies.

Exploratory Data Analysis (EDA)

Used seaborn and matplotlib for data visualization.

Analyzed correlations between soil nutrients, environmental factors, and crops.

Model Building

Trained a Random Forest Classifier for high-accuracy predictions.

Used train-test split and feature scaling to improve generalization.

Measured accuracy, precision, recall, and confusion matrix.

Fertilizer Recommendation Logic

Implemented a rule-based or mapping approach that links specific crops with ideal fertilizer combinations (NPK-based).

Integrated predictive insights for better fertilizer selection.

Deployment Readiness

Model saved using joblib for easy integration into web apps or APIs (Flask/Django).

🧩 Technologies Used
Category	Tools / Libraries
Language	Python
Libraries	NumPy, Pandas, Matplotlib, Seaborn, Scikit-learn
IDE / Platform	Google Colab / Jupyter Notebook
Model Storage	Joblib
Visualization	Seaborn, Matplotlib
Deployment (Future Scope)	Flask or Dash
📊 Model Evaluation
Metric	Result
Accuracy	~98%
Precision	High
Recall	High
Confusion Matrix	Well-balanced across classes

The Random Forest Classifier outperformed other algorithms, showing strong generalization for unseen soil and weather data.


💡 Future Scope

Real-time prediction using IoT-based soil sensors and weather APIs

Integration with Flask/Django web application for live recommendation dashboards

Enhanced fertilizer prediction using multi-class classification models

Addition of yield prediction and soil health tracking module
