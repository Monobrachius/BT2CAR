ESP32-C3 pinout

| PIN | name | description|
|-----|------|------------|
| 9 | button | activated WIFI for configuration CAN buttons and selection of devices|
| 6 | led    |    |
|0/A0| Vaccu | voltage coming from accu: will be used to switch to low-power mode after TBD minutes. Apparantly treshold used is 13V when motor is off|
| e.g. GPIO4 | CTX/twai_rx          | CAN-bus, can be any pin, see page 32 manual |
| e.g. GPIO5 | CRX/twai_rx          | CAN-bus, can be any pin, see page 32 manual |
| TBD        | twai_bus_off_on      | probably not needed |
| TBD        | twai_clkout          | probably not needed |
| TBD, e.g. 26 | bck_io_num         | I2S, can be any pin, see page 31 manual |
| TBD, e.g. 25 | ws_io_num          | I2S, can be any pin, see page 31 manual |
| TBD, e.g. 22 | data_out_num       | I2S, can be any pin, see page 31 manual |

ESP32C3 manual:https://www.espressif.com/sites/default/files/documentation/esp32-c3_datasheet_en.pdf page 31 and 32.  
https://github.com/MagnusThome/RejsaCAN-ESP32  
https://github.com/LuukEsselbrugge/Volve

OBDII pinout
| PIN | name | description|
|-----|------|------------|
| 4 |  Chassis GND | 
| 16|  Battery PWR | 
| 5 |  Signal GND  | 
| 6 |  CAN-HIGH    | 
| 14|  CAN-LOW     | 
