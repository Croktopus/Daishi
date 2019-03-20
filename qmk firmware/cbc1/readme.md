Meta75 keyboard firmware
======================

The Meta75 is a 15x5 full-grid ortholinear keyboard "manufactored" by myself, using cheap Chinese PCB fabs, aliexpress switch sellers, a 3d printer, and a whole lot of help from people on the internet.
In particular, the base of the code for this keyboard's firmware is stolen from the xd75 firmware found here: https://github.com/qmk/qmk_firmware/tree/master/keyboards/xd75 so a big thanks to Benjamin Kesselring for all his hard work.
This isn't intended as a commercial product or anything, so if it does come to that I'll streamline the code, but for the time being you'll find I just commented out a bunch of stuff...

## Quantum MK Firmware

For more info on this firmware (and how to make it your own), head over to [qmk.fm](http://qmk.fm).

## Building

Download or clone the whole firmware and navigate to the keyboards/meta75 folder. Once your dev env is setup, you'll be able to type `make` to generate your .hex - you can then use the Teensy Loader to install the resulting .hex file, or have the `make` process install it using teensy.

### Default

To build with the default keymap, simply run `make meta75:default` from the root directory (i.e. two levels above this file), and to install via teensy, `make meta75:default:teensy`, also from the root directory.

### Other Keymaps

The "default" keymap included is essentially an ortho 65% layout, but basically any layout from a 5x15 keyboard like the XD75 will be compatible with the obvious code modifications (changing header file names referenced in the code).

Keymaps follow the format **__\<name\>.c__** and are stored in subdirectories under `keyboards/meta75/keymaps`

To build the firmware binary hex file for a specific keymap, and install it, using Teensy, just do `make` with a keymap like this:

```
$ make meta75:[default|<name>]
```

