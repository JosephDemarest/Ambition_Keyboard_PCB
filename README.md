
---

# Ambition Keyboard

This repository contains all of the PCB related files for the Ambition Keyboard. The project is currently in development and is not yet complete. 

## Project Status

The keyboard case is currently being designed in CAD. The PCBs have been ordered and are expected to arrive soon. The firmware will be based on QMK.

## Repository Contents

This repository contains the following:

- Schematic files
- PCB layout files
- Renderings of the PCB
- Other related files

## Setup / Build / Installation

### Firmware

The firmware for the Ambition Keyboard will be based on QMK. The QMK firmware is a powerful open-source firmware for keyboards that allows for customization and control over every aspect of your keyboard.

To setup the firmware, follow these steps:

1. Clone the QMK firmware repository: `git clone https://github.com/qmk/qmk_firmware.git`
2. Navigate to the keymaps directory for the Ambition Keyboard (this will be added once the keyboard is supported by QMK).
3. Modify the keymap to your liking.
4. Build the firmware with `qmk compile`.

### Flashing the Firmware

After building the firmware, you will need to flash it onto your keyboard. Here are the general steps to do this:

1. Connect your keyboard to your computer.
2. Put your keyboard into bootloader mode. This is usually done by pressing the reset button on the PCB, but the method can vary depending on the keyboard.
3. Use QMK Toolbox or a similar tool to flash the firmware onto your keyboard. In QMK Toolbox, you would select the .hex or .bin file you compiled earlier, select the correct microcontroller, and then click the "Flash" button.

Please refer to the QMK documentation for more detailed instructions and troubleshooting tips.

### Hardware

Once the PCBs arrive and have been tested, you will need to solder the components onto the PCB. This includes switches, LEDs, and any other components used in the design.

### Case

Once the case design is complete, it will need to be manufactured. The method of manufacturing will depend on the design and materials used. I am planning on 3-d Printing.

## Contributing

As this project is still in development, contributions are welcome. Please feel free to submit issues and pull requests.

---

![Render](https://github.com/JosephDemarest/Ambition_Keyboard_PCB/blob/main/render.png)
![PCB](https://github.com/JosephDemarest/Ambition_Keyboard_PCB/blob/main/pcb.png)
![led_key_matrix](https://github.com/JosephDemarest/Ambition_Keyboard_PCB/blob/main/led_key_matrix.png)
![Controller](https://github.com/JosephDemarest/Ambition_Keyboard_PCB/blob/main/Controller.png)
