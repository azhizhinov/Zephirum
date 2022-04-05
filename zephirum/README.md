# Zephirum

## Description

This is a [LibrePCB](https://librepcb.org) project!

Despite having a look similar to many other ergo monoblock angled
keyboards, this build has a couple of unique features:

- it has been designed with LibrePCB.  This EDA tool deserves more
  love, so I published the project & library files under CC0 1.0
  licence (https://git.tuxfamily.org/zephirum/zephirum.git &
  https://git.tuxfamily.org/zephirum/keyboard_lplib.git)

- its MCU board is a Nucleo STM32WB55CG USB dongle (MB1293); it is
  surface mounted on the top to showcase it ☺

Regarding the other features, they are more classic:

- it has been designed for Kailh Choc switches with MBK keycaps
  (L=17.5mm × H=16.5mm)

- it is powered by ZMK; only USB HID is supported so far.  The sources
  are available here: https://git.tuxfamily.org/zephirum/zmk.git

- it uses an I²C 128x32 OLED screen (SSD1306)

## License

Creative Commons (CC0-1.0). For the license text, see [LICENSE.txt](LICENSE.txt).
