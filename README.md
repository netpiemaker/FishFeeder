# FishFeeder
An IOT fish feeder powered by NETPIE platform

![fishfeeder](https://cloud.githubusercontent.com/assets/7685964/13938407/2e1af972-f000-11e5-91a2-4c3cb060126c.jpg)

###Instruction

- Sign up at https://netpie.io
- Generate the App ID and get the AppKey and AppSecret

####ESP8266
- Edit the file ESP8266/FishFeeder/AppKey.h with the above AppID, AppKey and AppSecret
- Before building with an Arduino IDE, make sure you have these dependencies installed
 - Arduino Core for ESP8266 https://github.com/esp8266/Arduino
 - Microgear-esp8266-arduino https://github.com/netpieio/microgear-esp8266-arduino
 - WiFiManager https://github.com/tzapu/WiFiManager.git
 - ESP8266-OLED-SSD1306 https://github.com/squix78/esp8266-oled-ssd1306

####HTML5
- Open HTML5/index.html directly with any web browsers (except IE) passing a URL hash like this
```
index.html#<NETPIE_APPID>:<NETPIE_APPKEY>:<NETPIE_APPSECRET>
```
- Replace NETPIE_APPID, NETPIE_APPKEY and NETPIE_APPSECRET with the same keys in ESP8266.
- You don't need a web server to host HTML files as they can be accessed from the following URL
```
http://rawgit.com/netpiemaker/FishFeeder/master/HTML5/index.html#<NETPIE_APPID>:<NETPIE_APPKEY>:<NETPIE_APPSECRET>
```
- For your convenience, you may attch a QR code of the URL above on the feeder.
- For more information about NETPIE please visit https://netpie.io
- NETPIE microgear library for ESP8266 is available here
https://github.com/netpieio/microgear-esp8266-arduino

