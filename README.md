# ATmega32U4 Macropad

For my first-ever PCB project, I've designed a 9 key low-profile macropad with a rotary encoder and oled screen. My intention was to keep costs minimal while retaining features found in most contemporary macropads. I began this journey after soldering my very own low-profile Lily58 build. While the Lily58 takes up minimal desk space and is very ergonomic, I found myself suffering from the small key count and lack of special features such as rotary encoders. Since I couldn't find any affordable alternative online, I set out to build my very own low-profile macropad to complete my desk setup.

![Macropad Render](https://github.com/vlee6/Macropad/blob/main/Images/Full.png)

### Specs:
- ATmega32U4 Microcontroller
- 9 Kailh Hotswap Sockets (Low-profile Choc V1)
- WS2812B-2020 South-Facing Per-Key RGB Lighting
- Bourns PEC11R Rotary Encoder Switch
- 128x32 Oled I2C Display Module
- Easy-to-assemble 3D printed case
- (soon to be) VIA Compatible

### How is this different from the other macropads?
- Low-profile switches (like the Choc V1s I'm using in this build) are 40% shorter than regular mechanical keyboard switches.
- All components are directly soldered onto the board, no pro-micro (or equivalent devkit) necessary
- Per-key RGB lighting, not just underglow
- Estimated total cost of $30 to make, including all components and switches

### Assembly Instructions:
You will need...
- A switch for the reset buttom
- 9 Kailh Choc V1 switches of your choice
- 9 Choc V1 1U keycaps, I'm using clear Chosfox ones but MBK Choc keycaps will also work
- 9 WS2812B-2020 LEDs
- PEC11R-4015F-S0024 rotary encoder or equivalent
- A soldering setup
- Various electrical components that can be found on the [full parts list](https://docs.google.com/spreadsheets/d/1zmoziKfNFVxXU5fcjUS9J8uJfZayq2XkwIlthU0o6MI/edit?usp=sharing)

1. The board can be ordered with the production files in this repository (BOM and CPL included). If you are manufacturing with JLCPCB, have them assemble the bottom side (you will only need to solder the LEDs on the top side).
2. After printing out the top and bottom case from the STLs in this repository, they can be sandwiched to the PCB with four 4mm M2 screws (inserted from the bottom). If your PCB and case is aligned properly, the switches will snap in easily.

### Image Dump
![PCB Back](https://github.com/vlee6/Macropad/blob/main/Images/PCB%20Back.png)
![PCB Front](https://github.com/vlee6/Macropad/blob/main/Images/PCB%20Front.png)
