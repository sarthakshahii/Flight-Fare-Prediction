# ✈️ Flight Fare Prediction

## 📌 About The Project

The **Flight Fare Prediction App** is a machine learning-based web application that predicts airline ticket prices based on various travel parameters. The goal of this project is to help users estimate flight fares in advance so they can plan their travel more efficiently.

The model is trained on historical flight data and uses machine learning algorithms to analyze factors such as:

- Airline  
- Source and Destination  
- Date of Journey  
- Total Stops  
- Departure Time  
- Arrival Time  
- Duration  

Users can enter these details through a **web interface**, and the application predicts the expected flight price instantly.

This project demonstrates the **end-to-end machine learning pipeline**, including:

- Data preprocessing  
- Model training  
- Experiment tracking  
- Model deployment  

---

# 🚀 Tech Stack

## Machine Learning
- Pandas  
- NumPy  
- Scikit-learn  
- Matplotlib  
- Seaborn  

## Backend
- Flask  

## MLOps Tools
- MLflow (Experiment Tracking)  
- DVC (Data Versioning)  

## Deployment & Containerization
- Docker  

---

# 📂 Project Structure
Flight-Fare-Prediction
│
├── Notebook_Experiments # Data analysis and model experimentation
├── src # Source code for ML pipeline
├── static # CSS / frontend assets
├── templates # HTML templates
├── artifacts # Trained model artifacts
├── app.py # Flask application
├── requirements.txt # Project dependencies
├── Dockerfile # Docker configuration
└── README.md

---

## 📊 Features

- ✅ Flight fare prediction using Machine Learning
- ✅ Clean web interface built with Flask
- ✅ ML experiment tracking using MLflow
- ✅ Data versioning using DVC
- ✅ Dockerized application for easy deployment

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/sarthakshahii/Flight-Fare-Prediction.git
cd Flight-Fare-Prediction
```

### 2️⃣ Create Virtual Environment
```bash
conda create -n flightfare python=3.9 -y
conda activate flightfare
```

### 3️⃣ Install Dependencies
```bash
pip install -r requirements.txt
```

### 4️⃣ Run the Application
```bash
python app.py
```

### 🌐 Access the Application

After running the application, open your browser and navigate to:
```
http://localhost:5000
```

Enter the flight details to get the predicted fare.

---

## 🐳 Run Using Docker

### Pull Docker Image
```bash
docker pull sarthakshahi/flight-fare-prediction
```

### Run Docker Container
```bash
docker run -p 5000:5000 sarthakshahi/flight-fare-prediction
```

Then open `http://localhost:5000` in your browser.
