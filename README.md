# Raspberry-Video-Player
This is a bare-bones tutorial for installing a Raspberry Pi video player from scratch.

## Hardware
We have tested this tutorial with a Raspberry PI 3b & 4b, but given that we're using only basic pre-installed functions, it should (theoretically) work on a standard Raspberry PI Zero.

- [Raspberry Pi Zero](https://www.raspberrypi.org/products/raspberry-pi-zero/)
- [Raspberry Pi 3A+](https://www.raspberrypi.org/products/raspberry-pi-3-model-a-plus/)
- [Raspberry Pi 4b](https://www.raspberrypi.org/products/raspberry-pi-4-model-b/)

You will also need:

- An SD card (cf. below)
- A Keyboard (during setup)

## SD Card
We start with a blank SD card for the Raspberry OS system. You will also place your video on this card in a later step. Given that we are using Raspberry OS Lite, we can get away with tiny sizes (2GB, 4GB, ...) for the SD Card. Remember to have enough space for both the OS itself and your video(s).

- SD Card Tests for Raspberry
  - [Raspberry PI Micro SD Cards](https://www.tomshardware.com/best-picks/raspberry-pi-microsd-cards)
- Current cards I've been using:
  - [SanDisk MAX ENDURANCE microSDHC](https://www.amazon.fr/dp/B084CJ96GT)
  - [SanDisk Ultra MicroSDHC](https://www.amazon.fr/gp/product/B073K14CVB)

## Raspberry OS
1. Download the [Raspberry Pi Imager](https://www.raspberrypi.org/software/) to install Raspberry OS onto your SD Card
  - <https://www.raspberrypi.org/software/operating-systems/>
2. Open the Raspberry Pi Imager software and `CHOOSE OS` to select the operating system you wish to install. We are going to choose the 'Lite' version. Select `Raspberry PI OS (other)` > `Raspberry Pi OS Lite (32-bit)`
3. Insert your blank SD Card into your computer and select it under `Storage`
4. `Write` the SD to your card


