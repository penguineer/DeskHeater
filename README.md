# Desk Heater

> Low-power heated desktop for reducing conductive heat loss while working in a cool room.

This project adds a thin 24 V carbon heating film underneath a bamboo desktop. The goal is not to make the desk feel hot, but to keep the work surface close enough to room/body-neutral temperature that it no longer cools hands and forearms during long work sessions in winter.

The controller is based on an ESP8266 (ESP-12E) and provides:

- temperature monitoring with multiple NTC sensors
- hardware over-temperature protection independent of the ESP
- current, voltage, power and energy measurement
- slow duty-cycle control of the approximately 60 W heating film
- UART and Wi-Fi connectivity for monitoring and future controls

The KiCad design for the controller is in [`Controller/`](Controller/).

## Status

Work in progress. The electrical and mechanical design is currently being prototyped and characterized.

## License

[![Creative Commons License](https://i.creativecommons.org/l/by-sa/4.0/88x31.png)](http://creativecommons.org/licenses/by-sa/4.0/)

This work is licensed under a [Creative Commons Attribution-ShareAlike 4.0 International License](http://creativecommons.org/licenses/by-sa/4.0/).

BY: Stefan Haun (mail@tuxathome.de)

See [LICENSE.txt](LICENSE.txt) for details.
