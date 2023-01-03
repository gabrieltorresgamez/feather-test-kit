# feather-test-kit
Example for using CircuitPython to communicate with sensors on a Feather nRF52840 Express.

![Layout](FeatherLayout.png)

## Hardware
* CO2 Sensor SCD30
* Temperature and Humidity Sensor DHT11
* PIR Motion Sensor
* Light Sensor  v1.2
* Chainable RGB LED

## Software
* CircuitPython 7.2.0 (.uf2 file in this repo)

## Wiring
As shown in the first image:
* CO2 Sensor SCD30: I2C-1
* Temperature and Humidity Sensor DHT11: D2
* Motion Sensor: D4
* Light Sensor: A0
* Chainable RGB LED: A2/D16

