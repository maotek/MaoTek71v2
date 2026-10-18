# MaoTek 71 v2

A custom 3D printed handwired mechanical keyboard powered by QMK and an STM32F401 Blackpill.

## Features

- 71-key layout
- Rotary encoder for volume and media control
- Two programmable layers
- VIA-compatible keymap
- NKRO, Bootmagic, mouse keys, and media keys

## Build

From the QMK firmware root:

```sh
qmk compile -kb maotek71v2 -km default
qmk compile -kb maotek71v2 -km via
```

To flash, enter the STM32 DFU bootloader or use the boot key on layer 1:

```sh
qmk flash -kb maotek71v2 -km default
qmk flash -kb maotek71v2 -km via
```

Designed and maintained by [MaoTek](https://github.com/maotek).
