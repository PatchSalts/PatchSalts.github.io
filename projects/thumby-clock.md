[← Back](/)

# Thumby clock

A multi-function clock application for the Thumby device by TinyCircuits.

[View Thumby clock on GitHub](https://github.com/PatchSalts/thumby-clock)

## About Thumby

![A teal Thumby grasped between my fingers; it displays the startup logo and the word "Start"](/assets/img/tc_device.png)

The Thumby is a device by TinyCircuits. It is designed to be a portable game console, like a Game Boy, but about the same size as the last segment of your thumb. The Thumby supports 3 different programming languages, a version of Python called MicroPython, Arduino C/C++, and a visual programming language called Blockly. I chose to implement this project in MicroPython. As the name implies, it is a smaller subset of Python, so some features are not included, such as the module for building Interfaces. On top of that, the hardware does not support certain features, such as a real-time clock. I would have enjoyed building a 3rd feature that tells the current time, but it's just not feasible. I decided that the best approach for the remaining features I wanted was to build a stopwatch using the State pattern, and extending that class to build the timer. It might be a bit much for a simple stopwatch and timer feature, but I think it's good to practice good design.

## Usage

After placing the application in the "games" folder on your device (or Thumby Code Editor in your browser), simply start up the application (`Clock.py`).

Currently my test modules display a series of tests, but they are not loaded by default. One must import the tests and run them from the `Clock.py` file.

![A screenshot from Thumby-clock displaying the start of the test suite; it says "0.0" in larger text, with smaller text saying "<class 'stopwatchModelStateStop'>" in smaller text below](/assets/img/tc_stop.png)

[Switch between the screens by holding the Left or Right buttons. On the Stopwatch screen, press the "A" button to start or pause the stopwatch, and the "B" button to stop it. On the Timer screen, use the Up/Down/Left/Right buttons to select your time (only when stopped), the "A" button to start or pause the timer, and the "B" button to stop it.]: #

## About the project

When I was gifted a Thumby for Christmas, I thought it was wonderful! But I was also kinda sad because it's too small for me to practically play games on it. Eventually, I realized its miniscule size is actually an advantage; it may not be the game console for me, but I could still use it to make and run practical applications. I've been trying all sorts of fun productivity strategies lately, so I thought it might be fun to build a tool to help me, like a timer and alarm clock.
