# NES-controller-input-switchboard
The switchboard is essentially a 2:2 6-channel multiplexer, with one output being routed to an RP2040 for processing and a USB Keyboard output as opposed to exposing it directly.
Part of a larger homemade arcade project, I want to be able to have a embedded controller with arcade buttons and an external connector for external controllers or a light zapper, to be routed to an NES for retro games, as well as a ZimaBoard or Pi 4 (or other computer, via USB) for modern games

## Features:
- 6 channel 2:2 multiplexer
- ability to switch a power line
- NES Controller signal decode
- USB-HID keyboard output for decoded signals
- Separate data and power USB-C connectors
- ~~Exposed GPIO for expansion~~


<img width="1406" height="558" alt="image" src="https://github.com/user-attachments/assets/2ce03a60-d389-4eba-9ffc-dc2e4c19f39d" />

## Schematics
<img width="947" height="669" alt="image" src="https://github.com/user-attachments/assets/b5fb0da6-4cbb-4ef2-8807-060963402cd1" />
<img width="947" height="669" alt="image" src="https://github.com/user-attachments/assets/7f3d9be5-b7d4-4803-a8ec-03606ba998a9" />
<img width="947" height="669" alt="image" src="https://github.com/user-attachments/assets/cad9fa51-807b-439b-8b4d-e75514c7c795" />

## Board
<img width="973" height="860" alt="image" src="https://github.com/user-attachments/assets/2e57f564-1c9e-413a-b47f-24308dd76a88" />

## Firmware
Thanks to [Print 'N Play](https://www.youtube.com/@PrintNPlay) ([Github](https://github.com/printnplay)) for opensourcing a [CircuitPython Script](https://github.com/printnplay/Pico-MicroPython/blob/main/NES2USB.py) that already performs my desired functionailty. If I feel up to it I may rewrite it myself in the future.

## JLCPCB order
<img width="1670" height="711" alt="image" src="https://github.com/user-attachments/assets/3587de38-7ebb-4619-87e3-83d81e0a85b6" />

## Credits
This project uses work from:
- [Kicad](https://www.kicad.org/)
- [CircuitPython](https://circuitpython.org/)
- [Print 'N Play](https://github.com/printnplay)
- [Hack Club!](https://hackclub.com)
