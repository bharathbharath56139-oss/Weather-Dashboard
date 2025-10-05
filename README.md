Weather Dashboard (Server-Side APIs)

Table of Contents
Description
Key Features
Usage
Links
Screenshots
Description:
A weather dashboard that allows the user to get a city's current weather conditions and the five day forecast. Third-party APIs are used to access weather data by making requests with specific parameters to a URL. This was a homework assignment for the University of Toronto SCS Coding Boot Camp and no starter code was provided.

Key Features:
Two different OpenWeather APIs are used to retrieved the required weather data
localStorage is used to save seach history and if any past search history is in local storage it is displayed when the site first loads
User can either enter a city to search for or click on a button for a previously searched city to get the current weather and five day forecast
jQuery event listeners are used to identify when a user wishes to search for a city (including past city) or clear search history
New elements were created using jQuery or vanilla Javascript
Bootstrap was used for styling and creation of new components (e.g. cards for each day of the five day forecast)
The Bootstrap grid was used to establish containers, rows and columns
Clean simple UI with graphical representation of weather
Moment.js is used to convert unix timestamp to MM/DD/YYYY format
Background color of UV index will adjust based on World Health Organization color scale
Usage:
Enter the name of the city or city name, state code and country code you wish to search for in the search input field.  You can click on cities in the history section to obtain their weather data again . For country codes visit: https://github.com/bharathbharath56139-oss/Weather-Dashboard.git
Links:
Deployed application: https://weather-dashboard-swart-tau.vercel.app/
Screenshots: 
The following image shows a snapshot of the application:

![1000012261](https://github.com/user-attachments/assets/00db4c40-f285-46a3-b0b8-f86418ea80aa)

![1000012267](https://github.com/user-attachments/assets/2f388b07-d345-4387-bf34-a7212846fbdc)
