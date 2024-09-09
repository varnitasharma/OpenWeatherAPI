This API project utilizes the free tier of OpenWeatherMap's API. It prompts the user to enter a city name, retrieves relevant weather data from the API, and then presents the current weather conditions and temperature in a user-friendly format.

This project demonstrates the ability to leverage external APIs to enrich applications. 

The retrieved JSON response can be further parsed to extract and display additional weather information such as wind speed, humidity, or forecast data, depending on the desired functionality.

JSON data looks like this:
  {'base': 'stations',
 'clouds': {},
 'cod': ,
 'coord': {'lat': , 'lon': },
 'dt': ,
 'id': ,
 'main': {'feels_like': ,
          'grnd_level': ,
          'humidity': ,
          'pressure': ,
          'sea_level': ,
          'temp': ,
          'temp_max': ,
          'temp_min': },
 'name': ,
 'sys': {'country': ,
         'id': ,
         'sunrise': ,
         'sunset': ,
         'type': },
 'timezone': ,
 'visibility': ,
 'weather': [{'description': , 'icon': , 'id': , 'main': }],
 'wind': {'deg': , 'speed': }}
