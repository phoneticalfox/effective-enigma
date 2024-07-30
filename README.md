## Disclaimer

This guide is provided as-is, without any warranty. Use at your own risk. While this method is designed to be safe, incorrect use can potentially damage your motherboard. If you're unsure about any step, consult with MSI support or a professional technician.

# MSI Z77A-GD65 Dual BIOS Recovery Guide

This guide provides instructions for recovering from a corrupted dual BIOS situation on the MSI Z77A-GD65 motherboard using the USB BIOS Flashback feature.

## Overview

The MSI Z77A-GD65 motherboard features a dual BIOS system for redundancy. If both BIOS A and BIOS B become corrupted, you can use the USB BIOS Flashback feature to recover without needing to boot into the BIOS or OS.

## Prerequisites

- MSI Z77A-GD65 motherboard
- USB drive (8GB or larger, FAT32 formatted)
- Access to a working computer for file download and USB preparation
- Stable power supply

## Steps to Recover Corrupted BIOS

1. **Download the BIOS File**
   - Visit the [MSI Z77A-GD65 support page](https://www.msi.com/Motherboard/Z77AGD65/support)
   - Navigate to the "BIOS" section
   - Download the latest BIOS version for your motherboard

2. **Prepare the USB Drive**
   - Format a USB drive to FAT32 file system
   - Rename the downloaded BIOS file to `MSI.ROM` (all uppercase)
   - Copy `MSI.ROM` to the root of the USB drive (looking something like: `USB:`/`root-of-drive`/`MSI.ROM`)

3. **Perform USB BIOS Flashback**
   - Plug the USB drive into the designated USB BIOS Flashback port on your motherboard
     (Usually marked in a different color, refer to your motherboard manual for exact location)
   - Ensure the PC is powered off but still plugged into a power outlet
   - Press and hold the BIOS Flashback button on the back of your motherboard for about 3 seconds
   - Release the button when the LED starts flashing
   - The flashing process will begin automatically and may take several minutes
   - Wait until the LED stops flashing, indicating the process is complete

4. **Post-Recovery Steps**
   - Remove the USB drive
   - Power on your PC
   - If it boots successfully, enter BIOS setup (usually by pressing Delete during startup)
   - Load optimized defaults
   - Configure your BIOS settings as needed
   - Save changes and exit

## Troubleshooting

- If the PC doesn't boot after flashing, try clearing CMOS:
  1. Unplug the power cord
  2. Remove the CMOS battery for about 5 minutes
  3. Replace the battery and power cord
  4. Try booting again

- If USB BIOS Flashback doesn't seem to start (LED doesn't flash):
  - Ensure you're using the correct USB port
  - Try a different USB drive
  - Double-check that the BIOS file is named correctly and is in the root directory

- If recovery fails multiple times, contact MSI support or consider RMA service

## Safety Precautions

- Ensure stable power during the entire flashing process
- Do not interrupt the flashing process
- Use a high-quality USB drive to minimize the risk of corruption during flashing

## Additional Resources

- [MSI Z77A-GD65 User Manual](https://www.msi.com/Motherboard/Z77AGD65/support#down-manual)
- [MSI BIOS Flashback+ Video Guide](https://www.youtube.com/watch?v=iTkXunUAriE)
