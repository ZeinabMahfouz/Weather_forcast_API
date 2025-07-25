
Weather Forecast CLI
A simple Python command-line application that fetches and displays current weather and a 3-day forecast for any city using the WeatherAPI.

Features
Displays current temperature, weather condition, humidity, and local time for a city

Shows a 3-day weather forecast including max/min temperatures and chance of rain

Interactive CLI that asks if you want to check weather for another city or exit

Handles invalid city inputs gracefully

Exit anytime by typing exit

Prerequisites
Python 3.x installed on your system

requests library installed (pip install requests)

A free API key from WeatherAPI

Setup & Usage
Clone the repository:

bash
Copy
Edit
git clone https://github.com/yourusername/weather-forecast-cli.git
cd weather-forecast-cli
Install dependencies:

bash
Copy
Edit
pip install requests
Open the Python script and replace the API_KEY variable with your own WeatherAPI key:

python
Copy
Edit
API_KEY = 'your_actual_api_key_here'
Run the script:

bash
Copy
Edit
python weather_forecast.py
Follow on-screen prompts to enter a city name or type exit to quit.

Example Output
yaml
Copy
Edit
Enter a city name (or type 'exit' to quit): London

Weather in London, United Kingdom
Local Time: 2025-07-25 15:00
Current Temp: 22 °C
Condition: Partly cloudy
Humidity: 60%

3-Day Forecast:
  2025-07-25
     Max: 24 °C | Min: 16 °C
     Chance of Rain: 10%
  2025-07-26
     Max: 26 °C | Min: 17 °C
     Chance of Rain: 5%
  2025-07-27
     Max: 25 °C | Min: 18 °C
     Chance of Rain: 20%

Do you want to check another city? (yes/no): no
Goodbye!
