# ESPFAN
Fancoller based upon ESPHome

To be used in a setup with a convector, like my 600mm wide Jaga Tempo T21.
It combines a readily available ESP8266 controller with some simple electronics to control PWM fans (4pin). Also it monitors the temperatures going in and out of the convector and the current fanspeed.

The project is based upon EPSHome, a project by Nabu Casa.

# Schematics

Will follow soon

# Electronics

    Wemos D1 Mini: Cheap 'n simple ESP8266 controller
    Relay Shield: Toggles the 12V to the fans
    Power Shield (12V Stepdown to 3.3V and 5V): Power converter from 12V to 3.3V and 5V for the electronics
    2x DS18B20 Sensors: Reliable temperature sensors for monitoring.
    4.7 kohm resistor
    12V Adapter and 12V Extension Cable (Male/Female Barrel Jack): Convenient power source, readily available from online or local suppliers.

While the basic kit suffices, there's room for customization. Consider adding external connectors for easier access and enhancing functionality for future projects.

# Hardware

    2x Noctua NF-A20 PWM 200mm Fans: Known for silent operation and efficient airflow.
    1m 35x35mm Plastic Angle Profile: A versatile structural element.
    1m Glass Tape: To dampen vibrations between components.
    Residual Wood, Beech: Salvaged from previous projects.
    Junction Box: Essential for organization and safety.
