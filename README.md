# CTRL-AI-Macropad
<img width="1419" height="571" alt="Screenshot 2025-12-28 222231" src="https://github.com/user-attachments/assets/f7881569-19a2-49f7-9838-46889130ec1f" />

## What is CTRL?
CTRL is a custom-built programmable macropad designed for productivity,
automation, and future AI-assisted workflows. It features mechanical
switches, a rotary encoder, and an IPS display, powered by a Raspberry Pi Pico.

  ![0111(2)](https://github.com/user-attachments/assets/c879a765-367e-4b05-86a0-af208b819c26)


-------------------------------------------------------------------------------------------------
## Purpose 
I wanted to design a fully custom keyboard input device from scratch — including
PCB design, firmware, and enclosure — to better understand hardware design
and embedded systems. This project is also built with future software
customization & productivity in mind , ensuring optimization of the project
 
 ![0111(1)](https://github.com/user-attachments/assets/4551a615-e77e-4ec2-b289-c4d70b81c0fa)

-------------------------------------------------------------------------------------------------
## Features
- 6 mechanical keys (MX cherry switches)
- Rotary encoder with push button
- IPS SPI display
- Raspberry Pi Pico (RP2040)
- Fully custom PCB
- Open-source hardware & firmware
-------------------------------------------------------------------------------------------------
## Hardware
- The PCB was designed in KiCad (opensource software) & fusion 360
- 2-layer board
- Diode-protected key matrix
- SPI-connected IPS display
all PCB files in `/hardware/kicad`.

![0111(3)](https://github.com/user-attachments/assets/b63ff671-658b-4ba5-a15d-6402b3deaaeb)

-------------------------------------------------------------------------------------------------
## Firmware
The firmware is written using KMK and CircuitPython.
Currently, it supports basic key mapping and encoder input.

there are also future plans for the hackpad 
Future plans include:
- Dynamic key remapping
- Software-based configuration tool
- Display-driven UI
Firmware is in `/firmware`.

-------------------------------------------------------------------------------------------------
## Case
The enclosure is designed in Fusion 360 (personal use).
[STEP and source files are included in `/case`.]

![0111](https://github.com/user-attachments/assets/2931899d-0f27-4e3b-9777-3a29c8599f60)

-------------------------------------------------------------------------------------------------
## Images
<img width="1139" height="808" alt="Pcb" src="https://github.com/user-attachments/assets/395aed8f-0ed4-41ae-b612-e8b5305dca23" />

<img width="803" height="557" alt="assembled-case" src="https://github.com/user-attachments/assets/95c67418-6ab1-4e1c-b6ce-ca660ebd0613" />

-------------------------------------------------------------------------------------------------
## BOM
The complete BOM with purchase links is available in `/hardware/bom.csv`.

Services that will be used 
- JLCPCB
- Robu.in (for india)
- online 3d printing services (if not provided)
-------------------------------------------------------------------------------------------------
## License
This project is open-source hardware and uses the MIT License

