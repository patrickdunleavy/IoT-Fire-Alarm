# IoTFireAlarm
This project was completed for EEL3923C Electrical Engineering Design 1 (Junior Design) at the University of Florida

Smart Fire Alarm triggered using a thermistor. The board contains a PIC18F47K40 microcontroller which is responsible for driving an external DAC, LEDs, and other externals. An ESP8266 communicates with the PIC using a flag, which is set when a fire is detected. The ESP then writes to a Blynk server, which handles a very simple GUI on a mobile phone app to indicate that a fire has been detected.

**Assembled Project:**



