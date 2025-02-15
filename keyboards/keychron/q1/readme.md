# Keychron Q1

![Keychron Q1](https://cdn.shopify.com/s/files/1/0059/0630/1017/t/5/assets/pf-823ebdc7--1073.jpg)

A customizable 75% keyboard.

* Keyboard Maintainer: [Keychron](https://github.com/keychron)
* Hardware Supported: Keychron Q1
* Hardware Availability: [Keychron](https://www.keychron.com)

Make example for this keyboard (after setting up your build environment):

    make keychron/q1/rev_0100:default

Flashing example for this keyboard:

    make keychron/q1/rev_0100:default:flash

Getting into bootloader mode: Hold reset key under spacebar while plugging in.

Compiling and flashing the default keymap with qmk tool (you can put the keyboard in bootloader mode after running the flash command)                                 xxxxxc:
```
qmk compile -km default
qmk flash -km default
```


**Reset Key**: Hold down the key located at *K00*, commonly programmed as *Esc* while plugging in the keyboard.

See the [build environment setup](https://docs.qmk.fm/#/getting_started_build_tools) and the [make instructions](https://docs.qmk.fm/#/getting_started_make_guide) for more information. Brand new to QMK? Start with our [Complete Newbs Guide](https://docs.qmk.fm/#/newbs).
