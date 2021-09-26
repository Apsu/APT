# Atreus Keymap

Since I use an Atreus keyboard, I have a custom setup for the rest of my keymap that works in conjunction with the layout.

The JSON config file for the Keyboard.io graphical configurator [Chrysalis](https://github.com/keyboardio/Chrysalis) is included [here](APT.json).

## Goals

- Provide easy access to modifiers without interfering with typing
- Use symmetric mods so either hand can hold down mods as needed to press a key on the other hand
- Put layer keys on thumbs so layers + mods are still usable on either hand
- Make it easy to access any printing character by only holding at most one other key
    - For base layer, shift can be held
    - For num layer, the shifted syms have dedicated key spots, so only the layer key needs to be held
- Add a bunch of miscellaneous keys and useful shortcuts
    - These are put in the nav layer since there's a lot of extra room

## Base

The base layer is the APT layout, with some additional punctuation on the extra middle keys.

![APT](Layer1.png)

Mods are symmetric in the bottom corners, and extra layers are dual-function on the thumb home keys.

In addition, the remaining common base-layer symbols `-=[]` live on the right-hand mods, giving easier access to them without removing mod symmetry and hand alternation.

## Nav/Shortcuts

In addition to navigation and shortcuts, this is also where `Escape`, `Caps Lock`, `Menu`, `Print Screen`, `Scroll Lock`, `Pause`, and `Num Lock` live. All blank keys are passthrough.

![Nav](Layer2.png)

## Number/Symbol

This layer is setup to make it easier to only have to hold one key and press one other in order to produce any letter, number, or symbol. 

![Num](Layer3.png)

## Function

Lastly, just in case they're needed, the function keys are added to their own layer as well, and mods are still usable here with them.

![Num](Layer4.png)