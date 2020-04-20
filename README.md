# covid19_e-paper
A wearable e-paper device to track the covid19 status coded by breakstring. Adapted to Lilygo T5 V2.3 ESP32 board by admiral-tryptamine

# Hardware
 - Lilygo T5 V2.3 ESP32 board [E-Paper_ESP32_Driver_Board](https://github.com/Xinyuan-LilyGO/LilyGo-T5-ink-series): This is a badge style ESP32 board with a 2.13 inch ePaper display.
 
# Depend on
 - Diplay render: [GxEPD2](https://github.com/ZinggJM/GxEPD2)
 - [Data source](https://covid19.mathdro.id/): [API source code](https://github.com/mathdroid/covid-19-api)
 - ArduinoJson: [ArduinoJson](https://github.com/bblanchon/ArduinoJson)
 - WifiClientSecure: [arduino-esp32](https://github.com/espressif/arduino-esp32/tree/master/libraries)




# Connect
If you have all the libraries above installed (most can be found through the built-in Library manager) then compiling and installing should be a breeze. Message me if you run into any problems and I'll try to help you out :)  Do not forgot to change the WiFi SSID and password at the beginning of the sketch to match your own settings. It will pull the confirmed/recovered/deaths data of global, China, Italy, Spain, USA and Germany, from the mathdroid COVID-19 API (which pulls data from John Hopkins University) and cycle through the data country by country in a loop. If you want more, just add logo data of the country and also the related API endpoints. 
