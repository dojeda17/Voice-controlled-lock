# Voice-controlled-lock
This project allows you to open and close a lock with voice commands. It uses an AI voice model to detect commands and send serial communication from the code to the arduino. The AI voice model is Open AI's "Whisper" to detect voice commands. 

This is my first arduino project and my first project using C++ and Python. This project was a really challenging but fun experience overrall. 

## Project Requirements:
Arduino Mega 2560(or any arduino of choice) || Python 3.11(Whisper does not work for python 3.13) || WhisperAI || Jumper cables || servo motor || Pyserial 3.5 library, helps python communicate to arduino via serial communication through designated port || Arduino IDE ||

## Potential issues
1. Port configuration
- Make sure the baud Rate is set at 9600 and to make sure to set the right port name to the variable "port" in the code. For example, my port name was "USBmodem2101". This varies from computer to computer but a common one is "COM3"
- To make sure python has access to your port, make sure the port address is typed in the "port" tab in the bottom section of VScode. For example, mine was 2101.
2. Python environments
-  If using virtual environments, activate it correctly and ensure all required packages are installed within it.
3. Missing python modules
- Make sure you download all of your imports through the terminal. One way I did this was by manually installing it in the terminal with this command: pip install serial whisper openai numpy sounddevice
4. Hardware
- Make sure all hardware is working correctly. Any damage to the hardware would not let the project work.

- Video Link: https://youtu.be/LQOoFSo-Rjc
