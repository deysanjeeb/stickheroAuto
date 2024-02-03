# stickheroAuto

# Stick Hero Automation Project

This project is a Python script that automates the game Stick Hero using the Android Debug Bridge (ADB) and image processing.

## Features

- Connects to an Android device using ADB.
- Takes screenshots of the game.
- Processes the screenshots to determine the positions of the platforms.
- Calculates the distance the hero needs to travel.
- Automates the game based on the calculated distances.

## Requirements

- Python 3
- ADB installed and configured
- An Android device with Stick Hero installed
- The following Python packages: `ppadb`, `PIL`, `numpy`

## Installation

1. Clone this repository.
2. Install the required Python packages using pip:

    ```bash
    pip install -r requirements.txt
    ```

3. Run the script:

    ```bash
    python stickhero.py
    ```

## Usage

1. Connect your Android device to your computer.
2. Start the Stick Hero game on your device.
3. Run the script on your computer.

## Contributing

Contributions are welcome. Please open an issue to discuss your idea or submit a pull request.

## License

This project is licensed under the terms of the MIT license.
