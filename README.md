# Interfacing-sensors-with-microcontroller-Arduino-ESP32
**Exp 1: Interfacing Temperature and Humidity Sensor with ESP32 Using Wokwi**

Aim:

To interface a DHT22 temperature and humidity sensor with an ESP32 microcontroller using the Wokwi online simulator, measure the temperature and relative humidity, and display the measured values on the Serial Monitor.

Apparatus / Software Required:

Software / Online Tools
•	Wokwi Online Simulator 
•	Web browser 
•	ESP32 simulation board 
•	Arduino C/C++ program 
•	DHT22 sensor model 

Simulated Components
•	ESP32 DevKit
•	DHT22
•	Jumper wires
•	Serial Monitor

Circuit Diagram: 

Students shall design and simulate the circuit using the Wokwi online simulator. Take a clear screenshot of the completed circuit showing all the components and their connections, and include it in this section. The component names, pin connections, and ESP32 GPIO connections should be clearly visible in the screenshot.

Procedure:

Step-by-step operation
•	ESP32 is powered. 
•	ESP32 initializes the DHT22 sensor. 
•	The DHT22 measures temperature and relative humidity. 
•	The sensor sends digital data to ESP32. 
•	ESP32 reads the data through GPIO 4. 
•	The Arduino program converts the received data into temperature and humidity values. 
•	The values are sent through UART/USB serial communication and appear on the Wokwi Serial Monitor.

Simulation Procedure:

Step 1 : Install Wokwi online simulator and Open 
Step 2 : Create a new ESP32 project.
Step 3 : Add ESP32 DevKit, DHT22
Step 5 : Connect the sensor: VCC  → 3.3 V; DATA → GPIO 4; GND  → GND
Step 6 : Open the program editor.
Step 7 :Enter the Arduino C/C++ program.
Step 8 : Make sure the DHT22 library is available in the Wokwi project.
Step 9 : Start Simulation
Step 10 : Open the Serial Monitor and Observe the temperature and humidity values.

Output:

<img width="829" height="529" alt="image" src="https://github.com/user-attachments/assets/c6437f9d-f71c-4e46-acf6-1ba573461c3d" />

Result:
Thus, the DHT22 temperature and humidity sensor was successfully interfaced with the ESP32 microcontroller using the Wokwi online simulation platform. 
