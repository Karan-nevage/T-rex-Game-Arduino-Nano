# DIY Chrome T-Rex Game with Arduino Nano and OLED Display

This project is a fun and educational DIY project where we bring the classic Chrome T-Rex game to life using an Arduino Nano, an OLED display, and a couple of buttons.

## Components

- Arduino Nano
- OLED Display (128x64 pixels)
- Two Buttons

## Libraries Used

- Wire.h
- Adafruit_GFX.h
- Adafruit_SSD1306.h

## Game Features

- The T-Rex and obstacles (trees) are displayed on the OLED.
- The T-Rex jumps when a button is pressed.
- The game speed increases as your score increases.
- The game ends when the T-Rex collides with a tree.

## How to Run

1. Connect the Arduino Nano to your computer.
2. Open the Arduino IDE and upload the provided code to the Arduino Nano.
3. Once the code is uploaded, the game will start running on the OLED display.
4. Press the button connected to the Arduino to make the T-Rex jump and avoid the trees.

## Code Structure

The code includes the setup and loop functions, which are standard in every Arduino program. The setup function runs once when the program starts and the loop function runs continuously afterwards.

There are also several helper functions to handle different aspects of the game:

- `introMessage()`: Displays the intro message on the OLED.
- `moveDino()`: Moves the T-Rex on the OLED.
- `moveTree()`: Moves the trees on the OLED.
- `gameOver()`: Displays the game over message and the final score on the OLED.
- `displayScore()`: Displays the current score on the OLED.
- `play()`: Contains the main game logic.
- `renderScene()`: Renders the game scene on the OLED.

Enjoy the game!
