# 🌿 Air Quality Prediction

This project is an **Air Quality Prediction** application built with **Machine Learning** and **Django**. It uses a **Random Forest** model to predict air quality based on various environmental factors.

---

## 🌟 Project Overview
Air quality is a crucial aspect of public health, and **predicting air quality** in real-time can help mitigate health risks. This web application allows users to input environmental data and receive a **prediction** of the air quality index (AQI), helping raise awareness and promote cleaner environments.

---

## 🎯 Features
- 🔍 **Machine Learning Model**: Utilizes **Random Forest** for accurate air quality prediction.
- 🌐 **Web Interface**: Provides a user-friendly, interactive interface built with **Django**.
- 🌡️ **Real-time Data**: Predicts air quality based on real-time environmental data inputs.
- 📊 **Data Visualizations**: Displays air quality trends and predictions using beautiful charts.

---

## 🛠 Technology Stack
- **Backend**: Django
- **Frontend**: HTML, CSS, JavaScript
- **Machine Learning**: Random Forest, scikit-learn
- **Database**: SQLite

---

## 📂 Dataset
The model leverages a dataset (`data.csv`) used for training and evaluation of the air quality prediction model. 

**Note**: The dataset file is approximately **59.64 MB**. It is recommended to use **Git Large File Storage (Git LFS)** for handling large files.

---

## 🚀 Getting Started

### Prerequisites
Ensure you have **Python** installed on your system.

1. Clone the repository:
   
   ```bash
   git clone https://github.com/kholivox/Air_Quality.git
   cd Air_Quality

4. ```bash
   pip install -r requirements.txt

5. ```bash
   python manage.py migrate

6. ```bash
   python manage.py runserver

---   


## 🌐 Access the Application
### Open a web browser and go to: http://127.0.0.1:8000/
### Enter patient data to receive a prediction of heart disease risk.


---

## 🧩 Project Structure
### Backend: Contains machine learning models and Django views.
### Frontend: Templates for the user interface with HTML, CSS, and Django templating.
### Static Files: CSS and JavaScript files for styling and interactivity.

---

## ⚙️ How to Run the Code
   To run the application, follow these steps:

### 1.Install the Requirements: Run pip install -r requirements.txt to install all dependencies.
### 2.Run the Server: Start the server using python manage.py runserver.
### 3.Access the Application: Open http://127.0.0.1:8000/ in your browser.
