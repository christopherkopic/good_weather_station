# Dossier
Links to hardware, software, tutorials, other useful info.

## Hardware for Minimal Viable Product:
- [Waveshare 2.7inch e-paper display](https://www.waveshare.com/wiki/2.7inch_e-Paper_HAT)
- [Waveshare esp driver board](https://www.waveshare.com/wiki/E-Paper_ESP8266_Driver_Board)
- [Adafruit Reset Enable Timer](https://learn.adafruit.com/adafruit-tpl5111-reset-enable-timer-breakout/overview)

## Hardware for V1:
- [Waveshare 4.2inch e-paper display](https://www.waveshare.com/wiki/4.2inch_e-Paper_Module)
- [Waveshare E-Paper Driver HAT](https://www.waveshare.com/wiki/E-Paper_Driver_HAT)
- [Adafruit Feather Huzzah](https://www.adafruit.com/product/2821)
- Some 3.7V protected LiPo Battery

## Hardware once considered:
- [Waveshare 7.5inch e-paper display](https://www.waveshare.com/wiki/7.5inch_e-Paper_HAT_(C))
- [Adafruit Power Boost 1000](https://www.adafruit.com/product/2465)

## Libraries:
- [GxEPD](https://github.com/ZinggJM/GxEPD)
- [Adafruit GFX](https://github.com/adafruit/Adafruit-GFX-Library)
- [Json Streaming Parser](https://github.com/squix78/json-streaming-parser)
- [Esp2866 Weather Station](https://github.com/ThingPulse/esp8266-weather-station)

## Libraries once considered
- [ArduinoJson](https://github.com/bblanchon/ArduinoJson)

## Similar Projects:
- [Kevin Darrah - Youtube Stats Display](http://www.kevindarrah.com/wiki/index.php?title=EPaperBoard)
- [Educ8s - Esp8266 Weather Station](http://educ8s.tv/esp8266-weather-display/)
- [Losant - Esp2866 Deep Sleep](https://www.losant.com/blog/making-the-esp8266-low-powered-with-deep-sleep)
- [Adafruit ESP2866 TFT Weather Station](https://learn.adafruit.com/wifi-weather-station-with-tft-display/overview)

## APIs
- [OpenWeatherMap](https://openweathermap.org/appid)

## Issues
- The Waveshare esp driver board cannot easily wake from deep sleep, as GPIO 16 is already used for the display. Additional hardware, like the Adafruit Reset Enable Timer may solve this problem.
- OpenWeatherMap forecasts are too large to be used with the ArduinoJson Library on ESP2866. Use a Streaming Parser or the Esp2866 Weather Station Library instead.
