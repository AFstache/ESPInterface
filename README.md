# ESPInterface
GPIO Interface for ESP-01 chip

This is an interface card between an ESP-01 chip and a GPIO device. The board was designed in KiCad and based on the plans found <a href = https://www.instructables.com/ESP-12E-ESP8266-With-Arduino-Uno-Getting-Connected/>here</a>.

To send the files to a manufacturer, add all .gbr and .drl files to a zip archive and upload. The board has been manufactured by JLCPCB and does work from them. Required are three 10k resistors, two 6x6x5mm 4 pin momentary switches, a row of 10 pin right angle GPIO pins, and the ESP-01 board.

![Front View](https://github.com/AFStache/ESPInterface/blob/main/Front_View.png?raw=true)
![Rear View](https://github.com/AFStache/ESPInterface/blob/main/Rear_View.png?raw=true)

To flash custom firmware to the ESP, connect the board to the GPIO interface, press and hold the flash button, and press and release the reset button. This will put the ESP into flash mode. Using your favorite code IDE (recommend Arduino), set the bit rate to 115200, and push the firmware.
