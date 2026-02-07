# 🚗 Vehicle Price Prediction Dashboard

[![Streamlit App](https://static.streamlit.io/badges/streamlit_badge_svg.svg)](https://share.streamlit.io/)
[![Python 3.9+](https://img.shields.io/badge/python-3.9+-blue.svg)](https://www.python.org/downloads/)

A comprehensive Machine Learning project that predicts vehicle prices using a Linear Regression model. This repository contains the full pipeline, from data exploration and cleaning in Jupyter Notebooks to a production-ready web interface built with Streamlit.

---

## 📖 Project Overview
This project aims to simplify car valuation by analyzing technical and brand specifications. By training on a dataset of high-performance and consumer vehicles, the model identifies key price drivers like Horsepower, Torque, and Brand prestige to provide accurate real-time estimates.

## ✨ Key Features
* **Interactive Sidebar:** User-friendly inputs for horsepower, torque, and vehicle categories.
* **Feature Importance Chart:** Dynamic visualization showing which specs influence price the most.
* **Full Data Pipeline:** Includes the original research notebook showing data cleaning and model training.
* **Visual Documentation:** Built-in diagrams explaining the ML process and data cleaning steps.

## 📁 Project Structure
```text
├── app.py                     # Main Streamlit application (previously Regr_model_cars.py)
├── Car Price Prediction.ipynb  # Jupyter Notebook with EDA and Model Training
├── car_data.xlsx              # Raw/Processed dataset
├── linear_model.pkl           # Saved Linear Regression model
├── feature_importance.xlsx    # Exported importance scores for the dashboard
├── ml_process.png             # Visual diagram of the Machine Learning workflow
├── Data Cleaning.png          # Visual summary of data preprocessing steps
├── pic 1.PNG / pic 2.PNG      # UI/UX branding images
└── requirements.txt           # Project dependencies
