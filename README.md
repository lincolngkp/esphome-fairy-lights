# esphome-fairy-lights
ESPHome-based fairy lights controller using an ESP32, IR transmitter and Home Assistant integration.

Turn inexpensive IR-controlled fairy lights into a fully integrated Home Assistant device using an ESP32 and ESPHome.

This project shows the complete process, from capturing the original IR remote codes through to creating a reliable Home Assistant integration.

https://youtu.be/Ni5tayycIq4

## Features

- Capture IR codes from the original remote
- Test captured commands using an ESP32
- Control fairy lights from Home Assistant
- ESPHome-based configuration
- Supports power and mode control
- Uses inexpensive, readily available components

## Hardware

- ESP32
- IR Receiver Module
- IR LED / IR Transmitter
- 5V Buck Converter
- IR-controlled Fairy Lights

## Repository Contents

### IR Capture & Testing

Used to capture commands from the original remote control.

```
ir_capture/
```

### Final Project

The finished ESPHome configuration used for Home Assistant integration.

```
final_project/
```


## Wiring



## Installation

1. Clone this repository.
2. Open the required YAML file in ESPHome.
3. Update API key, fallback hotspot PSK, GPIO and naming variables
4. Flash the ESP32.
5. Test IR communication with your fairy lights.
6. Add the device to Home Assistant.

## Video Walkthrough

Watch the full build on YouTube:

https://youtu.be/Ni5tayycIq4

## Why This Project?

Many inexpensive fairy lights include an IR remote but no smart home integration.

Rather than replacing the controller, this project preserves the original hardware and adds Home Assistant control by emulating the original remote using an ESP32 and an IR transmitter.

## License

This project is licensed under the MIT License.
