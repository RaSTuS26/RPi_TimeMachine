# RPi_TimeMachine
Clock and Weather display

- A simple Clock and Weather display for Raspberry Pi with 5" 800 x 480 LCD.

- /html/index.html should be a symlink to /html/date-time-weather.html, somehow GitHub can't handle symlinks.

- /html/images is the directory for the background images, I think mine are free but can't be sure, see README in that directory for more info.

- For /html/weather-current.html, must have a Websockets enabled MQTT server running that can supply local weather information (I use a custom weewx server with weewx-mqtt to supply MQTT data to my MQTT server).

- Not sure on the restrictions to importing data to /html/weather-forecast.html, I use a OpenHAB3 forecast page, but I suppose any external URL will also work (though untested).

- The bottom Underlined texts in following screenshots are links are to the other page (two pages in total).


Screenshots:

![Main Display](TimeMachine_210614_213347_800x480.png)



![Weather Forecast](TimeMachine_210614_213413_800x480.png)

