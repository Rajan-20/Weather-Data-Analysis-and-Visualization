# Weather Data Analysis and Visualization 

**OVERVIEW**

This project is fully functional console based application developed in Python. It collects the weather information like current temperature, max and min temperature,pressure,humidity,wind speed and weather description using OpenWeatherMap API.Finally,forecast the weather data using Matplotlib and Seaborn libraries. This project works based on the two ways, one is getting the current weather data enter the geo coordinates like latitude and longitutde and other one is getting weather based on the city name.

**LIBRARIES USED**

      * Requests - handle the API requests
      * datetime - it formats the datetime in the response data
      * matplotlib - visualize the weather data
      * seaborn - gives attractiveness to the visualization
 
**API USED**

  *  URL  - https://api.openweathermap.org/data/2.5/weather?q={city_name}&appid={API_key} (based on city name)
  *  URL  - https://api.openweathermap.org/data/2.5/weather?lat={lat}&lon={lon}&appid={API_key}  (based on geo coordinates)
  *  URL  -  https://api.openweathermap.org/data/2.5/forecast?q={city_name}&appid={API_Key}  (provides weather data 3 hr once in a day for 5 days)

**FEATURES OF WEATHER FORECAST**

  * 3 hour once in day the weather data updated.
  * The API gives forecase data for next 5 days.
  * change weather in every 3 hours as according to weather changes
  * provide accurate data information about weather.
  * user can search weather anytime and anywhere

**WORKFLOW**

  * It will take the input from the user for getting the weather data based on city name or Geo coordinates.
  * Next, suppose user enter the first option it will ask latitude and longitude of the city or user enter the second option it will ask city name for API request.
  * Based on the user preference it will give description,current temperature,humidity and Wind Speed etc.,
  * Finally Automatically it gives the rain volume,temperature,humidity data for visualization.
