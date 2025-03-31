## Arduino IDE Setttings

If the Arduino IDE doesn't have by default the board "ESP32 Dev Module", then go to **Settings** (Arduino IDE menu), then be sure that in **Additional boards manager URLs** there is:

```
https://espressif.github.io/arduino-esp32/package_esp32_index.json
```

## Libraries

**This project requires this additional lib:**

https://github.com/Links2004/arduinoWebSockets<br>
https://github.com/bblanchon/ArduinoJson<br>
https://github.com/ewpa/LibSSH-ESP32<br>
https://github.com/iodeo/Minitel1B_Hard<br>

## IMPORTANT WARNING

keep version 2.0.x of esp32 library (**don't** jump on 3.x.x)
