# SmartMethods-IOT
This repository is for the tasks in the IOT path in smart methods training.
# Task 1
## Draw the electronic circuit and write the code required to turn on the LED at the letter F and turn it off at the letter S.
- Turn on the LED at the letter F
  <img width="960" alt="image" src="https://github.com/NZ199/SmartMethods-IOT/assets/95175322/9b031d2c-6bad-435c-b63c-73d4c652cbc9">
   https://wokwi.com/projects/370835854808263681
- Turn it off at the letter S
  <img width="960" alt="image" src="https://github.com/NZ199/SmartMethods-IOT/assets/95175322/1229a7d8-384d-4d3e-a54a-02e6c77a3c0c">
  https://wokwi.com/projects/370834935272048641
- HTML Page
  1. https://s-m.com.sa/f.html
  2. https://s-m.com.sa/s.html


# Task 2
## Connecting two controllers together
This task demonstrates how to connect two Arduino controllers together using the I2C communication protocol in Tinkercad. The first controller reads the state of a push button and sends it to the second controller, which controls an LED based on the received value.
### Hardware Requirements
To complete this task, you will need the following components:
- 2 x Arduino UNO boards
- 1 x Push button
- 1 x LED
- 2 x 220-ohm resistors
- Jumper wires

### Software Requirements
To complete this task, you will need access to the Tinkercad online simulation platform.

### Circuit 
<img width="960" alt="image" src="https://github.com/NZ199/SmartMethods-IOT/assets/95175322/4654c7fa-e7a4-43a1-a170-c6cf74ba863b">

 # Task 3
## Make an electronic circuit for the humidity reading sensor & link the sensor readings with a plate containing GET
This task involves creating an electronic circuit that measures humidity using a humidity sensor and then transmits the sensor readings to a web server using the GET method. The circuit will be simulated using WOKWI, and the data will be stored and managed using PHPMyAdmin.
### Requirements
To successfully complete this task, you will need the following:
- A computer with internet access WOKWI account (https://wokwi.com)
- Basic knowledge of electronics and circuit design
- ESP32
- Humidity sensor (e.g., DHT11 or DHT22)
- Arduino board (e.g., Arduino Uno)
- Jumper wires
- ohm resistors
- Web server with PHP and MySQL support (e.g., XAMPP)
### Electronic circuit for the humidity reading sensor   
<img width="431" alt="image" src="https://github.com/NZ199/SmartMethods-IOT/assets/95175322/e9126984-370c-426d-84a4-07cc2a9c7cf1">

### HTML Page
<img width="960" alt="image" src="https://github.com/NZ199/SmartMethods-IOT/assets/95175322/518e01c4-349d-4598-8b1b-44ecab0043f2">

### Database
1. In phpMyAdmin, create a database named "esp32", then create a table named "dht" with values shown in below image
<img width="386" alt="image" src="https://github.com/NZ199/SmartMethods-IOT/assets/95175322/03bdef2b-a7ca-4811-bd7a-fc1f66f2658a">

2. Now power ON the ESP32 and use the index.html and app.css files in Task3 to test it.
3. Let the ESP32 run for few minutes to send data to MYSQL database, and as you can see database now have temperature and humidity data:
<img width="184" alt="image" src="https://github.com/NZ199/SmartMethods-IOT/assets/95175322/9bc08126-abd3-4571-a50d-650463f7aabd">




