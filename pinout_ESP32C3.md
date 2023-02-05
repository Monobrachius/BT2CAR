ESP32-C3 pinout


- 9    button    activated WIFI for configuration CAN buttons and selection of devices
- 6    led
- 0/A0 Vaccu     voltage coming from accu: will be used to switch to low-power mode after TBD minutes. Apparantly treshold used is 13V when motor is off.

CAN-bus  
Any pin: https://www.espressif.com/sites/default/files/documentation/esp32-c3_datasheet_en.pdf page 32.
- GPIO4 CTX/twai_rx                       like
- GPIO5 CRX/twai_rx
- TBD        twai_bus_off_on      probably not needed
- TBD        twai_clkout          robably not needed
https://github.com/MagnusThome/RejsaCAN-ESP32  
https://github.com/LuukEsselbrugge/Volve

I2S-bus  
Any pin: https://www.espressif.com/sites/default/files/documentation/esp32-c3_datasheet_en.pdf page 31.
- TBD
- TBD
- TBD

OBDII pinout
- 4    Chassis GND
- 16   Battery PWR 

- 5    Signal GND
- 6    CAN-HIGH
- 14   CAN-LOW
