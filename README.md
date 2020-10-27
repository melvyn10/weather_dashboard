# weather_dashboard


This is a weather dashboard that provide the user the capabilities to enter a city name and search for it. The dashboard will then show the current and future conditions for that city. It will also save the city as a selectable field. If the user select any of the historical city, it will show the present and future weatheer conditions. The dashboard will also present the user with the last searched information if the dashboard is closed.This app will run in the browser and feature dynamically updated HTML and CSS powered by jQuery.

The dashboard uses the following:
    -jquery is used to dynamically create the html
    -[Moment.js](https://momentjs.com/) library to work with date and time
    -Bootstrap to create a jumbotron for the current weather conditions
    -Bootstrap to create the cards for the 5 forecasted weather
    -the openweather api was used to retrieve weather information for city requested
    -Two functions were created: cityList and getCityWeather
        -cityList: reads the list of historical cities and populates the city search list
        -getCityWeather: take input city and performs 3 api calls to retrive current weather, UV index, and 5 day weather forecast

This application consists of 1 html page and a style css file.

The following were implemented:
the code to include semantic elements

Header

This code has been validated by W3C Markup Validation Service and error/warnings are corrected or understood.

Installation instruction

Create a GitHub account on github.com.
Create a new repository in your GitHub application. 
Download the files
Publish the website in GitHub
![image](https://github.com/melvyn10/weather_dashboard/tree/main/asset/Images/imageLowAlaska.gif)

![image](https://github.com/melvyn10/weather_dashboard/tree/main/asset/Images/imageModerateAtlanta.gif)

![image](https://github.com/melvyn10/weather_dashboard/tree/main/asset/Images/imageVHighSidney.gif)
