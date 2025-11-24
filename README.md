# 🌤️ Python Weather App

A lightweight, desktop-based weather application built with **Python**, **Tkinter**, and the **OpenWeatherMap API**. Instantly view current weather conditions, temperature, humidity, wind speed, and more for any city worldwide.

---

## 🚀 Features

- **Real-time Weather Data:**  
  Instant access to live weather updates from anywhere on the globe.

- **Search Any City:**  
  Simply type the city name and get up-to-date local weather information.

- **Detailed Weather Metrics:**  
  - **Temperature** (Current, Max, Min – in °C/°F)
  - **Weather Conditions** (Clear, Rain, Clouds, etc.)
  - **Pressure & Humidity**
  - **Wind Speed**
  - **Sunrise & Sunset Times** (local)

- **Clean & Responsive UI:**  
  Simple, modern interface built with Tkinter for an intuitive user experience.

---

## 🛠️ Technologies Used

- **Python 3.x**
- **Tkinter** (GUI framework)
- **Requests** (HTTP library for API calls)
- **OpenWeatherMap API** (weather data source)

---

## 📦 Installation

Follow these steps to set up and run the project locally:

1. **Clone the Repository**
   ```bash
   git clone https://github.com/your-username/weather-app-python.git
   cd weather-app-python
   ```

2. **Install Dependencies**
   The app requires the `requests` library. Install using pip:
   ```bash
   pip install requests
   ```
   > 📝 **Note:** Tkinter comes pre-installed with most Python distributions. If you encounter errors, install `python-tk` (or `tkinter`) according to your OS.

3. **Get an OpenWeatherMap API Key**  
   - Register for a free API key at [OpenWeatherMap](https://openweathermap.org/appid).
   - Replace `"YOUR_API_KEY_HERE"` in the code with your actual key.

4. **Run the Application**  
   ```bash
   python main.py
   ```
   > Replace `main.py` if your main file has a different name.

---

## 🔑 API Key Note

For demonstration, you might find a placeholder API key in the code. **Always use your own API key for production or personal use**.

Update your main Python file:
```python
api = "https://api.openweathermap.org/data/2.5/weather?q=" + city + "&appid=YOUR_API_KEY_HERE"
```
<img width="1425" height="965" alt="Screenshot 2025-11-24 204935" src="https://github.com/user-attachments/assets/660af28c-418d-4d75-9dc3-2ed3880ecb7d" />

---



<img width="754" height="665" alt="Screenshot 2025-11-24 204732" src="https://github.com/user-attachments/assets/4f6454cf-e20b-4a08-b2e1-bb1f0f9b1533" />


---

## 🤝 Contributing

Contributions are welcome! Here's how you can help:

1. **Fork the repository**
2. **Create a new branch:**  
   ```bash
   git checkout -b feature-branch
   ```
3. **Commit your changes**
4. **Push to your branch**
5. **Open a Pull Request**

---

## 📃 License

This project is [MIT licensed](LICENSE).

---MADE BY 
NAME - ANSHU KUMAR 
REG No. - 25BHI10040




VIT BHOPAL 
