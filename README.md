# GameportUSB-STM32
Gameport-USB adapter based on STM32F1 blue pill



## Description

Adapter for game controllers of the previous era.
Not so long ago, we connected our joysticks and gamepads to the sound card - to the 15 pin game port.
Nowadays, this port no longer exist. 

There are 3 solutions to that "problem":
- buy new joystick with USB connector
- buy overly expensive usb adapter on ebay
- make your own for fraction of the price



## Getting Started

Tools:
- soldering iron
- wire stripper
- HD20 crimping tool (this one is expensive, I know*)
- STLink V2 (optional - you can flash blue pill over uart) 
- 3D printer (optional, for fancy case)

Bill of materials:
- DSub-15 female connector
- pins for DSub-15 connector
- STM32F1 blue pill board
- wire
- solder wire

Software:
- STM32CubeIDE (https://www.st.com/en/development-tools/stm32cubeide.html)
- 

### How to?

1. Download or clone the repo
2. Install STM32CubeIDE
3. Open the project
4. Compile it and download to Blue Pill
5. Make the wire connections, solder everything
6. Connect the joystick, plug the blue pill to your PC
7. Enjoy
