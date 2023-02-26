I'm not going to follow the project, I can't find information for it.
If you find any information on how to program it, I would appreciate it if you let me know.
Thank you


# ESP32-GATEWAY
Sobre el ESP32-GATEWAY
Olimex ESP32 boards are supported in the official Arduino IDE for ESP32. We commit updates 
directly in the ESP32's GitHub. When installing the ESP32 for Arduino IDE refer to these 
instructions:

https://espressif-docs.readthedocs-hosted.com/projects/arduino-esp32/en/latest/installing.html

(!) Make sure to use the stable release JSON link in your Arduino IDE (not the stable 
release link).

This link exactly:

https://raw.githubusercontent.com/espressif/arduino-esp32/gh-pages/package_esp32_index.json

(!!) No olvides instalar el paquete ESP32 en Arduino. Esto se hace a través de las Boads.
Administrador en el menú Herramientas > Tablero /Board menu).


After package is installed you can load example from File -> Examples and look under tab named
"Examples for OLIMEX ESP32-GATEWAY".

To load example for the Ethernet go to:

File -> Examples -> Ethernet -> ETH_LAN8720

Some of the examples might need manual software setting pins compatible with the Olimex-made
board.
