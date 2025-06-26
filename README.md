# Smart-Parking-System-using-NodeMCU-and-IoT

With growing popularity of Smart Cities, there is always a demand for smart solutions for every domain. The IoT has enabled the possibility of Smart Cities with it’s over the internet control feature. A person can control the devices installed in his home or office from anywhere in the world by just using a smartphone or any internet connected devices. There are multiple domains in a smart city and Smart Parking is one of the popular domain in the Smart City.

In this IoT Smart Parking System, we will send data to webserver for looking up the availability of space for vehicle parking. Here we are using firebase as Iot database to get the parking availability data. For this we need to find the Firebase host address and the secret key for authorization.


Components Required:

ESP8266 NodeMCU 
Ultrasonic Sensor
DC Servo Motor
IR Sensors
16x2 i2c LCD Display
Jumpers

Working :
In Smart Parking System two IR sensor, two servo motors, one ultrasonic sensor and one 16x2 LCD.
The ESP8266 will control the complete process and also send the parking availability information to Google Firebase so that it can be monitored from anywhere in the world over the internet. Two IR sensors are used at entry and exit gate to detect the presence of car and automatically open or close the gate. IR Sensor is used to detect any object by sending and receiving the IR rays
Two servos will act as entry and exit gate and they rotate to open or close the gate. Finally an Ultrasonic sensor is used to detect if the parking slot is available or occupied and send the data to ESP8266 accordingly.
