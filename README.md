# cloud-functions-flights-weather
This repository contains three Jupyter Notebooks related to the collection and processing of flight and weather data.
The goal of the project was to fetch, clean, and organize flight and weather information for further analysis or storage in a database (originally hosted on Google Cloud).

⚠️ Note:
The original Google Cloud project, database, and server have been deleted. Therefore, live connections to the database are no longer available. The notebooks are provided for educational and documentation purposes only.

📁 Contents
Flights.ipynb
Script for collecting and processing flight schedules and related data.

Flights_data.ipynb
Additional data extraction and preparation for flight records.

collecting of weather data.ipynb
Script for fetching weather forecast data using OpenWeather API and preparing it for database insertion.

📦 Requirements
Python 3.9+

pandas

requests

sqlalchemy

pymysql

pytz

functions-framework

Flask (for local function testing)

You can install all required libraries by running:

bash
Copy
Edit
pip install -r requirements.txt
(Please create a requirements.txt file if needed.)

🚀 How to Use
Clone the repository:

bash
Copy
Edit
git clone https://github.com/Afsaneh-esm/cloud-functions-flights-weather.git
Open the Jupyter Notebooks locally.

Run each cell step-by-step.

Note that some cells (such as database connection parts) may require adjustments if a new database is available.

📚 Notes
The database schema included two main tables: Static_cities (for city info) and Weather (for weather forecasts).

API keys (like OpenWeather API) should be added manually where necessary.

Database credentials have been removed or anonymized for security.
