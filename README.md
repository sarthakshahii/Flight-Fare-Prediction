✈️ Flight Fare Prediction
📌 About The Project

The Flight Fare Prediction App is a machine learning-based web application that predicts airline ticket prices based on various travel parameters. The goal of this project is to help users estimate flight fares in advance so they can plan their travel more efficiently.

The model is trained on historical flight data and uses machine learning algorithms to analyze factors such as:

Airline

Source and Destination

Date of Journey

Total Stops

Departure Time

Arrival Time

Duration

Users can enter these details through a web interface, and the application predicts the expected flight price instantly.

This project demonstrates the end-to-end machine learning pipeline, including data preprocessing, model training, experiment tracking, and deployment.

🚀 Tech Stack
Machine Learning

Pandas

NumPy

Scikit-learn

Matplotlib

Seaborn

Backend

Flask

MLOps Tools

MLflow (experiment tracking)

DVC (data versioning)

Deployment & Containerization

Docker

📂 Project Structure
Flight-Fare-Prediction
│
├── Notebook_Experiments       # Data analysis and model experimentation
├── src                        # Source code for ML pipeline
├── static                     # CSS / frontend assets
├── templates                  # HTML templates
├── artifacts                  # Trained model artifacts
├── app.py                     # Flask application
├── requirements.txt          # Project dependencies
├── Dockerfile                # Docker configuration
└── README.md
⚙️ Installation & Setup
1️⃣ Clone the Repository
git clone https://github.com/sarthakshahii/Flight-Fare-Prediction.git
cd Flight-Fare-Prediction
2️⃣ Create Virtual Environment
conda create -n flightfare python=3.9 -y
conda activate flightfare
3️⃣ Install Dependencies
pip install -r requirements.txt
4️⃣ Run the Application
python app.py
🌐 Access the Application

After running the app, open your browser and go to:

http://localhost:5000

Enter the flight details to get a predicted fare.

🐳 Run Using Docker
Pull Image
docker pull sarthakshahi/flight-fare-prediction
Run Container
docker run -p 5000:5000 sarthakshahi/flight-fare-prediction
📊 Features

✔ Flight fare prediction using machine learning
✔ Clean web interface using Flask
✔ ML experiment tracking with MLflow
✔ Data versioning using DVC
✔ Dockerized application for easy deployment
