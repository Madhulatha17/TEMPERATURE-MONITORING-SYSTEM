# TEMPERATURE-MONITORING-SYSTEM

## Project Overview

This project demonstrates a Temperature Monitoring System using Arduino Uno and a Temperature Sensor. The system reads temperature values from the sensor and displays the measured temperature on the Serial Monitor in real time.

## Objective

To design and implement a temperature monitoring system capable of measuring ambient temperature and displaying the readings continuously.

## Components Used

* Arduino Uno
* Temperature Sensor
* Jumper Wires
* Tinkercad Simulation Environment

## Circuit Connections

### Temperature Sensor to Arduino Uno

* VCC → 5V
* GND → GND
* SIG → A0

## Working Principle

The temperature sensor generates an analog signal based on the surrounding temperature. Arduino reads this signal through the analog input pin (A0), converts it into temperature values, and displays the result on the Serial Monitor.

## Arduino Code Functionality

1. Read analog data from the temperature sensor.
2. Convert the sensor value into voltage.
3. Calculate temperature in degrees Celsius.
4. Display temperature readings on the Serial Monitor.
5. Repeat the process every second.

## Simulation Procedure

1. Open the circuit in Tinkercad.
2. Connect the Temperature Sensor to Arduino Uno.
3. Upload the Arduino code.
4. Start the simulation.
5. Open the Serial Monitor.
6. Observe the temperature readings displayed in real time.

## Sample Output

```text id="tempsample"
Temperature: 24.78 °C
Temperature: 25.12 °C
Temperature: 25.45 °C
Temperature: 25.67 °C
```

## Applications

* Weather Monitoring Systems
* Smart Home Automation
* Industrial Temperature Monitoring
* Environmental Monitoring Systems
* IoT-Based Sensor Networks

## Files Included

* temperature_sensor.ino
* circuit_diagram.png
* output_demo.png
* README.md

## Outcome

Successfully developed and simulated a Temperature Monitoring System using Arduino Uno and a Temperature Sensor. The system continuously monitors temperature and displays real-time readings on the Serial Monitor.
