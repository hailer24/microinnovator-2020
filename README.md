# Soteria
### Why do we need a product like this?

More than 65 Million people are suffering from epilepsy, a disease which bars to either use public transport or drive their own vehicle to travel. Our product enables them to drive their vehicle safely anywhere by alerting them of the upcoming seizure, if any.

## Features of our product:

1. Continuous monitoring of heartbeat and detection of an upcoming seizure.
2. Alert the user by an LED indication before a seizure, hence preventing any fatal accident.
3. Notify the user's family member and  the hospital for immediate attention.

## Working:

```
A heartbeat monitoring sensor, connected to a 32-bit microcontroller(NodeMCU ESP8266) will be placed on the steering wheel.
```
```
Our program will detect a seizure, before it comes, using the data collected by the sensor.
```
```
The NodeMCU will be connected to a cloud based IoT service, IFTTT, through the internet.
```
```
Whenever there will be a seizure, the NodeMCU will send data to IFTTT and an LED will blink to alert the driver.
```
```
IFTTT will generate an SMS, containing the GPS location of the user to the registered numbers immediately after receiving the data.
```
## Circuit

![circuit_image](https://github.com/hailer24/microinnovator-2020/blob/main/circuit.jpg?raw=true)

## Preview

![preview_image](https://github.com/hailer24/microinnovator-2020/blob/main/sample.png?raw=true)
