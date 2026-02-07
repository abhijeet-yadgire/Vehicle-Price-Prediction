# 🚗 Vehicle Price Prediction Dashboard

[![Streamlit App](https://static.streamlit.io/badges/streamlit_badge_svg.svg)](https://share.streamlit.io/)
[![Python 3.8+](https://img.shields.io/badge/python-3.8+-blue.svg)](https://www.python.org/downloads/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

An end-to-end Machine Learning web application that predicts vehicle prices using a Linear Regression model. This app features a dynamic sidebar for user input and interactive Plotly visualizations to explain feature importance.

---

## 📖 Project Overview
Determining the fair market value of a vehicle is a complex task involving various mechanical and brand-related factors. This project implements a **Linear Regression** model trained on high-performance vehicle data to provide instant price estimations based on user-defined specifications.

## ✨ Key Features
* **Interactive Side Panels:** Adjust Horsepower, Torque, and Body Specs in real-time.
* **Feature Importance Visualization:** A Plotly-powered bar chart showing which attributes (e.g., Horsepower vs. Brand) weigh most heavily on the price.
* **Smart Encoding:** Processes complex categorical data like Engine Aspiration and Drivetrain types.
* **Responsive UI:** A clean, dual-column layout optimized for wide screens.

## 🛠️ Tech Stack
* **Language:** Python
* **Framework:** [Streamlit](https://streamlit.io/)
* **Data Science:** Pandas, NumPy, Scikit-Learn
* **Visualization:** Plotly Express
* **Serialization:** Pickle (for model loading)

## 📁 Project Structure
```text
├── Regr_model_cars.py       # Main Streamlit application script
├── linear_model.pkl         # Pre-trained Linear Regression model
├── feature_importance.xlsx  # Calculated importance scores for the chart
├── pic 1.PNG                # Sidebar branding image
├── pic 2.PNG                # Header banner image
└── requirements.txt         # List of dependencies
