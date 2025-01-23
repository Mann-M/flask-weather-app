# Weather Forecast App

This is my first project using Flask, a lightweight web framework for Python. The **Weather Forecast App** allows users to get real-time weather updates for any city using the OpenWeatherMap API. The app has been deployed on Render and is accessible at:

🔗 [Live Demo](https://flask-weather-app-u6ji.onrender.com)

---

## Features

- Search for the current weather by entering a city name.
- Displays:
  - Temperature (in Fahrenheit by default).
  - Weather status (e.g., sunny, cloudy, etc.).
  - Feels-like temperature.
  - Humidity
- Responsive user interface using HTML and CSS.
- Backend powered by Flask and integrated with OpenWeatherMap API.

---

## Technology Stack

- **Frontend**:
  - HTML5
  - CSS3

- **Backend**:
  - Python (Flask)

- **API**:
  - [OpenWeatherMap API](https://openweathermap.org/api)

- **Deployment**:
  - Render (https://render.com)

---

## Setup and Installation

To run this project locally, follow these steps:

1. **Clone the Repository:**
   ```bash
   git clone <repository-url>
   cd flask-weather-app
   ```

2. **Create and Activate a Virtual Environment:**
   ```bash
   python -m venv venv
   source venv/bin/activate   # For Linux/Mac
   venv\Scripts\activate    # For Windows
   ```

3. **Install Dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

4. **Set Up the Environment Variables:**
   - Create a `.env` file in the root directory.
   - Add your OpenWeatherMap API key:
     ```
     API_KEY=your_openweathermap_api_key
     ```

5. **Run the Application:**
   ```bash
   python server.py
   ```
   The app will be available at `http://127.0.0.1:5000`.

---

## File Structure

```plaintext
.
├── server.py             # Main Flask application
├── weather.py            # Module for fetching weather data from OpenWeatherMap
├── templates/            # HTML templates
│   ├── index.html        # Landing page
│   ├── weather.html      # Weather display page
│   └── cityNotFound.html # Error handling page for invalid city names
├── static/               # Static files (CSS, JS, images)
│   └── styles/
│       └── style.css     # Custom CSS styling
├── .env                  # Environment variables file (not included in repo)
├── requirements.txt      # Python dependencies
└── README.md             # Project documentation
```

---

## Deployment on Render

The app is deployed on [Render](https://render.com), a platform for deploying web applications. Visit the live app here:

🔗 [https://flask-weather-app-u6ji.onrender.com](https://flask-weather-app-u6ji.onrender.com)

---

## Future Improvements

- Add support for multiple units (Celsius/Kelvin).
- Enhance UI/UX for better user experience.
- Add weather forecasts for the next few days.
- Implement error handling for invalid city names.

---

## Acknowledgements

- [Flask Documentation](https://flask.palletsprojects.com/)
- [OpenWeatherMap API](https://openweathermap.org/api)

---

## License

This project is licensed under the MIT License. Feel free to use and modify the code for your own projects.
