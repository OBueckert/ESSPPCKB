# ESSPPCKB

Happy Birthday Evan!

This is the repository for the Evan Super Secret Party Planning Committee Macro Keyboard!

This macro keyboard is powered by the Quantum Mechanical Keyboard Firmware: https://qmk.fm/

It uses a fork of this firmware called Vial: https://get.vial.today/

This code is the actual project files for the keyboard. This is just an explaination of how this stuff works if you're interested. You shouldn't have to use any of this code.

The reason we use vial is to be able to store keymaps (the thing that tells qmk which key does what) on the EEPROM instead of on the flash. This allows the user to change keymaps without reflashing the keyboard every time (which requires a reset of the processor). You simply run the vial GUI, change what you want, and close the software. You don't even have to press a button to upload code.

If you would just like to change the keymap on your keyboard, use this software: https://get.vial.today/download/

# Reflashing

# NOTE: Reflashing should not be necessary in any circumstances.

You will have to have setup the vial firmware in advance in order to reflash this keyboard. Then, you should be able to put this project in your "qmk_firmware/keyboards" directory.
