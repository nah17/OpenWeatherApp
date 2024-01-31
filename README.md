## OpenWeatherApp
#### ITSS 4312 - Project 3: Weather App
11/28/2023

This project is a Weather App that gives users daily weather information based on location.
It that takes the user input (city or zipcode)
and parses the information to be sent in a request for the weather API.

This project uses OpenWeather's free API to retrive weather data about the entered location
such as: the current temperature, a brief weather description, 
maximim and minimum daily temperatures, what the current weather feels like,
the country the entered location is in, and the weather icon associaited with current condidtions.

The home entry page consists of an input box where the user can enter the name of the city
or the zipcode of the place they are looking for weather information about.
It features a stormy background image and a button where users will click to enter the location.

Once users click the button, it will direct them to a new page that displays the city, country,
current temperatures, weather icon of current temperatures, description of the weather,
maximum daily temperature, minimum daily temperature, and what the weather currently feels like
in Fahrenheit (imperial units).

Files included in this folder are ajax.html, gethint.php, hint.html, index.html, itunes.html,
jquery-3.5.1.min.js, jquery.html, location.html, styleW.css, weather_background.jpg, weather.html,
and wt.html. Most of these files are extra files to help create an app. The most important files 
are jquery-3.5.1.min.js, jquery.html, styleW.css, weather_background.jpg, and weather.html. 
jquery-3.5.1.min.js and jquery.html provide the foundation to use javascript in the .html files.
styleW.css is the stylesheet for the application, weather_background.jpg is the image used for 
the background of application, and weather.html houses all the back-end code to run the application
including the code to request and send the API.

This program only uses front-end languages such as HTML, CSS, JavaScript, or jQuery.
All this application's webpages are responsive to mobile devices
