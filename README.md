# Gamer2040

**Gamer2040** is a portable game console powered by the Raspberry Pi Pico and written in MicroPython. It features a dynamic home screen, customizable settings (including background and volume), and supports a variety of games—all running smoothly on a vibrant 240x240px ST7789 display.

---

## Features

- **Dynamic Home Screen:** Easily browse and launch games from a visually engaging menu.
- **Customizable Settings:** Adjust background, volume, and more from an intuitive settings menu.
- **MicroPython Powered:** Simple, fast, and open-source—easy to modify or expand.
- **Compact Hardware:** Designed for portability and tinkering.

---

## Hardware Requirements

- **Mandatory:**
  - Raspberry Pi Pico or Pico W
  - MicroPython ≥ v1.22.2  
    _Note: Older versions are untested._
  - 240x240px ST7789 display
  - Jumper wires
  - Pushbuttons

- **Optional:**
  - Speaker
  - Batteries (for portability)

---

## Display Wiring Guide

| Pi Pico Pin | ST7789 Signal |  
|:-----------:|:-------------:|  
| GP8         | DC            |  
| GP9         | CS            |  
| GP10        | CLK           |  
| GP11        | MOSI          |  
| GP12        | RST           |  
| GP13        | BL            |  
| GND         | GND           |  
| 3V3         | VCC           |  

---

## Getting Started

1. **Flash MicroPython** onto your Raspberry Pi Pico.  
   [Download MicroPython](https://micropython.org/download/)  
2. **Connect the ST7789 display** as shown above.
3. **Wire up pushbuttons** to your chosen GPIO pins.
4. (Optional) Add a speaker for sound and batteries for portability.
5. **Clone this repository** and upload the files to your Pico.
6. **Power on and start gaming!**

---

## Credits

Gamer2040 is inspired by the awesome work on  
- [PicoGameBoy](https://github.com/YouMakeTech/Pi-Pico-Game-Boy)  
- [PicoBoy](https://github.com/HalloSpaceBoy5/PicoBoy)  

---

## License

This project is open-source. See the [LICENSE](LICENSE) file for details.

---

### Happy Gaming!
