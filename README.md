# Django Weather System 🌦️

## Overview 📌
The **Django Weather System** is a web application that allows users to check the current weather conditions for any city worldwide. It fetches real-time weather data using an external API and displays it in an easy-to-read format.

## Features ✨
- 🌍 Search weather by city name
- 📊 Display temperature, humidity, wind speed, and weather description
- 🎨 User-friendly UI built with Django templates
- 🔄 Live API integration for real-time weather updates
- 🛠️ Built with Django, Python, and Bootstrap

## Technologies Used 🛠️
- **Backend:** Django (Python)
- **Frontend:** HTML, CSS, Bootstrap
- **API:** OpenWeatherMap API
- **Database:** SQLite (default Django DB)

## Installation & Setup ⚙️
Follow these steps to set up the project on your local machine:

### 1️⃣ Clone the Repository
```sh
 git clone https://github.com/SnehaKamble04/Djnago_Weather_Syatem.git
 cd Djnago_Weather_Syatem
```

### 2️⃣ Create & Activate Virtual Environment
```sh
python -m venv venv
# Activate virtual environment
# Windows:
venv\Scripts\activate
# macOS/Linux:
source venv/bin/activate
```

### 3️⃣ Install Dependencies
```sh
pip install -r requirements.txt
```

### 4️⃣ Configure API Key
- Sign up on [OpenWeatherMap](https://openweathermap.org/)
- Get your **API key**
- Create a `.env` file in the project directory and add:
  ```plaintext
  WEATHER_API_KEY=your_api_key_here
  ```

### 5️⃣ Run Migrations
```sh
python manage.py makemigrations
python manage.py migrate
```

### 6️⃣ Start the Development Server
```sh
python manage.py runserver
```
- Open **http://127.0.0.1:8000/** in your browser.

## Contributing 🤝
Contributions are welcome! Feel free to fork the repo and submit pull requests.

## License 📜
This project is licensed under the MIT License.

---
Made with ❤️ by [Sneha K. Kamble](https://github.com/SnehaKamble04) 🚀

