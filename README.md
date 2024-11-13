# 📊 Customer Satisfaction Prediction App 🎯
###  🚀 Overview
The Customer Satisfaction Prediction App is a cutting-edge, machine learning-powered web application designed to predict customer satisfaction scores based on various features like gender, country, product quality, service quality, feedback score, and more. The app utilizes a Random Forest Regressor model trained on historical customer feedback data to provide accurate and actionable satisfaction predictions.

This application is tailored for businesses aiming to understand how different attributes influence customer satisfaction and enables data-driven decisions to enhance services or products.

## ⚙️ Features
### 📝 User Input Form
Users can input detailed customer information via an intuitive sidebar form.
Input categories include:
Gender
Country
Product Quality
Service Quality
Feedback Score
Loyalty Level
Age
Income
Purchase Frequency

## 🔮 Prediction
The app predicts a Customer Satisfaction Score using a trained Random Forest model based on the user's input.

## 📊 Feature Importance Visualization
Displays a bar chart illustrating the importance of each feature in predicting customer satisfaction.
Helps businesses prioritize the most influential factors affecting customer satisfaction.

## 📈 Model Evaluation Metrics
Mean Absolute Error (MAE): Shows the average of the absolute errors between predicted and actual satisfaction scores.

Mean Squared Error (MSE): Displays the average of squared errors.

R-squared (R²): Indicates how well the model fits the data. A higher R² value signifies a better model fit.

## 🛠 Requirements
Before running the app, ensure the following Python libraries are installed:

Python 3.7 or higher
Streamlit — To build and run the web app
pandas — Data handling
numpy — For numerical operations
matplotlib — For data visualization
seaborn — For statistical plots
scikit-learn — For machine learning models

## 🧠 How It Works
1. Data Loading & Preprocessing
The dataset, which contains historical customer feedback data, is loaded and preprocessed.
Unnecessary columns are removed.
Categorical features like Gender, Country, Feedback Score, and Loyalty Level are encoded into numeric values for model compatibility.
2. Model Training
The Random Forest Regressor model is trained on the cleaned dataset.
The dataset is split into training and testing sets to evaluate the model's performance.
3. Feature Importance Visualization
After training, the app generates a bar chart to visualize which features are most important in determining customer satisfaction.
4. User Input
The app provides a user-friendly sidebar form where users can input customer details.
5. Prediction
Once the user submits their input, the model predicts the Customer Satisfaction Score, which is displayed on the page.

## 🌱 Future Enhancements
Model Optimization: Implement hyperparameter tuning (e.g., using GridSearchCV or RandomizedSearchCV) to improve the model's predictive accuracy.
Advanced Models: Explore more sophisticated models such as Gradient Boosting or XGBoost for better performance.
Cloud Deployment: Host the app on cloud platforms like AWS, Heroku, or Streamlit Sharing for broader access.
