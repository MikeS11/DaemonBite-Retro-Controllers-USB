# DaemonBite SNES/NES USB Controller adapter
## Introduction
Note: This is the Dual Controller is slightly less optimized than the NES only code, and also scans 2 more controllers than the SNES and NES. If you want the absolute lowest latency, I would stick with the original codes but this should not add much more.

With this simple to build  adapter you can connect SNES and NES gamepads to a PC, Raspberry PI, MiSTer FPGA etc. The Arduino Pro Micro has very low lag when configured as a USB gamepad and it is plug n' play once it has been programmed. The NTT Data Keypad controller for SNES is also supported. The controller type is auto-detected.

## Parts you need
- Arduino Pro Micro (ATMega32U4)
- Male end of SNES or NES controller extension cable
- Heat shrink tube (Ø ~20mm)
- Micro USB cable

## Wiring
![Assemble1](images/snes-usb-adapter-wiring.png)

## License
This project is licensed under the GNU General Public License v3.0.
