# 🌦️ Weather Data Retrieval and Forecasting 🌧️
This Python script allows you to retrieve weather data for cities and their forecasts using the OpenWeatherMap API. It provides a user-friendly interface to input city names and displays the current weather conditions. Additionally, it allows you to save the collected data to an Excel file for further analysis or reference.

# Requirements 📋
- Python 3.x 🐍
- requests library: Install using pip install requests 📦
- pandas library: Install using pip install pandas 📈
# Setup and Usage 🚀
- Clone the repository and navigate to the project directory.

- Install the required libraries if you haven't already:
- pip install requests pandas
- Obtain an API key from the OpenWeatherMap website by signing up for a free account. 🔑

- Open the Python script Weather App.ipynb in your preferred code editor.

- Replace the api_key variable with your OpenWeatherMap API key.

- Run the script:
python weather_data.py

- The script will prompt you to enter the city names to retrieve weather data. It will display the current weather conditions for each city and give you the option to continue or exit. 🏙️

- If you want to know the forecasted conditions for a specific city, choose "Yes" when prompted. The script will display the forecast data for the given city.

- After collecting the weather data, the script will save it to an Excel file named Weatherdata.xlsx in the project directory. 💾

# Additional Notes ℹ️
- The script handles input validation and will prompt for valid city names if an invalid city name is entered.

- The number of forecast data points (currently set to 5) can be adjusted by changing the cnt parameter in the forecast API call.

- The script creates a MultiIndex in the Excel file to categorize the data by "Temperature," "Humidity," "Windspeed," and "Weather Condition" for easy reference.

# Credits 💡
The script uses the OpenWeatherMap API (https://openweathermap.org/) to retrieve weather data.

Developed by Ali Khan 🧑‍💻

# Acknowledgments
This project was completed as part of my internship program, showcasing my skills and learning progress.


