# Box release

This script will release an entire box in Pokémon Scarlet/Violet.

#### How to use

- Download Joystick.hex
- Download the [Teensy Loader application](https://www.pjrc.com/teensy/loader.html) and inject Joystick.hex with the included instructions
- SAVE YOUR GAME and then disable auto save (I don't want to be responsible for accidentally releasing any valuable pokemon)
- Go to a full box that you want to release
- Put your cursor on the first Pokémon in your party
- Disconnect all controllers
- Plug in the Teensy board
- The board will stop by itself after clearing all boxes. 

# Item dupe

Script that dupes any items that can be held by a Pokémon

### How to use

- Download Joystick-Dupe.hex
- Download the [Teensy Loader application](https://www.pjrc.com/teensy/loader.html) and inject Joystick-Dupe.hex with the included instructions
- SAVE YOUR GAME and then disable auto save (just in case)
- Put your duped Koraidon/Miraidon in the second slot of your party
- Go to your first box then leave the menu
- Give the item you want to dupe to your duped legendary
- Put your cursor on the duped legendary
- Disconnect all controllers
- Plug in the Teensy board
- Enjoy !


(if you want to compile the dupe script just replace "TARGET = Joystick" with "TARGET = Joystick-Dupe" in the makefile)

# Slightly more text here:

Here's a link to the original repository which includes instructions on how to compile the code and the original project: https://github.com/bertrandom/snowball-thrower

# And of course:
Big thanks to [Bertrandom](https://github.com/bertrandom) for sharing this cool project and big thanks to everyone in the [Switch-Fightstick](https://github.com/shinyquagsire23/Switch-Fightstick) project !
