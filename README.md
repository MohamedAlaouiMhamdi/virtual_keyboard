# Virtual Hand Gesture Keyboard


## Table of Contents

- [Introduction](#introduction)
- [Installation](#installation)
- [Usage](#usage)
- [How It Works](#how-it-works)
- [Demo Video](#demo-video)
- [Contributing](#contributing)
- [License](#license)

## Introduction

The Virtual Hand Gesture Keyboard is an interactive virtual keyboard that allows users to type using hand gestures in front of their webcam. It uses the OpenCV library for hand tracking and recognizes hand gestures to simulate keypresses on the user's computer.

## Installation

1. Clone the repository:

   git clone https://github.com/MohamedAlaouiMhamdi/virtual_keyboard.git

2. Install the required libraries:

   pip install opencv-python mediapipe numpy pynput

3. Run the application:

   python virtual_keyboard.py

## Usage

1. Place your hand in front of the webcam to enable hand tracking.
2. Use gestures to select keys from the virtual keyboard displayed on the screen.
3. The selected keys will be typed into any active text input on your computer.

## How It Works

The Virtual Hand Gesture Keyboard uses the Mediapipe library for hand tracking. It tracks the user's hand landmarks and calculates the distance between specific landmarks to recognize gestures.

The virtual keyboard consists of buttons, and each button is associated with a specific key. When a user's hand is detected, the program identifies the hand gestures and simulates keypresses based on the gestures.

## Demo Video

https://github.com/MohamedAlaouiMhamdi/virtual_keyboard/assets/98537138/5f3d6f68-3233-4664-abaf-0c07cd220b05

## Contributing

Contributions to this project are welcome! If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
