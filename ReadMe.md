# Django Weather App

A lightweight Django web application that fetches real-time weather details for any city using the OpenWeatherMap API and tracks recent search history using Django models.

## Features
- Real-time weather data (Temperature, Humidity, Pressure, and Conditions)
- Weather condition icons powered by OpenWeatherMap
- Search history tracking (displays the last 5 searched cities)
- Built-in error handling for invalid cities and network issues

## Tech Stack
- **Backend:** Python, Django
- **API:** OpenWeatherMap API
- **Database:** SQLite (Default Django ORM)
- **Frontend:** HTML5, CSS3

## Installation & Setup

1. **Clone the repository:**
   ```bash
   git clone (https://github.com/Athena2805/Weather_Project.git)
   cd weatherproject/weather

   python -m venv venv
   source venv/bin/activate  # On Windows use: venv\Scripts\activate
   pip install django requests
   python manage.py makemigrations
   python manage.py migrate
   python manage.py runserver
