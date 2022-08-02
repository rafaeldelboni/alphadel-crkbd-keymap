# The AlphaDel Crkbd Layout

## Build environment

1) See [The Complete Newbs Guide To QMK](https://docs.qmk.fm/#/newbs).

2) Clone the QMK repository
```bash
git clone git@github.com:qmk/qmk_firmware.git
```

3) Clone this repository inside the following folder structure `keyboards/crkbd/keymaps/alphadel/`
```bash
git clone git@github.com:rafaeldelboni/alphadel-crkbd-keymap.git qmk_firmware/keyboards/crkbd/keymaps/alphadel
```

## Building Instructions

1) from the `qmk_firmware` directory run:
```bash
qmk compile -kb crkbd/rev1 -km alphadel
```
