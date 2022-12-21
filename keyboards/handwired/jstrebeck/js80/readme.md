# js80

![js80](https://i.imgur.com/CU8z8RS.png)

80% keyboard with extra keys on the left hand side.


* Keyboard Maintainer: [jstrebeck](https://i.imgur.com/CU8z8RS.png)
* Hardware Supported: Elite-Pi(RP2040)
* Hardware Availability: [Elite-Pi](https://keeb.io/products/elite-pi-usb-c-pro-micro-replacement-rp2040)

Make example for this keyboard (after setting up your build environment):

    make js80:default
    qmk compile -kb handwired/js80 -km default 

Flashing example for this keyboard:

    qmk flash -c -kb handwired/js80 -km default

See the [build environment setup](https://docs.qmk.fm/#/getting_started_build_tools) and the [make instructions](https://docs.qmk.fm/#/getting_started_make_guide) for more information. Brand new to QMK? Start with our [Complete Newbs Guide](https://docs.qmk.fm/#/newbs).

## Bootloader

Enter the bootloader in 3 ways:

* **Bootmagic reset**: Hold down the key at (0,0) in the matrix (usually the top left key or Escape) and plug in the keyboard
* **Physical reset button**: Briefly press the button on the back of the PCB - some may have pads you must short instead
* **Keycode in layout**: Press the key mapped to `QK_BOOT` if it is available
