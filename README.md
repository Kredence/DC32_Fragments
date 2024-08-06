# DC32_Fragments
Welcome to the Illuminati Party® badge 'Fragments' for 2024 (DC32).

Setup:
1. Install the Arduino IDE https://www.arduino.cc/en/software
2. Open the Arduino IDE, click on Tools at the top, then "Manage Libraries"
3. On the left side of the screen, click on Board Manager
4. Search for ESP32 by Espressif and install the package.
5. On the left side again, click on Library Manager.
6. Search for and install the Adafruit NeoPixel Library. This will likely need to install other dependencies, which you will be prompted to do.
7. Plug in your badge and make it is turned on.
8. Go to Tools > Board, and select ESP32 Dev Module.
9. You'll need to select the appropriate COM port. This will likely be the highest number COM available. If you're unsure, check Device Manager on your computer.

Program:
1. You're all set to push code to the badge. Copy the code into the IDE (paste over anything in the window).
2. Press "Upload" in the ribbon at the top (the arrow in a circle icon)
3. For the first upload, you'll be prompted to save the code to your computer.
4. You should see the IDE compile the code and upload it to the badge.

