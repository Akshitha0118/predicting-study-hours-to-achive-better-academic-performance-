# 📘 Predicting Study Hours to Achieve Better Academic Performance

An end-to-end Machine Learning regression project that predicts academic performance (marks/percentage) based on the number of study hours.
The model is deployed as a Flask web application, enabling real-time, data-driven predictions to help students plan their study time effectively.

## 🔍 Problem Statement

Many students face a common question:

❓ “How many hours should I actually study to perform well academically?”

Some students overstudy, leading to burnout 😓

Others understudy due to lack of clear guidance

Most academic advice is generic and not data-driven

As a result, students struggle to balance effort and performance.

## ✅ Solution

To address this problem, a Machine Learning–based predictive system was developed that estimates academic performance based on study hours.

The solution uses a supervised regression model and is deployed through a Flask web application for real-time predictions.

The application includes:

✔ Input validation (0–24 study hours)

✔ Output constraints to ensure predicted marks do not exceed 100%

✔ Simple and intuitive user interface

## This system helps students:

🎯 Set realistic study goals

🔥 Avoid burnout and overstudying

📊 Understand the relationship between study time and performance

🧠 Make informed academic decisions

## 🧠 Machine Learning Approach

Problem Type: Regression

Learning Type: Supervised Learning

Input Feature: Study Hours

Target Variable: Academic Performance (Marks / Percentage)

Model Serialization: Joblib

## 🛠️ Tech Stack

🐍 Python

📊 Pandas

🔢 NumPy

🤖 Scikit-learn

🌐 Flask

📦 Joblib

## ✨ Key Features

Real-time academic performance prediction

Regression-based Machine Learning model

Flask web app for model deployment

Input validation (0–24 hours)

Output limits to ensure realistic predictions

Lightweight, fast, and beginner-friendly


## ⚙️ How It Works

User enters the number of study hours.

Input is validated to ensure it lies between 0 and 24.

The trained regression model processes the input.

Predicted academic performance is generated.

Output is displayed on the web interface.

## ▶️ Usage
Run the application locally:
python app.py

### Steps:

Open the Flask app in your browser

Enter study hours

Click Predict

View predicted academic performance

## 📊 Output

Displays predicted marks / percentage

Ensures predictions do not exceed 100%

Provides instant feedback for better planning

## 📘 Key Learnings

✔ End-to-end Machine Learning workflow
✔ Supervised regression modeling
✔ Model serialization using Joblib
✔ Deploying ML models with Flask
✔ Building practical, user-focused ML applications

## 🔮 Future Improvements

Add multiple regression models for comparison

Visualize study hours vs performance graph

Include confidence intervals for predictions

Deploy the app on cloud platforms (Render / Heroku)

Improve UI with advanced styling

