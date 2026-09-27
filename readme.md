# Lily58 Manum45


these are adaptions to the lily58 qmk config for my hw adaptions.
initially copied from qmk commit b1aea2556040c28d58d611c8aef0082b5780bb6d


## my adaptions
### Fix for Right Half Right Column Bonked
Column is now connected to PF5 instead of PF6 because I fried one of the pins.
Adapt qmk_firmware\keyboards\lily58\rev1\keyboard.json:
matrix_pins -> cols -> change F6 to F5

Useful links:

ATmega32U4 (controller of pro micro) data sheet w/ pinout: https://ww1.microchip.com/downloads/en/DeviceDoc/Atmel-7766-8-bit-AVR-ATmega16U4-32U4_Datasheet.pdf
Promicro Pinout: https://imgur.com/wMNx2u6

## Original readme

Lily58 is 6×4+5keys column-staggered split keyboard.

![Lily58_01](https://user-images.githubusercontent.com/6285554/50394214-72479880-079f-11e9-9d91-33fdbf1d7715.jpg)
![2018-12-24 17 39 58](https://user-images.githubusercontent.com/6285554/50394779-05360200-07a3-11e9-82b5-066fd8907ecf.png)
Keyboard Maintainer: [Naoki Katahira](https://github.com/kata0510/) [Twitter:@F_YUUCHI](https://twitter.com/F_YUUCHI)  
Hardware Supported: Lily58 PCB, ProMicro  
Hardware Availability: [PCB & Case Data](https://github.com/kata0510/Lily58)

Make example for this keyboard (after setting up your build environment):

    make lily58:default

See the [build environment setup](https://docs.qmk.fm/#/getting_started_build_tools) and the [make instructions](https://docs.qmk.fm/#/getting_started_make_guide) for more information. Brand new to QMK? Start with our [Complete Newbs Guide](https://docs.qmk.fm/#/newbs).
