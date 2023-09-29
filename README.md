# ESP32

ESP32 connects to Wi-Fi

## How to use

### Configure the project

<!-- Open the project configuration menu (`idf.py menuconfig` / F1 -> `ESP-IDF: SDK Configuration Editor`). -->
<!-- In the `ESP Configuration` menu: -->

<!-- * Set the Wi-Fi configuration. -->
<!-- * Set `WiFi SSID`. -->
<!-- * Set `WiFi Password`. -->

Edit parameters ssid and passwd in BS_ESP.

Optional: If you need, change the other options according to your requirements.

### Build and Flash

Build the project and flash it to the board, then run the monitor tool to view the serial output:

Run `idf.py -p PORT flash monitor` to build, flash and monitor the project.