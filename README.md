# Moledcule Sanwa OBSF 30 LED PCB

This repository contains the design and firmware for the WS2812B Programmable LED PCB for Sanwa OBSF 30mm Buttons. This PCB is designed to fit into Sanwa OBSF 30 buttons and provides customizable LED lighting effects using WS2812B LEDs.

![Sanwa OBSF 30](https://raw.githubusercontent.com/moledcule/sanwa-obsf-30/master/sanwa-obsf-30.png)

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Requirements](#requirements)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Overview

The Moledcule Sanwa OBSF 30 LED PCB is designed to enhance the visual appeal of your fightstick by integrating programmable WS2812B LEDs into Sanwa OBSF 30mm buttons. This PCB allows for dynamic and customizable lighting effects, adding a new dimension to your gaming experience.

## Features

- Compatible with Sanwa OBSF 30mm buttons
- Integrated WS2812B LEDs for vibrant lighting effects
- Easy installation and setup
- Customizable through firmware updates
- Low power consumption

## Requirements

- Moledcule Sanwa OBSF 30 LED PCB
- Sanwa OBSF 30mm buttons
- Power source (typically 5V via USB)
- Microcontroller (e.g., Arduino, ESP8266, ESP32) for controlling the LEDs
- Required libraries and dependencies

## Installation

1. **Hardware Setup:**
   - Install the Moledcule Sanwa OBSF 30 LED PCB into your Sanwa OBSF 30mm buttons.
   - Connect the PCB to a power source.
   - Connect the data line of the WS2812B LEDs to the microcontroller.

2. **Software Setup:**
   - Clone the repository:

     ```bash
     git clone https://github.com/moledcule/board.git
     cd board
     ```

   - Install the necessary libraries for your microcontroller. For example, if using an Arduino:

     ```bash
     arduino-cli lib install "Adafruit NeoPixel"
     ```

   - Upload the provided firmware to your microcontroller.

## Usage

1. Power on your fightstick with the Moledcule Sanwa OBSF 30 LED PCB installed.
2. The LEDs should light up according to the default configuration.
3. Customize the lighting effects by modifying the firmware and re-uploading it to the microcontroller.

## Contributing

We welcome contributions to the Moledcule Sanwa OBSF 30 LED PCB project. To contribute:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Make your changes and commit them with descriptive messages.
4. Push your changes to your fork.
5. Create a pull request to the main repository.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
