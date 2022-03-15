# ESP8266IGate Project
ESP826IGate is a Internet Gateway + Tracker + Display that is implemented for Espressif ESP82666 processor.
ESP8266 connect to wifi and decode or config display by OLED SD1306 or SH1106 and control by rotary swicth.

## Feature
- APRS Decode and Display monitor
- Package History 50 station
- Swap Display info and TNC2 Raw by push button
- Smart Beacon Tracker to TNC or WiFi Only Support
- OLED Bright control
- Push Rotory button to Manual TX
- Push Hold Rotory button to Display pause
- Popup display TX Status
- Compass Heat Up
- Display GPS Dash board
- nTNC-Module control and firmware support

## ESP8266IGate Circuit

![Tracker WiFi](Image/ESP8266_IGATE_noTNC.png)

![NodeMCU](Image/modemcu.png)

![HT_Inteface](Image/ESP8266_IGATE_TNC_MIC.png)

## ESP8266IGate Screen Short

![screen_tracker](ScreenShort/tracker.png)

![screen_config](ScreenShort/configstation.png)

![screen_laststation](ScreenShort/laststation.png)

![screen_gps](ScreenShort/gps.png)

## TOOL & Firmware

- Tool Flash ESP8266 [here](Firmware/ESP8266Flasher.rar)
- Firmware V0.8 for OLED SD1306 0.96" [here](Firmware/ESP_IGate_SD1306.bin)
- Firmware V0.8 for OLED SH1106 1.3" [here](Firmware/ESP_IGate_SH1106.bin)
