# SMART ATTENDANCE

# Description of the project

RFID integrated with cloud system which allows instructors to check attendance of the students on an online platform

# Team Members

Can KARACA
Yigit YALCINKAYA

### Hardware setup
### RFID RC522 Pin Connection

* SDA to pin 10 on Arduino

* SCK to pin 13 on Arduino

* MOSI to pin 11 on Arduino

* MISO to pin 12 on Arduino

* IRQ to NC on Arduino

* GND to GND on Arduino

* RSD to pin 9 on Arduino

* 3.3V to 3.3V on Arduino


### ESP 8266 Pin Connection

* RX to RX on Arduino

* TX to TX on Arduino

* GND to GND on Arduino

* VCC to 5V on Arduino

* CH_PD to 5V on Arduino


### Flow of data 
* RFID reads the ID card
* Data is sent to Node-Red with WIFI module
* Node-Red converts the data to the student names
* Node-Red sends student names to the mail address


### Development Environment

* Development Operating System: MacOS 10.13.2

* Development tools: node-RED v0.17, Arduino IDE

