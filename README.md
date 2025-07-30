# 🌿 Plant Disease Detection Web App

A web-based application that predicts plant diseases using a machine learning model and provides users with information about the disease and possible remedies. Built using Django (Python backend) and a pre-trained machine learning model.

## 🚀 Features

- 🌱 Upload leaf images to detect plant diseases
- 🧠 Backend powered by ML for image classification
- 🌐 Django-based server with session handling
- 📍 Geo-location support (using GeoLite2 database)

## 🛠️ Tech Stack

- **Frontend**: HTML, CSS, JavaScript
- **Backend**: Python, Django
- **ML Framework**: TensorFlow / Keras (model pre-trained and saved)
- **Database**: Default Django SQLite
- **Geo-Location**: MaxMind GeoLite2

## 📁 Project Structure

PlantDisease/
├── manage.py
├── run.bat
├── messages.txt
├── session.txt
├── GeoLite2-City.mmdb
├── PlantDisease/ # Django project settings
├── PlantDiseaseApp/ # Main Django app with views and ML logic
├── model/ # Contains pre-trained ML model files
└── .git/ # Git version control (hidden)

## ⚙️ Setup Instructions

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/PlantDisease.git
   cd PlantDisease
2.**Create virtual environment & activate**

bash
Copy
Edit
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

3.**Install dependencies**

bash
Copy
Edit
pip install -r requirements.txt

4.**Run migrations**

bash
Copy
Edit
python manage.py migrate


5.**Start the server**

bash
Copy
Edit
python manage.py runserver
