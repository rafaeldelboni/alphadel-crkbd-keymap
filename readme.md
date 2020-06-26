# The AlphaDel Crkbd Layout

# Base Layer
```
 ,-----------------------------------------------------.                    ,-----------------------------------------------------.
    KC_TAB,    KC_Q,    KC_W,    KC_E,    KC_R,    KC_T,                         KC_Y,    KC_U,    KC_I,    KC_O,   KC_P,  KC_BSPC,\
 |--------+--------+--------+--------+--------+--------|                    |--------+--------+--------+--------+--------+--------|
   KC_LCTL,    KC_A,    KC_S,    KC_D,    KC_F,    KC_G,                         KC_H,    KC_J,    KC_K,    KC_L, KC_SCLN, KC_QUOT,\
 |--------+--------+--------+--------+--------+--------|                    |--------+--------+--------+--------+--------+--------|
   KC_LSFT,    KC_Z,    KC_X,    KC_C,    KC_V,    KC_B,                         KC_N,    KC_M, KC_COMM,  KC_DOT, KC_SLSH, KC_RSFT,\
 |--------+--------+--------+--------+--------+--------+--------|  |--------+--------+--------+--------+--------+--------+--------|
                                       KC_LGUI,   LOWER,  KC_SPC,     KC_ENT,  RAISE,  KC_RALT \
                                     `--------------------------'  `--------------------------'
```
# Lower Layer
```
 ,-----------------------------------------------------.                    ,-----------------------------------------------------.
    KC_ESC,    KC_1,    KC_2,    KC_3,    KC_4,    KC_5,                         KC_6,    KC_7,    KC_8,    KC_9,    KC_0, KC_BSPC,\
 |--------+--------+--------+--------+--------+--------|                    |--------+--------+--------+--------+--------+--------|
   KC_LCTL, XXXXXXX, XXXXXXX, XXXXXXX, XXXXXXX, XXXXXXX,                      KC_LEFT, KC_DOWN,   KC_UP,KC_RIGHT, XXXXXXX, XXXXXXX,\
 |--------+--------+--------+--------+--------+--------|                    |--------+--------+--------+--------+--------+--------|
   KC_LSFT, XXXXXXX, XXXXXXX, XXXXXXX, XXXXXXX, XXXXXXX,                      XXXXXXX, XXXXXXX, XXXXXXX, XXXXXXX, XXXXXXX, XXXXXXX,\
 |--------+--------+--------+--------+--------+--------+--------|  |--------+--------+--------+--------+--------+--------+--------|
                                       KC_LGUI,   LOWER,  KC_SPC,     KC_ENT,   RAISE, KC_RALT \
                                     `--------------------------'  `--------------------------'
```

# Raise Layer
```
 ,-----------------------------------------------------.                    ,-----------------------------------------------------.
    KC_ESC, KC_EXLM,   KC_AT, KC_HASH,  KC_DLR, KC_PERC,                      KC_CIRC, KC_AMPR, KC_ASTR, KC_LPRN, KC_RPRN, KC_BSPC,\
 |--------+--------+--------+--------+--------+--------|                    |--------+--------+--------+--------+--------+--------|
   KC_LCTL, XXXXXXX, XXXXXXX, XXXXXXX, XXXXXXX, XXXXXXX,                      KC_MINS,  KC_EQL, KC_LCBR, KC_RCBR, KC_PIPE,  KC_GRV,\
 |--------+--------+--------+--------+--------+--------|                    |--------+--------+--------+--------+--------+--------|
   KC_LSFT, XXXXXXX, XXXXXXX, XXXXXXX, XXXXXXX, XXXXXXX,                      KC_UNDS, KC_PLUS, KC_LBRC, KC_RBRC, KC_BSLS, KC_TILD,\
 |--------+--------+--------+--------+--------+--------+--------|  |--------+--------+--------+--------+--------+--------+--------|
                                       KC_LGUI,   LOWER,  KC_SPC,     KC_ENT,   RAISE, KC_RALT \
                                     `--------------------------'  `--------------------------'
```

# Adjust Layer
```
 ,-----------------------------------------------------.                    ,-----------------------------------------------------.
     RESET,  RGBRST, XXXXXXX, XXXXXXX, XXXXXXX, XXXXXXX,                      XXXXXXX, XXXXXXX, XXXXXXX, XXXXXXX, XXXXXXX, XXXXXXX,\
 |--------+--------+--------+--------+--------+--------|                    |--------+--------+--------+--------+--------+--------|
   RGB_TOG, RGB_HUI, RGB_SAI, RGB_VAI, XXXXXXX, XXXXXXX,                      XXXXXXX, XXXXXXX, XXXXXXX, XXXXXXX, XXXXXXX, XXXXXXX,\
 |--------+--------+--------+--------+--------+--------|                    |--------+--------+--------+--------+--------+--------|
   RGB_MOD, RGB_HUD, RGB_SAD, RGB_VAD, XXXXXXX, XXXXXXX,                      XXXXXXX, XXXXXXX, XXXXXXX, XXXXXXX, XXXXXXX, XXXXXXX,\
 |--------+--------+--------+--------+--------+--------+--------|  |--------+--------+--------+--------+--------+--------+--------|
                                       KC_LGUI,   LOWER,  KC_SPC,     KC_ENT,   RAISE, KC_RALT \
                                     `--------------------------'  `--------------------------'
```

## Build environment

1) See [The Complete Newbs Guide To QMK](https://docs.qmk.fm/#/newbs).

2) Clone the QMK repository
```
git clone git@github.com:qmk/qmk_firmware.git
```
3) Clone this repository inside the following folder structure `keyboards/crkbd/keymaps/alphadel/`
```
git clone git@github.com:rafaeldelboni/alphadel-crkbd-keymap.git qmk_firmware/keyboards/crkbd/keymaps/alphadel
```

## Building Instructions

1) from the `qmk_firmware` directory run:
```
$ sudo make crkbd/rev1:alphadel                                                                                               <<<
```
