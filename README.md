# Fetch-data-from-Thingspeak-API

## Objective
- Design a HTML file to get data from the ThingSpeak Channel with jQuery, ajax, css/html elements and design interact buttom functions with JavaScript.

## Desciption
**fetchData.html** is the HTML file that intented to get the temperature data from ThingSpeak IoT platform. There are two buttom function. If the user click the “Get Data” button, the page can download the real-time update weather data, including humidity and temperature (Fahrenheit and degrees Celsius), from the MathWorks Weather Station ([thingspeak channel link](https://thingspeak.com/channels/12397)). 

If the user wants to stop fetch the data, the “Stop” button could stop getting data by clearing the timeout set for looping the getData function, and clear the value in the text field.

## Capture
1. After the user click the **Get Data** Buttom
![image](https://user-images.githubusercontent.com/44689459/169243228-7315e76d-a2f4-4115-bb16-3908748c0b72.png)
2. After the user click the **Stop** Buttom
![image](https://user-images.githubusercontent.com/44689459/169242697-3db5abbb-c2c2-4a77-91a4-a212314948fc.png)


## How to use the file
1. Download the *fetchData.html* and *jquery-3.6.0.js* JQuery library file, assign them in the same directory
2. Open the HTML file in a browser
3. Data will be fetch from ThingSpeak every 30 second and It will refresh automatically if the data has changed. 
