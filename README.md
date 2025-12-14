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

