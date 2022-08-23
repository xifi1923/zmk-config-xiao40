# Xiao40 ZMK Config Repo

This is a repository for the Xiao40 keyboard: a wireless 40%.

![](https://i.imgur.com/7OZHs3J.png)

![](https://i.imgur.com/UkVDD4t.png)

## Build Guide

TBA

## Default Keymap

![](https://i.imgur.com/uopymB9.png)

Multiple layout options available as seen above.

Holding left spacebar activates the `LOWER` layer and keys pressed will activate the lower left legend. The same applies for the right spacebar and the `RAISE` layer.

Holding both `LOWER` and `RAISE` layers activates the 3rd layer. The functions are noted as the bottom legends (front face) of the keys in the iamge.

## Editing a keymap

1) Edit the `config/app/boards/shields/` file to change your keymap.

- https://zmkfirmware.dev/docs/behaviors/key-press
- https://zmkfirmware.dev/docs/behaviors/layers
- and pretty much everything in the "Behaviors" section, plus
- https://zmkfirmware.dev/docs/codes/

2) Head over to the Actions tab at the top of the repository.

3) Click on the latest workflow run.

- If you did your keymap correctly, there should be a green checkmark to the left.

5) Click on the firmware file to download. Unzip it somewhere too.

6) Plug the USB connector in, and double press the reset button twice quickly (Has to be <500 ms apart).

- The reset button is located underneath the left shift.

7) Drag and drop the UF2 file you unzipped to the mass storage device that appeared.
