# 🌦️ Weather Forecasting Agent using Pydantic AI

This project is a conversational weather assistant built using Python, Pydantic AI, and the OpenWeatherMap API. It lets users interact naturally to get real-time weather information for any city in the world.

> 🧠 Ask it: “What’s the weather in Hyderabad?”
> ✅ It replies with: “The current temperature in Hyderabad is 30°C with clear sky. Humidity is 65%.”



## 📌 Features

- ✅ Real-time weather data using OpenWeatherMap API
- 🧠 AI agent powered by [Pydantic AI](https://github.com/pydantic/pydantic-ai)
- 🌐 Supports any global city
- 📝 Structured outputs using `Pydantic` models
- ⚙️ Runs entirely in [Google Colab](https://colab.research.google.com/) – no setup or deployment needed

---

## 🚀 Technologies Used

- Python 3 (Colab)
- Pydantic AI (with `groq:llama3-8b-8192`)
- OpenWeatherMap API
- `requests` library
- `RunContext` and `@tool` for tool integration

---

## 📥 How to Use

1. Clone or open the notebook in Colab.
2. Install the required packages:
    ```python
    !pip install pydantic-ai requests nest_asyncio
    ```
3. Get your **OpenWeatherMap API key** from [https://openweathermap.org/api](https://openweathermap.org/api)
4. Get your **GROQ API key** from [https://console.groq.com](https://console.groq.com)
5. Replace the placeholder keys in the notebook:
    ```python
    os.environ["GROQ_API_KEY"] = "your_groq_api_key"
    API_KEY = "your_openweathermap_api_key"
    ```
6. Ask any weather-related question and get instant feedback!

---



