# About
This repository contains codes to realize an expensive espDrone

# espDrone

The espDrone works with Drone Controller https://github.com/Simaho99/espDroneController.git

Use uptodate Arduino IDE, or Platformio in VS Code 

Devices:
1. MPU6050
2. ESP8266 (any chip)

The rest is optional, it depends on your design
3. MOSFET (IRFZ/ IRFL etc)
4. SmallBrushed Motor
5. Propellers
6. Frame
7. etc

[env:esp12e]
platform = espressif8266
board = esp12e
framework = arduino

lib_deps =
1. 7364 ;Modbus IP
2. 11 ;I2Cdev.h
3. PID
4. EspSoftwareSerial
5. MPU6050 library
    
 ***STILL IN DEVELOPMENT***
