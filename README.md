# NES-Style-Keyboard

## Description
A friend wanted a new keyboard. Instead of buying something off of the shelf, he asked me to build a custom 75% keyboard for him. I decided to go with something retro themed, and after searching a long list of keycap designs, I landed on an NES inspired set. That's when the idea of a custom NES inspired keyboard originated from.

## Features
The custom keyboard is a 75% keyboard, with a full function key and arrows, as well as a rotary encoder and a sliding potentiometer. The keyboard also has 6 rgb leds on the mid to bottom left of the keyboard, meant to display caps lock state and slider state (can be programmed to do more). The encoder is intended for music playback and volume control, but can be programmed to do whatever the user likes.

At the heart of the keyboard is the RP2040, a powerfull 32bit arm microcontroller, powering the keyboard matrix as well as the leds, the slider and the encoder. The keyboard consists of two PCBs, one for the main board and one for the power supply circuit. The daughterboard handles the conversion between 5V and the 3.3V required by the RP2040. Since it can be prone to failure, due to heat or a worn usb connector, the daughterboard is designed to be cheap and replaceable, yet reliable.

## Potential Future Features
- Two side buttons on the top right of the keyboard, inspired by the NES controller.
- A switch near the LEDs to cut power (usefull for battery powered version)
- Wireless/battery powered (includes daughterboard design to acquire a simple, yet compact charging circuit. 
