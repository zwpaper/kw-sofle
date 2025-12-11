# ZMK Config for Sofle Wireless

This repository contains the ZMK firmware configuration for the Sofle Wireless keyboard.

## Automated Build

Every time you push changes to this repository, a GitHub Action will automatically run to build the firmware. This process generates two firmware files:

- Firmware for the **Left** half
- Firmware for the **Right** half

You can find these firmware files in the artifacts of the GitHub Action run.

## Flashing Instructions

To flash the new firmware onto your keyboard:

1. **Enter Bootloader Mode**: Double-click the reset button on the keyboard half you want to flash.
2. **Connect**: A new external drive will appear on your computer.
3. **Flash**: Drag and drop the corresponding firmware file (e.g., left firmware for the left half) into the drive.
4. **Complete**: The keyboard will flash the firmware, disconnect, and reboot automatically.

Repeat the process for the other half if you have updated both.