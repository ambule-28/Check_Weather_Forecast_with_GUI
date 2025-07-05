
# 🌤️ Check Weather Forecast with GUI

This project is a **Python-based GUI application** that fetches and displays the current weather information for a given city using the **OpenWeatherMap API**. The application is built using **Tkinter** for the graphical interface and uses the `requests` and `Pillow` libraries to handle API communication and display weather icons.

---

## 📌 Features

- Simple and intuitive **Graphical User Interface** (GUI)
- Fetches **real-time weather data** from OpenWeatherMap
- Displays:
  - City name
  - Weather conditions (like clear, cloudy, rain)
  - Temperature in Celsius
  - Weather icons
- Error handling for invalid or empty city names

---

## 🚀 Technologies Used

- **Python 3**
- **Tkinter** - for GUI
- **OpenWeatherMap API** - for live weather data
- **Requests** - for sending HTTP requests
- **Pillow (PIL)** - for image processing (weather icons)

---

## 🧾 Requirements

Before running the application, ensure you have the following installed:

```bash
pip install requests pillow
```

---

## 🛠️ How to Run

1. Clone the repository or download the `.ipynb` file.
2. Open the `Check_Weather_Forecast_with_GUI.ipynb` file using **Jupyter Notebook** or **VS Code with Jupyter extension**.
3. Replace the placeholder in the code with your **OpenWeatherMap API key**:

   ```python
   api_key = "your_api_key_here"
   ```

4. Run all the cells to start the GUI.
5. Enter a city name and click **"Get Weather"** to see the results.



---

## 🌐 API Used

This project uses the **[OpenWeatherMap Current Weather Data API](https://openweathermap.org/current)**. You can get a free API key by signing up at [https://openweathermap.org/](https://openweathermap.org/).

---

## 🧠 Concepts Practiced

- API Integration
- GUI design using Tkinter
- Error and exception handling
- Image rendering using PIL
- Real-time data processing

---

## ✅ Example Output

```
City: Mumbai
Conditions: light rain
Temperature (°C): 28.5
```

---

## 📄 License

This project is open-source and free to use under the MIT License.
