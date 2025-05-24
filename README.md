# REST-API-CLIENT

*COMPANY*: CODTECH IT SOLUTIONS

*NAME*: CHALAKACHARLA CHANDU

*INTERN ID*: CT06DL1134

*DOMAIN*: FILE HANDLING UTILITY

*DURATION*: 6 WEEKS

*MENTOR*: NEELA SANTOSH

*DESCRIPTION*:

## 🌦️ WeatherDataApp – Java Console Application Using WeatherAPI

**WeatherDataApp** is a simple yet powerful Java console application that fetches and displays real-time weather information for any city around the world using the [WeatherAPI](https://www.weatherapi.com/). Built using core Java and the Gson library, this application demonstrates how to make HTTP requests, parse JSON responses, and handle user input — all within a clean and easy-to-understand structure. It's a great starting point for Java developers interested in API integration, JSON parsing, or building lightweight CLI tools.

---

### 🔧 Features

* 🌍 **City-Based Weather Fetching**: Enter any city name to get up-to-date weather information.
* 📦 **API Integration**: Uses WeatherAPI for reliable and detailed weather data.
* 🧾 **JSON Parsing**: Parses and displays temperature, humidity, wind speed, and weather condition.
* 👤 **Command-Line Interface**: Clean, interactive console experience.
* 🛠️ **Error Handling**: Basic validation for invalid city inputs and API response errors.
* 💡 **Modular Design**: Organized code structure for easy extension and maintenance.

---

### 🚀 How It Works

1. The user is prompted to input a city name.
2. The application constructs a request URL using the provided city and a valid API key from WeatherAPI.
3. It makes a `GET` request to the WeatherAPI endpoint and retrieves a JSON response.
4. The JSON is parsed using the Gson library to extract relevant weather details.
5. The parsed data is displayed in a user-friendly format.

---

### 🧰 Tech Stack

* **Java SE**
* **Gson** (Google's JSON Parsing Library)
* **WeatherAPI** (for weather data)
* **HttpURLConnection**
* **URI/URL for safe HTTP handling**

### ⚙️ Setup Instructions

1. **Clone the Repository**

   ```
   git clone https://github.com/your-username/WeatherDataApp.git
   ```

2. **Add Your WeatherAPI Key**
   Replace the placeholder API key in the source code with your own from [https://www.weatherapi.com](https://www.weatherapi.com).

3. **Compile & Run**

   ```
   javac WeatherDataApp.java
   java WeatherDataApp
   ```

4. **Enter any city name** when prompted to get current weather data.

---

### 📌 Notes

* Make sure you have Java installed (JDK 8+ recommended).
* This is a console application — GUI support is not included in this version.
* API key must be valid to avoid request failure.
* Network connectivity is required to make API calls.

---

### 📈 Future Improvements

* GUI version using JavaFX or Swing.
* Integration with multiple APIs for comparison.
* Caching and offline support.
* Unit testing and error logging improvements.
* Docker support for easier deployment.

---

### 🤝 Contributions

Contributions are welcome! Feel free to fork the repo, submit pull requests, or suggest enhancements via issues.

---

### 📜 License

This project is licensed under the MIT License – see the [LICENSE](LICENSE) file for details.
