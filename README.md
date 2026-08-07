# cheapinov2-vial-qmk-firmware
Firmware files for the cheapino built against the latest vial-qmk version (as of 8/6/2026 at time of first commit)


cheapino_vial.uf2 is the firmware file itself to be flashed to the cheapinov2 controller. This is built defaulting to the default keymap from the original cheapino repository, with 14 dynamic layers and built using the top pinky keys on both half as the vial unlock keys.

dvorak-qwerty-brm-bleys43.vil is my vial config save based on a dvorak base layer, a toggle-able qwerty layer, nav, num/symbol, function/media and mouse layer. There are many macros and combos that are tailored to my workflow, many of which are focused on navigating tmux in the terminal. Included in case anyone finds it interesting or useful.

cheapino directory is the source code for compilation of this firmware. To successfully compile, you must place it in the vial-qmk/keyboards directory of your vial-qmk source tree once you have cloned it from the vial project's git repository.
