# Smart Scale

Project originally made by [davidevertuani](https://github.com/davidevertuani) Project info [hackster.io](https://www.hackster.io/daveVertu/make-a-screen-less-google-fit-connected-smart-scale-9a5934)

### Tasks

- [x] Get original code to build
- [ ] Clean up original code for final release
- [ ] Adapt code to work with e-ink display

## Required Libs

* [ESP8266 for Arduino](https://github.com/esp8266/Arduino)
* [HX711](https://github.com/bogde/HX711)
* [ArduinoJson](https://github.com/bblanchon/ArduinoJson)

## Building

To build with VS code ensure all files are added to "forcedInclude" in c_cpp_properties.json
```javascript
{
    "configurations": [
        {
            "forcedInclude": [
                "${workspaceFolder}/SmartScale/Google_Messages.ino",
                "${workspaceFolder}/SmartScale/GoogleFit.ino",
                "${workspaceFolder}/SmartScale/Scale.ino",
                "${workspaceFolder}/SmartScale/User.ino"
            ]
        }
    ],
    "version": 4
}
```
