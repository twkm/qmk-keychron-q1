## Bacon Work and Play

Version: 1.6

Custom keymap for the [Keychron Q1 (ANSI, v1)](https://www.keychron.com/products/keychron-q1-qmk-custom-mechanical-keyboard) ([PDF](bacon_work_and_play_1_6.pdf)).

### What it Does

- Defines custom layers and layouts
- Sets default LED colour and animation

### How to Use

\1. Clone this project into the keymaps folder, changing "~qmk_firmware" folder reference, if needed:

`git clone git@github.com:twkm/qmk-keychron-q1.git ~/qmk_firmware/keyboards/keychron/q1/ansi/keymaps/bacon_work_play`

\2. Compile using QMK.

\3. Flash keyboard using compiled image. 

### Tools

- [QMK Configurator](https://config.qmk.fm/#/keychron/q1/ansi/LAYOUT_ansi_82)
- [QMK Firmware](https://github.com/qmk/qmk_firmware)
- Can create keymap.c from a Configurator json file using `qmk json2c` command
