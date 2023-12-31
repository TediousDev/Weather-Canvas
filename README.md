# Weather Canvas: A Weather Visualization Tool

Weather Canvas is a Streamlit web application that allows you to visualize weather data for up to 10 cities using the OpenWeather API. 

## Features

- Enter the name of any city in the world, and the app will fetch and display the current temperature, humidity, and wind speed for that city.
- The app will visualize the selected weather factor for the entered cities on a bar plot.
- The weather data for each city is stored in a session and displayed in a table on the app.
- The app prevents you from entering more than 10 cities and notifies you when you try to fetch weather data for a city that's already in the table.
- You can reset the table and the plot at any time using the "Reset" button.


## Getting Started

To get started with this project, clone this repository and install the requirements.

1. Clone the repository:
```
git clone https://github.com/TediousDev/Weather-Canvas.git
```

2. Change to the project directory:
```
cd climate-canvas
```

3. Install the required packages:
```
pip install -r requirements.txt
```

4. You need to set your OpenWeather API key, Get your own API key from here: [OpenWeather](https://home.openweathermap.org/api_keys). Replace st.secrets[API_KEY] with your API key.
```
api_key = "YOUR_API_KEY"
```

5. Run the app:
```
streamlit run app.py
```

6. The app is now accessible at http://localhost:8501.
