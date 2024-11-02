# Version 2.0

Guide for checking if ESP32 on board is correctly set up:
1) Modify code for Blink.ino with appropriate pin number. Replace LED_BUILTIN with a hardcoded value (12).
2) Arduino version 2.3.2
3) ESP32 library should be added via additional boards manager.
    Link for JSON: https://espressif.github.io/arduino-esp32/package_esp32_index.json
4) Use a working data cable
5) Select correct board (ESP32 Dev Module)
6) Check if driver for CH340 is available. (Pre-installed in Windows 11)
7) Baud rate should be high enough.
8) While uploading, perform the following:
   i) Hold Reset and Flash. Release reset.
   ii) Hold Flash until uploading completes.

The below message should be seen:
