# BC3930 - Module2

## Blog: [Module 2 Project - Sanrio Space Invaders](https://spotted-cayenne-502.notion.site/Module-2-Project-Sanrio-Space-Invaders-12b28a677bce809c89b8e704d8e946c2)

### Tools Needed:
1. LILYGO ESP32 Board
2. [Arduino IDE](https://www.arduino.cc/en/software)
3. [Processing](https://processing.org/download)
4. TFT Espi Library [(Downloadable)](https://github.com/Xinyuan-LilyGO/TTGO-T-Display)  - [Documentation](https://github.com/Bodmer/TFT_eSPI/tree/5793878d24161c1ed23ccb136f8564f332506d53)
5. USB-c cord
6. 7 female/male wires (for breadboard)
7. 5 m/f jumper wires (for joystick)
8. Joystick
9. Button
10. Wires
11. Breadboard

### Code Description 

`/arduinoButtonAndJoystick` - holds the arduino file for code to uploaded to the ESP32 board

`/enclosure` - holds the svg files related to the enclosure for laser cutting

`/sanrioinvaders` - holds the code for launching the space invaders interface and game through the Processing application

### Fritzing Diagram

<img width="607" alt="fritzdiagram" src="https://github.com/user-attachments/assets/df4b17f3-2255-42ab-8668-069a451cace2">


### Setup
1. Follow the Fritzing diagram and add your button, joystick, wires, and ESP32 board to the breadboard
2. Connect your ESP32 board to your computer via a USB-C cord
3. Download the `/arduinoButtonAndJoystick` and `/sanrioinvaders` folders
4. Open these folders in the Arduino IDE application and Processing application, respectively
5. Confirm that your ESP32 board connects to the Arduino application by running the arduino code file `buttonjoystick.ino` (you should see printed values read from the serial communication)
6. Open the '' from the `/sanrioinvaders` folder in the Processing application and ensure that it runs and complies
8. Once a screen pops up from the Processing application go ahead and press "s" on the keyboard to start!
   
~ *Feel free to make any edits to the code after downloading and experiment on your own!* ~
### Media

https://github.com/user-attachments/assets/5a80bb89-0fcb-4d04-890f-efea8de33748

