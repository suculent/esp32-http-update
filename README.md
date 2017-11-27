# esp32-http-update

ESP Clone of https://github.com/esp8266/Arduino/tree/master/libraries/ESP8266httpUpdate (most work done by Markus Sattler).

# TL;DR

This is just a quick port of ESP8266httpUpdate for ESP32.

Buildable with Arduino framework for ESP32.

There are things remaining to be solved:

* Some headers are deprecated (will change for ESP32 anyway)
* Download to SPIFFS with AES-256 decryption
* Does not support ESP-IDF.
