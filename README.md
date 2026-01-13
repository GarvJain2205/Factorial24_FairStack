**🏨 Hotel Booking Analysis & Inventory Forecasting Dashboard**

📌 Project Overview

This project is a data-driven web dashboard that analyzes hotel booking data and uses machine learning and time-series forecasting to predict:

Future hotel occupancy

Future revenue

Cancellation risk

The system treats hotel rooms and nights as perishable inventory and helps hotels reduce:

Empty rooms (overstock)

Overbooking (stockout)

Revenue loss due to cancellations

🎯 Problem Statement

Hotels face challenges in:

Predicting future demand

Managing room inventory

Reducing cancellations

Maximizing revenue

This project solves these problems using historical hotel booking data and predictive models.

🛠️ Technologies Used

Python

Streamlit (Web Dashboard)

Prophet (Demand Forecasting)

ARIMA (Revenue Forecasting)

Random Forest (Cancellation Prediction)

Pandas, NumPy (Data Processing)

Matplotlib, Seaborn (Visualization)

Ngrok (Public Link for Demo)

📊 Features
1️⃣ Occupancy Forecast

Predicts future daily bookings

Uses Prophet model

Shows forecast graph and key insights

Helps plan room availability

2️⃣ Revenue Forecast

Predicts future revenue

Uses ARIMA model

Shows revenue trend with confidence range

Helps in financial planning

3️⃣ Cancellation Analysis

Predicts probability of booking cancellation

Uses Random Forest model

Identifies high-risk bookings

Helps reduce revenue loss

🏨 Inventory Concept in Hotels

In this project:

Each room = 1 inventory unit

Each night = perishable inventory

Unsold room = wasted inventory

So hotel demand forecasting is treated as inventory planning.

🚀 How to Run
Option 1: Google Colab

Upload hotel_bookings.csv

Run the notebook

Streamlit will start using ngrok

Open the generated link

Option 2: Local System
pip install streamlit prophet statsmodels scikit-learn seaborn pyngrok
streamlit run app.py

📁 Dataset

File: hotel_bookings.csv

Source: Public hotel booking dataset

Contains booking details, dates, guests, price, cancellation status

📈 Results

This dashboard helps hotels:

Forecast demand accurately

Plan room inventory

Reduce cancellations

Increase revenue

Improve customer satisfaction

💡 Use Cases

Hotel managers

Revenue management teams

Operations planning

Data analytics learning projects

Hackathons and academic projects
